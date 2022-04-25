# 如何从大量的url中找出相同的url
## 题目描述
> 给定 a、b 两个文件，各存放 50 亿个 URL，每个 URL 各占 64B，内存限制是 4G。请找出 a、b 两个文件共同的 URL。

## 思路
### 分治策略

    把一个文件中的 URL 按照某个特征划分为多个小文件，使得每个小文件大小不超过 4G，这样就可以把这个小文件读到内存中进行处理了。

首先遍历文件 a，对遍历到的 URL 求 hash(URL) % 1000 ，根据计算结果把遍历到的 URL 存储到 a0, a1, a2, ..., a999，这样每个大小约为 300MB。使用同样的方法遍历文件 b，把文件 b 中的 URL 分别存储到文件 b0, b1, b2, ..., b999 中。这样处理过后，所有可能相同的 URL 都在对应的小文件中，即 a0 对应 b0, ..., a999 对应 b999，不对应的小文件不可能有相同的 URL。那么接下来，我们只需要求出这 1000 对小文件中相同的 URL 就好了。

接着遍历 ai( i∈[0,999] )，把 URL 存储到一个 HashSet 集合中。然后遍历 bi 中每个 URL，看在 HashSet 集合中是否存在，若存在，说明这就是共同的 URL，可以把这个 URL 保存到一个单独的文件中。

### 代码例子

``` java
package com.cxytiandi.sharding.controller;

import cn.hutool.core.io.file.FileWriter;
import cn.hutool.core.util.HashUtil;
import java.io.BufferedReader;
import java.io.File;
import java.io.FileInputStream;
import java.io.IOException;
import java.io.InputStreamReader;

/**
 * @author pdongzheng
 * @date 2022/4/23
 */
public class ReadFiile {

    public static void main(String[] args) throws IOException {

        File file = new File(
                "/Users/w/Desktop/sharding-jdbc/sjdbc-db-read-write-sharding-springboot/src/main/resources/a.txt");
        BufferedReader reader = new BufferedReader(new InputStreamReader(new FileInputStream(file)));
        String line = null;
        FileWriter[] fileWriters = new FileWriter[1000];
        for (int i = 1; i <= 1000; i++) {
            fileWriters[i - 1] = FileWriter.create(new File(
                    "/Users/w/Desktop/sharding-jdbc/sjdbc-db-read-write-sharding-springboot/src/main/resources/a_"
                            + i));
        }

        while ((line = reader.readLine()) != null) {
            int i = HashUtil.pjwHash(line);
            int i1 = i % 1000;

            fileWriters[i1 - 1].write(line + "\n", true);
        }
    }

}


```