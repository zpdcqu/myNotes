# ✍正文
- 视窗(view)：内容的载体
- 选择（selection）：操作的目标
##  IntelliJ IDEA快捷键
### ✌视窗

在图形化界面里，视窗的重要性不言而喻。方便快捷的调出、隐藏、操作视窗，亦能有助于效率的提升。

下面笔者根据自身经验，介绍几个常用的视窗快捷操作。
#### 最近打开的文件

| Action Name | Key |
| ---- | ---- | ---- |
| Recent Files | command + e |

文件：包括.java、.class、.properties等**一切**文件类型。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSrKYbchMpN9WBJSULS9uBTeEmHUO559XoKDQ2TicqibVMdaph638LsM07w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)如果只想看**最近编辑过的**的文件，那就**再按一次**该快捷键即可（当然喽，你用鼠标点击勾选上也是可以的）：![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSrrCP2g6pXbAYicyHmTxRqic28K1RK5UBzPR3MRXawx7SwACFqndr98WUw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)
#### 最近所处的位置

| Action Name | Key |
| ---- | ---- | ---- |
| Recent Locations | command + shift + e |

[上篇文章](https://mp.weixin.qq.com/s?__biz=MzI0MTUwOTgyOQ==&mid=2247497263&idx=1&sn=760be2aa1d9def1e83a8e216c3c5db66&scene=21#wechat_redirect) 里知道了回到“快速回到上次编辑处”的快捷键是 `command + shift + delete` 。这个快捷键就“更厉害”了，它可以显示最近所处的位置（光标路过哪些地方），可以辅助 `command + shift + delete` 一起来达到快速定位的目的：![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSrIOORYw6HNZKeH3TXpdfO3oItxWk7OXY0FJMYqBoruxGJcKxTSlfRSQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)同样的，如果只想查看最近所处的**编辑过的位置**，再按一次本快捷键即可。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSrDExpfzmVzZLnFHQKEYpmZ6qVFpjjyibqicgHw2YCHtCg0zqkrU1wn06A/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)实话说，这个快捷键笔者并不太经常用，因为个人习惯喜欢用前进后退方式，但有时候饶的弯多了还是会用一下的。它对不同人的帮助效果可能是不一样的，因人而异，自行拾取喽。
#### （偏好）设置

| Action Name | Key |
| ---- | ---- | ---- |
| Preferences | command + , |

IDEA的设置项基本都在该视窗里![图片](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)这个快捷键不用多说，使用的频率贼高。而且，在Mac操作系统里，软件的（偏好）设置快捷键的都是它，（几乎）没有例外。
#### 打开/隐藏Project视窗

| Action Name | Key |
| ---- | ---- | ---- |
| Project | command + 1 |

要说IDEA里哪个视窗最常用，除了编辑窗口外，那绝对就是Project视窗了。![图片](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)由于“屏幕”显示面积有限，我们经常需要隐藏/打开此视窗，该动作很明显属于**高频动作**，所以特别适合用有个快捷键来“代替”，提高开发效率。

至于其它视窗（如Maven视窗、Run视窗、Debug视窗），都有（或者可以有）对应的快捷键。根据自己习惯需要，各取所需。
#### 显示/隐藏所有非编辑器窗口

| Action Name | Key |
| ---- | ---- | ---- |
| Hide All Tool Windows | commond + shift + f12 |

首先得来个名词解释：什么叫**编辑窗口**？看图就明白了：![图片](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)编辑器窗口是每个IDE最重要的窗口，查看内容、编辑等都在其中，其它视窗一般都只是辅助具有“暂时性”。

那么如上图所示，当打开的视窗比较多了，已严重干扰到编辑器窗口的“显示面积”时，怎么办？
- **忍**。不乏少数，编辑器视窗一行只能显示几十个字符了、共只能显示十几行了，依旧能继续干😄
- **逐个关闭**。这才是常规思维，把不需要的关掉，释放区域给编辑器视窗
- **一键隐藏所有非编辑器窗口**。当目标非常明确时，使用此快捷键可快速达到目的
  
  实话说，该快捷键笔者用的频率还是比较高的，因为不受干扰的沉浸式编程效率貌似确实高不不少，不信你也可以试试。
#### 聚焦到/返回到编辑器

| Action Name | Key |
| ---- | ---- | ---- |
| Focus Editor | esc |

当你习惯了用键盘操作时，该快捷键可让**焦点**回到编辑器里。比如正在Project视窗里查看项目时，就可以使用此快捷键（将光标、焦点）快速回到编辑区域喽。

> 

Tips：esc是让焦点回到编辑器，语义别和 `command + shift + delete` 混淆
### ✌选择

修改名称、批量修改、列编辑、选中查找的项...，这都是开发过程中的非常常见的“需求”嘛。下面一起来看一下
#### 按行选择

| Action Name | Key |
| ---- | ---- | ---- |
| Up with Selection | shift + ↑ |
| Down with Selection | shift + ↓ |

![图片](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)以焦点/光标位置为起点，向上/下逐行选中。它的特点是：没有“感知”能力，不会有跳跃性，老老实实的按照行逐行选中。

> 

说明：左右逐字选中，使用的是shift+←/→
#### 按模块选择

| Action Name | Key |
| ---- | ---- | ---- |
| Extend Selection | option + ↑ |
| Shrink Selection | option + ↓ |

![图片](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)相较于按行选择，它显得更“智能”：**能读懂上下文**，感知到什么叫模块，然后可以一个模块的快速选中，不管多长都可一步到位，十分高效。

显然，这里需要补充一个小知识点，这里指的模块有哪些：
- 一条语句，如：instances.add(instance)
- 一个代码块：if(xxx) {xxx} 或者 try{xxx} catch(){xxx}等
- 一个方法：private void fun(){ xxx }
- ...
  
  这种感知选择的规则还蛮有意思：即保证了模块的层级性，又**尽快的**选中模块，好像能懂你一样，这也是强类型语言的魔力？
  
  > 
  
  Tips：这里上下箭头不是存粹的代表方向，而代表了增/减量。比如，当没有选择任何模块时，按 `option + ↓` 是无效的，即使下面还有代码块也不会向下选中
#### 查找上/下一个

| Action Name | Key |
| ---- | ---- | ---- |
| Find/Move to next Occurrence | command + g |
| Find/Move to previous Occurrence | command + shift + g |

![图片](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)该快捷键的底层是 `common + f` ，只不过它无调起查找窗口，使用起来更为便捷。毕竟文件内查找是非常常用的功能，所以IDEA提供了此便捷操作。而功能上，匹配的方式，完全由最**近一次**的 `common + f` 来决定。

比如上图中，笔者将 `common + f` 功能限制为大小写敏感：![图片](data:image/gif;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVQImWNgYGBgAAAABQABh6FO1AAAAABJRU5ErkJggg==)再次按 `command + g` 会发现getKey中的 `Key` 就不再会被选中了。

笔者使用该快捷键的频率很高，因为它比呼起查找窗口来得更方便快捷，而且能满足我大部分时候的查找要求，毕竟大部分情况下咱都是精确查找嘛。
#### 重复选择

重复选择下一个，重复选择所有。这个功能在批操作时超级超级超级好用~

> 

和上面的功能区别：上面永远只会选中一个，而这里会选中多个，能进行批量编辑

| Action Name | Key |
| ---- | ---- | ---- |
| Add Selection for Next Occurrence | control + g |
| Unselect Occurrence | control + shift + g |
| Select All Occurrence | control + command +  g |

说明：该匹配规则为：文本**全部匹配**，和 `common + f` 无关。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSrrnJmXiazdibFzvTSia1eZctOO59P44RRRKcnGoHJoiaomk2dc9fAwiajOhg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)三个光标，代表可以批量编辑喽。

 `control + g` 会以第一个文本为基础，继续选择下一个**同名的文本**（ `control + shift + g` 是取消选择），如上图所示，可以非常方便的批量修改，即使它们不在同一列、处在不同地方、**不都是代码**（有注释），可大大提高操作的效率。

同时，因为进入了“多光标”模式，也可以“批量移动光标”，再做你喜欢的操作。比较常见的operation有：在对应行的所有**行头/尾**加/减内容。![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSr9TZBiaUoyDRZwfrJ5496pia1UicFzleacCH4c15K4pou0CicOmjVSTavibA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)tips：请注意此功能和 `rename` 这种功能的定位区别，切忌混淆使用而导致写bug啦。

该功能有个典型的应用场景，举个例子，有如下一串内容：

> 

为了节约篇幅，这里只例举10个数字，实际可能很长

```
10|
7|
68|
13|
18|
121|
25|
100056|
32|
100|
```

要求将上面纵向排列的数字内容，改为：
- 横向排列
- 数字之间改为使用逗号分隔（本来是使用 `|` 的嘛）
  
  对于这个case，有了这个快捷键就变得相当容易了，操作步骤如下：
- 选中一个 `|` 符号
- 按 `control + command + g` 选中全部 `|` 符号，就像这样：![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSrzvDAOjP2TtJ4Zgaa5NahibEsAKic3AoL0nb6j7S4TZrLN7mxxThQYSWg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)
- 输入 `,` 替换掉 `|`
- 使用快捷键回到（所有行）行首，按delete键，**将列变为行**。大功告成：
  
  ```
  10,7,68,13,18,121,25,100056,32,100,
  ```
  
  一般来讲：对于上面这种简单文本的编辑笔者会使用sublime text，恰巧**此功能快捷键同IDEA**。看来，很多主流IDE的快捷键都是遵循“规范”的，开发者切换起来也够方便。
  
  最后想强调一点：此快捷键虽好，请务必注意使用哦。此项操作属于**纯文本**操作，需特别注意选中编辑的范围，避免误伤。
  
  **特别在使用 `control + command + g` 全选时，一定要检查清楚喽(很长的单词误伤概率较小，短单词要更加注意)**
#### 切换到列模式

列编辑模式，特殊场景特殊用处。

| Action Name | Key |
| ---- | ---- | ---- |
| Column Selection Mode | commond + shift + 8 |

![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSrIfWreibIzEicrFF6f0KvbXLlN7KZlMkj7WWo3EuLsmj0LlXAcwONTribA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)使用该快捷键进入列模式后，界面不会有任何变化。那如何知道当前处在列模式or not呢？看右下角：![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSrnpB7DB22rKucyIcUcP5ZsyLYXQ9yJCMcuFrrarcoXDlvGSEP6NO6Iw/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)若多出了它，就说明编辑窗口当前处在列模式下，拖动鼠标/方向键就是按列编辑。

> 

注意：按esc是无法退出列模式的，退出方式是：再按一次 `commond + shift + 8` 

一般来讲列模式只需要在某些瞬间开启就行，不需要长期存在。所以IDEA提供了一种快捷方式：**按住option键**，然后**竖向**拖动光标，即可达到同样的列编辑的效果，优点比较明显：随用随走。

列编辑模式笔者使用的频率还是比较高的，比如一个非常非常典型的应用场景：批量修改访问修饰符：![图片](https://mmbiz.qpic.cn/mmbiz_png/crPesQVeyKIrtzuE9hC9EP8uuaId8LSrxRTC4icZMKF0HxaGAyOpCIeTulFmy3yibXZEtY426ClNicib8icmIpSXTLQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)该怎么快速完成所有属性访问修饰符protected -> private的修改，这里就不做说明了。留作作业，自己动手尝试一下？
# ✍总结