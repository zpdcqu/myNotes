# ✍正文 

几乎每个软件或多或少都会有快捷键，由此来提高使用效率。几乎每个人都愿意相信快捷键是能够提高效率的，但常常还是一个鼠标走天下。
##  研发人员效率的最大障碍是什么

![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgWciciazkpOpwNJicEoBP1xZOAsF3SD0m3tRhVKjBagbaw1VxR9VWYRFkA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)鼠标，鼠标，还是tm的鼠标。

诚然，鼠标是现代计算机不可或缺的外设。它极大程度降低了使用计算机的门槛，但作为各自领域的专业人士，追求效率应当：**重（双手操作的）键盘，轻（单手操作的）鼠标**。

本文将以IDEA为例，笔者分享自己在使用快捷键上的一些实战心得。
- ##  IDEA快捷键模板如何选择？
  
  
  
  说明：每个软件的快捷键，（没有冲突的情况下）保持默认是最好的，**十分不建议自定义**
  
  关于IDEA快捷键模板这块，笔者得承认自己是走了好几年“弯路”的，经验教训在这里分享出来。
  
  如下图所示，这是笔者很长时间（2017-2021长达4年之久）使用的快捷键模板：基于**Eclipse快捷键模板**的**私人定制版**。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgIHibDl3MvFhQesfpq344v6ibk9P5knFX4vqWiaeIo1qWvIY3Tj01Vqzug/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)下面对这两个“关键词”进行解释解释。
### ✌Eclipse快捷键模板

对于大多数**新生代程序员**（2016年之后入行）来讲，Eclipse大概率只听过但没用过，那值得恭喜：没有快捷键切换的包袱。

IntelliJ IDEA相较于Eclipse是后起之秀，早已成为JVM生态IDE领域绝对霸主。如下图所示（2021年统计的结果）：JVM圈最受欢迎的IDE，IntelliJ IDEA可谓遥遥领先。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgoxBzTKCshMbYDzh0XLxMJicibPFpjl2qWbGiaicSTGl5ibwSmDtpW29oMHQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)IDEA超越Eclipse有几个关键时间点，留个印象：
- 2001年1月：首个IntelliJ IDEA版本正式发布
- 2012年12月：IntelliJ IDEA支持炫黑主题。也是这一年，IntelliJ IDEA的综合表现实现了对老牌免费IDE Eclipse的超越，然后慢慢侵蚀着它的市占率
- **2016年：这一年在市占率上，IntelliJ IDEA也完成了对Eclipse的超越**。自此，IntelliJ IDEA来到舞台中央，成为JVM圈使用最广泛的IDE
  
  奈何笔者入行较早，2015年8月就已入行（开始使用基于Eclipse的STS），**2017年8月**入职新公司才首次接触到IntelliJ IDEA。2年，你知道这2年我怎么过的吗？![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgYc8479kLFqPic3hFvScOGMCSJKW1v6puev5R4mDibVn2l1fptlCHa45w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)这2年经过不断操练，**Eclipse快捷键早已成为肌肉记忆**，难以“摆脱”。
  
  2017年入职新公司必须使用IntelliJ IDEA的时候，碍于工作压力，我毅然决定沿用Eclipse的快捷键习惯，该决定便是我走弯路的开始。
  
  当初为何没有选择适应IntelliJ IDEA而选择沿用Eclipse的快捷键呢？这可能就是没有逃脱人性的弱点喽：舒适区。
  
  回头想想，这是一个只看到短期收益而忽略了长期价值的决定，是不明智的。如果上天再给我一次机会，我觉得正确的做法是：**短期内（比如半年内）先沿用Eclipse的快捷键方案以确保入职新公司后不会因为IDE问题而让开发效率打折扣，但之后（比如半年以后）对公司业务、人员比较熟悉后，能腾出时间了就一定要记得回归“正道”，全面拥抱变化**。
  
  笔者目前情况：已全部切回IntelliJ IDEA原生方式（默认的Mac OS快捷键模板），可喜可贺😄。
### ✌个人定制版

每个IDE都提供自定义快捷键的能力，IntelliJ IDEA自然也不例外。所以，我在这里又走了弯路：自定义了很多快捷键。

**我自定义了不少快捷键，好处是：自个用起来更顺手。但缺点非常明显：在其它人电脑上，我就像个“盲人”**。

自定义虽好，但也不要贪用哦。个人经验，若真需要DIY快捷键，那么：只做增加，不做修改，以保持和别人的最大公约数不会改变，自然也就拥有更好的“兼容性”。

> 

说明：快捷键表面看起来是私有行为，但其实它的普适性也是非常重要的
##  IntelliJ IDEA快捷键

接下就是“正文”了，笔者将自己常用的一些快捷键分享出来，供你参考。按照功能大类，分别展开。
### ✌导航/查找物件

在我眼中，这部分最重要的。

查找的重要性不言而喻，如何能快速定位到自己想要的类、文件、地点，将能直接体现出对IDEA的熟练程度，自然也会节约你非常非常多的时间。
#### 终极查找/导航

| Action Name | Key |
| ---- | ---- | ---- |
| Find Action... | command + shift + A |

上来就放大招：终极导航。一般的快捷键是执行某个Action，而它是**查找Action**，只需知道Action Name就能通过它（间接）导航过去，并且还帮你显示了对应快捷键哦。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVguGtuvicS4icJdCDMsXw3db4jyaV4mNNs1r2d5eTHdly5yo8zlZcpoXQA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)说实话，此快捷键笔者使用得并不多，毕竟通过它得经过2步才能“到达”目的地，但它对“新手”是很友好的，所以也推荐一下。
#### 打开/查找类

| Action Name | Key |
| ---- | ---- | ---- |
| Go to Class... | command + o |

IntelliJ IDEA里笔者认为最最最常用的快捷键，甚至**没有之一**。

![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVg6w4ibbcMkt53YwceGvoibtPgvdia6icIO22tk0ibE9Vea79kXt9qnmQA1ag/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1) `command + o` 在整个操作系统层面都具有非常明确的语义，所有用户都知道不需要“教训”。该快捷键在IDEA里被定义为查找/打开类，足矣见得它的高频性和重要性。

其实，不仅仅是IDEA，IntelliJ旗下的其它IDE产品都赋予了 `command + o` 非常重要的语义，如：**goland**和**DataGrip**![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgsV1LcprhHL2AZBOPxtK7mF7gOsuAQxvOSwX1ycbAwtPPnJ7Nachicfg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgibH1EwWIp3OsxSRoec4Il4EsSDLbGOcAPVj0y30F2ibUS9r6RNYeFuDw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)Tips：这种查找方式只匹配类名/表名/go文件名，不关心里面的内容，所以**检索速度非常非常非常快**。
##### 小技巧

有时候需要打开某个二方、三方库里的某个类的源代码，使用 `command + o` 找对应的类可能找不到：如**ArrayList**![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVg8PD9yChic8GPcTDpmY9icFfRic8Y67d9kOLE2EAZ7uQf9egeFxLcBgPkw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)默认情况下 `command + o` 检索的scope范围是：Project Files（当前工程）。上图可以看到（当前工程）没有找到ArrayList，IDEA非常“智能”的告诉了你如何去做：将搜索范围改为 `All places` 。

> 

说明：具有**确定性**的搜索结果能给予用户最好的使用体验，而并非检索出来一大推结果还需人工二次筛选，（无法盲操作）大大降低效率。**确定性**一般通过缩小检索范围 + AI人工智能推测来实现，IntelliJ IDEA就是这么做的，很高级

将搜索范围改为 `All places` 有两种做法：
- 使用鼠标点击选择：依旧没有脱离鼠标，不推荐![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgvUztMWRAP4KCtV39dPibGSqqbFsoK4VMotbMQXpYEZVficap5DTSr5gg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)
- **再按一次command + o：全键盘操作，推荐**通过 `command + o` 可以实现Project Files和All Places的自由切换，非常方便。
  
  另外，还有一个查找小技巧是**模糊搜索**，也很常用。比如你在检索时是否遇到这种情况：
- 不记得类的全名，只记得前面部分，或者中间部分，或者最后部分，甚至只记得零零碎碎的几个字母
- 类名太长，不想全部输入（太慢）
  
  举个栗子，要打开 `EntityManagerFactoryDependsOnPostProcessor` 这个类，我的做法是只在搜索框里这么输入就可以迅速打开我想要的：![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgu5r5gFUetT6ciah2mDoDHOiaA9Cz3H5bYUg4LuxsIHJ9zKSdsjZm6slA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)
  
  说明：从Eclipse迁移过来的小伙伴喜欢使用 `*` 这列通配符去模糊匹配，在IntelliJ IDEA里就duck不必这么做了，因为它足够智能（当然你写 `*` 也是阔以的）。
##### 使用误区

非常非常非常多同学在查找/打开类时有个使用误区：使用 `File in Files` 搜索一切，就像这样![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVg9dPGP1tgeKl4jBuzia8gtoAjtbJIZiczmUkgoD84Gde53dMIojbf7bicA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)对于这样的结果，你不觉得乱花渐欲迷人眼么？如果你也是这么做的，那么从看到笔者这篇文章开始就默默的改正哈。

问题来了，这两种检索有什么区别呢？
- **Go to Class...**：有且仅检索类名，所以**内部类**也是可以被非常快速检索到的
- 注意：不是文件名，而是类名。只是**单文件单类**在99.9999%情况下名称都相同而已，所以不要有误解哈
- **Find in Files**：用于检索文件的**内容**。当你需要关心文件内容的时候（如配置key的名称、字符串内容等）就使用它
  
  总结：如若你现在还使用**Find in Files**来进行打开类的话，会发现可能90%都是干扰项，觉得还能提高效率嘛？那你还会继续使用吗？
#### 打开/查找文件

| Action Name | Key |
| ---- | ---- | ---- |
| Go to File... | command + shift + o |

它用于根据**文件名**查找/打开文件。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgVPKrG95dE6zxnWiaBLZBmPUyy2ps6I1ACtqCmTNPmQYJvpD4MQwCQAg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)可以看到，它会将文件的后缀名也显示出来。理由很简单：它检索的是**文件，文件，文件**（后缀名不一样就是不同文件）。

我再“变个戏法”以加深理解：![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgWnACABbCrZ96fRAc8B1b9LcvMiaeojFPUmwicGofSFMQGq0AHx3iaMzZg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)可以看到，“同样名称”的 `.java` 和 `.class` 文件都被搜到了，这就是查找文件的“强大之处”。

> 

一般来讲，shift功能键是同类功能做加强，这里应该能体会到吧

**笔者眼中的最佳实践**：找类用 `command + o` ，而 `command + shift + o` 专用来找配置文件（当前project或者lib包内）、普通文件。
#### 打开/查找符号

| Action Name | Key |
| ---- | ---- | ---- |
| Go to Symbol... | command + option + o |

理解这个快捷键的关键，在于理解什么叫Symbol(符号)，笔者根据自己的使用经验，尝试帮你总结一下，包括：
- Class类
- 方法名
- 在Spring容器里的Bean名称
- 枚举项
- 全局（静态）属性名
- 成员（静态）属性名
- Rest URI路径
- ...![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgaibMxzzqk6TGnh876uoG4VZAVZ9cVCQoSR6ZzpPazI3gycQc1N6uVicw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgktbvVlSIl0LHqaRYaJq6wxaA5JdExBkiaLbXzHmSVIFkagjLeIFo2aQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)非常“强悍”有木有，总而言之，能够成为类的**一部分**的都可以通过它找到，这得益于Java强类型、静态语言的特性，用好了可大大提效，谁还说Java语言编程没有脚本语言快呢？
  
  Tips：这个检索的内容虽然多，但速度也还是非常快的。道理很简单：**结构化**的元素找起来就是快。
#### 打开/查找测试

| Action Name | Key |
| ---- | ---- | ---- |
| Go to Test | command + shift + t |

光标定位在**类内部**的任何位置，可快速跳转到对应的测试类or快速创建该类的测试用例。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgaUyrIxTibsluTdHer4zKrBFkiaCW8BeDyzqPcLAQlXIguQ4ekJUXuI6A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)如果你也“喜欢”写UT，保证代码质量，相信这个快捷键能节约你不少时间。
### ✌查找、替换文字/内容

类似于全文查找，功能强大。
#### 在当前文件查找

| Action Name | Key |
| ---- | ---- | ---- |
| Find... | command + f |
| Replace... | command + r（**查找并替换**） |

#+BEGIN_EXPORT hiccup
[:figure {} [:img {:crossorigin "anonymous", :_width "78%", :alt "图片", :src "https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgNd74eWg6sMsGb9rmgsOoaia3Gdwd3YfV0GVtY5LZibxibXkUO9icah40xA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1"}]]
#+END_EXPORT
#### 在所有文件查找

| Action Name | Key |
| ---- | ---- | ---- |
| Find in Files... | command + shift + f |
| Replace in Files... | command + shift + r（**查找并替换**） |

是查找当前文件的加强版（所以看到没，加了shift功能键）。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgeIlqg2mD7qy3JaD90iaE3eVYuZlFANqZAakDxKBmITfBWRPzFxre3WQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

> 

Tips：默认情况下也只会在当前项目（In Project）下查找。如上图所示，Scope也是可调整的哈

这个快捷键因为“强大”，被很多同学**误用**。正所谓通用性和精确性往往不可兼得，建议专键专用。再提醒一次：不要误用，不要误用，不要误用
### ✌查找代码

查找代码是个很宽泛的说法，比如说我们经常需要知道这个类/变量在哪些地方被用到了、类的继承结构是怎么样的、在哪儿申明的...这些都可认为是查找代码的范畴。
#### 所有使用的地方(窗口形式)

| Action Name | Key |
| ---- | ---- | ---- |
| Find Usages in File... | option + F7 |

> 

注意：这个快捷键不是command组合哟

选中类元素（类、接口、变量、属性、方法...），按此快捷键可以显示出该元素在哪些地方被使用到了。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgvhwDLicRJQUX7vNYic9ZIOz1XMhON4bTvpcDYRu4T1BCOcLWMias4iakibg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)这种窗口方式对于某元素被**很多地方**使用的时候比较有好，因为可以分工程、分jar包、分目录的进行展示，清晰明了，一般用于查找中大型框架里面的引用情况（如Spring框架、MyBatis框架等）。

但是，对于我们自己书写的一些元素，毕竟不太可能被很多地方用到，这个时候使用下面的**列表形式**可能更为合适。
#### 所有使用的地方(列表形式)

| Action Name | Key |
| ---- | ---- | ---- |
| Show Usages... | command + option  + F7 |

![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVg07ZoPBBEHlJhsV93juLv8N0fXV7ib8Pd2zxV4D7Lt0Cp7UGiapD15PRQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)这种方式显示的信息没有那么的全，所以**快捷性**更强，操作方便。

笔者的习惯是，使用它为主，使用上面的窗口形式为辅。
#### 元素声明处/使用处

| Action Name | Key |
| ---- | ---- | ---- |
| Go to Declaration or Usages... | command + b |

该快捷键有两个作用：
- 跳到元素的声明处（若光标处在元素使用的地方）
- 99.99%情况下声明是不存在歧义的，所以按下此快捷键会直接调转到“目的地”
- （列表形式）展示出使用该元素的地方，效果同 `option + command + F7` 
  
  现在知道笔者为何喜欢使用**列表形式**了吧，因为大部分情况下这一个快捷键搞定：声明、使用两大功能，岂不快哉。
  
  > 
  
  Tips：该快捷键功能同鼠标操作的 **按住command + 鼠标单击**。即使如此，还是建议，远离鼠标，远离鼠标，远离鼠标
#### 实现

| Action Name | Key |
| ---- | ---- | ---- |
| Go to implement(s)... | command + option + b |

注意：接口的实现、类的继承都属于该范畴。这里笔者以一个抽象类为例：![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVguVrJ5AWKtDGr093wlkdb1IDztib9h8LayOCoP9sBKbwFQNABDvOibZ9A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

若某接口/类的实现有多个，则会弹窗让你选择，否则（只有一个实现）就直导航过去了。当然喽，若没有任何实现，就会弹窗提示说没有任何实现。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgCPpibWOD9rXj4UC3QJZgubd8zttE5nWcSwHO9P2UhcYD7rLomeNY6hg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

> 

Tips：该快捷键功能同鼠标操作的 **按住command + option  + 鼠标单击**。即使如此，还是建议，远离鼠标，远离鼠标，远离鼠标

请注意本功能和上面的“元素声明处/使用处”的区别哈，前者要求必须要有继承/实现关系，后者只需有使用就能查找到（毕竟，继承/实现也属于一种使用嘛）。
#### 类的层次/继承树

| Action Name | Key |
| ---- | ---- | ---- |
| Type Hierarchy | control + h |

某些复杂的场景，某个类的继承关系相当的多，这个时候通过层次/树的方式来查看是最好的。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgS1LpvpbCxX9RfRjibr4jqDkIopwI01kiaKsy8SSv1jA6V54OgEhuxHjA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)该快捷键很好的对上面的 `command + option + b` （实现）形成了补充：
- 当某个类/接口的实现较少时，使用 `command + option + b` 即可快速导航
- 当某个类/接口的实现较多时，**或者想关注层次结构时**，那就使用本快捷键吧
#### 文件结构(列表方式)

| Action Name | Key |
| ---- | ---- | ---- |
| File Structure | command + F12 |

结构就相当于“解刨”，该快捷键可以快速看到某个类的所有元素，包括：**所有成员、所有方法**。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgOBrCY0CvUGIpwCr0Rn33U0TktQUFL7hNibibORGBQVXAZVuzXH5aFyng/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)说明：加入某个类的结构元素很多，那在下面的窗口方式查看更为合适。
#### 文件结构(窗口方式)

| Action Name | Key |
| ---- | ---- | ---- |
| File Structure | command + 7 |

![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgeW8BiaYhFmb7JeYNxyMksLLWKAMicyoa1S0STuibZMfEUzPDibsEwLETTw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)该窗口上面附有工具栏，可格局需要进行展示、隐藏、展开、排序等操作，非常方便。
### ✌其它导航

其它导航并非不重要，而是不方便分大类，所以列为其它吧。
#### 上一次修改

| Action Name | Key |
| ---- | ---- | ---- |
| Last Edit Location | command + shift + delete |

这个快捷键**巨好用**且非常智能。
- 好用体现在：将你从任意地方瞬间带回到现场，接着思绪敲代码
- 智能体现在：你在“同一个地方”编辑多次只会算作一次，智能决策
  
  比如你在浏览了其它代码、框架源码若干时间后，不知道自己写到哪了，使用它即可一键召回。按1次回到上次编辑处，按2次回到上上次，3次就是上上上次，依此类推...
  
  > 
  
  Tips：IDEA会记住你最近编辑的地方，所以能快速回去。但是，一旦重启IDEA就会清空“记忆”哈
  
  你可能会问有没有 `Next Edit Location` （下一次修改）的功能，答案是有的，但IDEA默认并没有帮你绑定快捷键，笔者估计是IDEA觉得（大部分场景下）这可以使用前进、后退快捷键代替，让使用者可以少记忆一个吧。
#### 下一个错误

| Action Name | Key |
| ---- | ---- | ---- |
| Next Highlighted Error | F2 |
| Previous Highlighted Error | shift + F2 |

当一个类里错误较多时，使用该快捷键可快速定位错误所在地，非常方便和快速。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgamjXR7Ja4WmTjbApmH4abxUBY5Qib5rS6BzL21nnXicb2byOb7NUBedw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)用鼠标操作看似问题不大，但谨记咱们的目标：尽量的脱离鼠标。
#### 前进、后退

| Action Name | Key |
| ---- | ---- | ---- |
| Back | command + [ **或** command + option + ← |
| Forward | command + ] **或** command + option + → |

这两个快捷键**非常非常非常**常用，不解释。
#### 行、列

| Action Name | Key |
| ---- | ---- | ---- |
| Go to Line:Column | command + l |

快速定位到当前文件的行、列位置。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgM8BybF1jSWsl2LORPT41BVGGLbnc1YK6IyHA4k6TMgtYStgMnLE7MA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)该快捷键最常见的使用场景：
- 抛出异常时，异常栈里会显示错误的行、列
- 代码静态检查时，会展示错误的具体行、列
  
  使用此快捷键可快速定位到错误处，非常方便。
#### 行头/行尾

| Action Name | Key |
| ---- | ---- | ---- |
| Move Caret to Line Start | command + ←或者option + a |
| Move Caret to Line end | command + →或者option + e |

还记得操作系统级别的行头、行尾快捷键吗？回忆一下下图：![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIKFyamticS5icSdAAdo4pCVgLob9f22YEc0ibM961jw1QNT0f3Fps5vvkShXSFficYwib3VluFbZNia1Qw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)IDEA因为处在编辑框里，因此针对性的提供了响应快捷键。

> 

Tips：总结来看，回到行头/行尾的快捷键有好几个了，具体使用哪个？根据个人习惯使用即可

另外，还有些基础键可结合（以上快捷键）一起使用：
- option+左右：一次移动一个单词
- shift+左右：选中