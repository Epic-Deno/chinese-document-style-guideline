# 中文技术文档写作教程
====
document-style-guide
====
[TOC]
====

# 关于

## 我为什么要做这份目录
---
在整理中文技术文档的写作规范时，发现有不少可供参考的优秀样例，整理使用 Wiki 的方式方便阅读，随着我的学习节奏也可以加入新的规范。

## 版权说明
---
除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可，[Maecenas](https://www.github.com/maecenas/) 版权所有。其中不少资料是在原基础上翻译或演绎而来的，在页面最上方标明了原作者、原文链接以及原文采用的协议。如仍有疑问，请在 Issue 中提出。

# 标题

> BY [Maecenas](https://www.github.com/Maecenas)
>
> 这是一篇在[阮一峰](https://github.com/ruanyf)的[《中文技术文档的写作规范》](http://www.ruanyifeng.com/blog/2016/10/document_style_guide.html)基础上演绎的文章，原文内容采用的协议为公共领域（public domain）。除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。

## 层级

标题分为四级。

- 一级标题：文章的标题
- 二级标题：文章主要部分的大标题
- 三级标题：二级标题下面一级的小标题
- 四级标题：三级标题下面某一方面的小标题

## 原则

- 一级标题下，不能直接出现三级标题。
- 标题要避免孤立编号（即同级标题只有一个）。
- 下级标题不重复上一级标题的内容。
- 谨慎使用四级标题，尽量避免出现，保持层级的简单和防止出现过于复杂的章节。如果三级标题下有并列性的内容，建议只使用项目列表（Item list）。

这篇文章是[**「document-style-guide」**](https://github.com/Maecenas/document-style-guide/)的一部分，点击 [**目录**](https://github.com/Maecenas/document-style-guide/wiki/) 查看所有章节。

如果你觉得文章对你有帮助，欢迎点击右上角的 **Star** :star2: 或 **Fork**​ :fork_and_knife:​。

如果你发现了错误或是想要加入协作，请参阅 [Wiki 协作说明](https://github.com/Maecenas/document-style-guide/issues/1)。

# 文本

> BY [Maecenas](https://www.github.com/Maecenas)
>
> 这是一篇在[阮一峰](https://github.com/ruanyf)的[《中文技术文档的写作规范》](http://www.ruanyifeng.com/blog/2016/10/document_style_guide.html)基础上演绎的文章，原文内容采用的协议为公共领域（public domain）。除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。

## 空格

全角中文字符与半角英文字符之间，应有一个半角空格。

```
错误：本文介绍如何快速启动Windows系统。

正确：本文介绍如何快速启动 Windows 系统。
```

全角中文字符与半角阿拉伯数字之间，有没有半角空格都可，但必须保证风格统一，不能两种风格混杂。

```
正确：2011年5月15日，我订购了5台笔记本电脑与10台平板电脑。

正确：2011 年 5 月 15 日，我订购了 5 台笔记本电脑与 10 台平板电脑。
```

半角的百分号，视同阿拉伯数字。

英文单位若不翻译，单位前的阿拉伯数字与单位间不留空格。

```
错误：一部容量为 16 GB 的智能手机

正确：一部容量为 16GB 的智能手机
```

半角英文字符和半角阿拉伯数字，与全角标点符号之间不留空格。

```
错误：他的电脑是 MacBook Air 。

正确：他的电脑是 MacBook Air。
```

注意：对链接之间是否增加空格有争议。无论是否遵循下述规则，从语法的角度来讲都是**正确**的。

> 用法：请 [提交一个 issue](#) 并分配给相关同事。
> 用法：访问我们网站的最新动态，请 [点击这里](#) 进行订阅！
> 
> 对比：请[提交一个 issue](#) 并分配给相关同事。
> 对比：访问我们网站的最新动态，请[点击这里](#)进行订阅！

## 句子

- 避免使用长句。句子内部不使用逗号时，总长度不应该超过 40 个字；使用逗号时，总长度不应该超过 100 字或者正文的 3 行。
- 尽量使用简单句和并列句，避免使用复合句。

## 写作风格

尽量不使用被动语态，改为使用主动语态。

```
错误：假如此软件尚未被安装，

正确：假如尚未安装这个软件，
```

不使用非正式的语言风格。

```
错误：Lady Gaga 的演唱会真是酷毙了，从没看过这么给力的表演！！！

正确：无法参加本次活动，我深感遗憾。
```

用对“的”、“地”、“得”。

```
她露出了开心的笑容。
（形容词＋的＋名词）

她开心地笑了。
（副词＋地＋动词）

她笑得很开心。
（动词＋得＋副词）
```

使用代词时（比如“其”、“该”、“此”、“这”等词），必须明确指代的内容，保证只有一个含义。

```
错误：从管理系统可以监视中继系统和受其直接控制的分配系统。

正确：从管理系统可以监视两个系统：中继系统和受中继系统直接控制的分配系统。
```

名词前不要使用过多的形容词。

```
错误：此设备的使用必须在接受过本公司举办的正式的设备培训的技师的指导下进行。

正确：此设备必须在技师的指导下使用，且指导技师必须接受过由本公司举办的正式设备培训。
```

不包含任何标点符号的单个句子，或者以逗号分隔的句子构件，长度尽量保持在 20 个字以内；20～29 个字的句子，可以接受；30～39 个字的句子，语义必须明确，才能接受；多于 40 个字的句子，在任何情况下都不能接受。

```
错误：本产品适用于从由一台服务器进行动作控制的单一节点结构到由多台服务器进行动作控制的并行处理程序结构等多种体系结构。

正确：本产品适用于多种体系结构。无论是由一台服务器（单一节点结构），还是由多台服务器（并行处理结构）进行动作控制，均可以使用本产品。
```

同样一个意思，尽量使用肯定句表达，不使用否定句表达。

```
错误：请确认没有接通装置的电源。

正确：请确认装置的电源已关闭。
```

避免使用双重否定句。

```
错误：没有删除权限的用户，不能删除此文件。

正确：用户必须拥有删除权限，才能删除此文件。
```

## 英文处理

英文原文如果使用了复数形式，翻译成中文时，应该将其还原为单数形式。

```
英文：⋯information stored in random access memory (RAMs)⋯

中文：……存储在随机存取存储器（RAM）里的信息……
```

外文缩写可以使用半角圆点(`.`)表示缩写。

```
U.S.A.
Apple, Inc.
```

使用规范的缩写

```
正确：我们需要一位熟悉 JavaScript、HTML5，至少理解一种框架（如 Backbone.js、AngularJS、React 等）的前端开发者。

错误：我们需要一位熟悉 Js、h5，至少理解一种框架（如 backbone、angular、RJS 等）的 FED。
```

表示中文时，英文省略号（`⋯`）应改为中文省略号（`……`）。

```
英文：5 minutes later⋯

中文：5 分钟过去了⋯⋯
```

英文书名或电影名改用中文表达时，双引号应改为书名号。

```
英文：He published an article entitled "The Future of the Aviation".

中文：他发表了一篇名为《航空业的未来》的文章。
```

第一次出现英文词汇时，在括号中给出中文标注。此后再次出现时，直接使用英文缩写即可。

```
IOC（International Olympic Committee，国际奥林匹克委员会）。这样定义后，便可以直接使用“IOC”了。
```

专有名词使用正确的大小写，非专有名词则不需要大写。

注意：当网页中需要配合整体视觉风格而出现全部大写／小写的情形，HTML 中请使用标准的大小写规范进行书写；并通过 `text-transform: uppercase;`／`text-transform: lowercase;` 对表现形式进行定义。

```
“American Association of Physicists in Medicine”（美国医学物理学家协会）是专有名词，需要大写。

“online transaction processing”（在线事务处理）不是专有名词，不应大写。

正确：我们的客户有 GitHub、Foursquare、Microsoft Corporation、Google、Facebook, Inc.。

错误：我们的客户有 Github、FourSquare、MicroSoft Corporation、Google、FaceBook, Inc.。
```

这篇文章是[**「document-style-guide」**](https://github.com/Maecenas/document-style-guide/)的一部分，点击 [**目录**](https://github.com/Maecenas/document-style-guide/wiki/) 查看所有章节。

如果你觉得文章对你有帮助，欢迎点击右上角的 **Star** :star2: 或 **Fork**​ :fork_and_knife:​。

如果你发现了错误或是想要加入协作，请参阅 [Wiki 协作说明](https://github.com/Maecenas/document-style-guide/issues/1)。

# 段落

> BY [Maecenas](https://www.github.com/Maecenas)
>
> 这是一篇在[阮一峰](https://github.com/ruanyf)的[《中文技术文档的写作规范》](http://www.ruanyifeng.com/blog/2016/10/document_style_guide.html)基础上演绎的文章，原文内容采用的协议为公共领域（public domain）。除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。

## 原则

- 一个段落只能有一个主题，或一个中心句子。
- 段落的中心句子放在段首，对全段内容进行概述。后面陈述的句子为核心句服务。
- 一个段落的长度不能超过七行，最佳段落长度小于等于四行。
- 段落的句子语气要使用陈述和肯定语气，避免使用感叹语气。
- 段落之间使用一个空行隔开。
- 段落开头不要留出空白字符。

## 引用

引用第三方内容时，应注明出处。

```
One man’s constant is another man’s variable. — Alan Perlis
```

如果是全篇转载，请在全文开头显著位置注明作者和出处，并链接至原文。

```
本文转载自 WikiQuote
```

使用外部图片时，必须在图片下方或文末标明来源。

```
本文部分图片来自 Wikipedia
```

这篇文章是[**「document-style-guide」**](https://github.com/Maecenas/document-style-guide/)的一部分，点击 [**目录**](https://github.com/Maecenas/document-style-guide/wiki/) 查看所有章节。

如果你觉得文章对你有帮助，欢迎点击右上角的 **Star** :star2: 或 **Fork**​ :fork_and_knife:​。

如果你发现了错误或是想要加入协作，请参阅 [Wiki 协作说明](https://github.com/Maecenas/document-style-guide/issues/1)。

# 数值

> BY [Maecenas](https://www.github.com/Maecenas)
>
> 这是一篇在[阮一峰](https://github.com/ruanyf)的[《中文技术文档的写作规范》](http://www.ruanyifeng.com/blog/2016/10/document_style_guide.html)基础上演绎的文章，原文内容采用的协议为公共领域（public domain）。除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。

## 半角数字

数字一律使用半角形式，不得使用全角形式。

注意：在设计稿、宣传海报中如出现极少量数字的情形时，为方便文字对齐，可以使用全角数字。

```
错误： 这件商品的价格是１０００元。

正确： 这件商品的价格是 1000 元。
```

## 千分号

数值为千位以上，应添加千分号（半角逗号）。

```
XXX 公司的实收资本为 RMB1,258,000。
```

对于 4 ～ 6 位的数值，千分号是选用的，比如`1000`和`1,000`都可以接受。对于7位及以上的数值，千分号是必须的。

多位小数要从小数点后从左向右添加千分号，比如`4.234,345`。

## 货币

货币应为阿拉伯数字，并在数字前写出货币符号，或在数字后写出货币中文名称。

```
$1,000
1,000 美元
```

## 数值范围

表示数值范围时，用`～`连接。参见《标点符号》一节的“连接号”部分。

带有单位或百分号时，两个数字都要加上单位或百分号，不能只加后面一个。

```
错误：132～234kg
正确：132kg～234kg

错误：67～89%
正确：67%～89%
```

## 变化程度的表示法

数字的增加要使用“增加了”、“增加到”。“了”表示增量，“到”表示定量。

```
增加到过去的两倍
（过去为一，现在为二）

增加了两倍
（过去为一，现在为三）
```

数字的减少要使用“降低了”、“降低到”。“了”表示增量，“到”表示定量。

```
降低到百分之八十
（定额是一百，现在是八十）

降低了百分之八十
（原来是一百，现在是二十）
```

不能用“降低N倍”或“减少N倍”的表示法，要用“降低百分之几”或“减少百分之几”。因为减少（或降低）一倍表示数值原来为一百，现在等于零。

这篇文章是[**「document-style-guide」**](https://github.com/Maecenas/document-style-guide/)的一部分，点击 [**目录**](https://github.com/Maecenas/document-style-guide/wiki/) 查看所有章节。

如果你觉得文章对你有帮助，欢迎点击右上角的 **Star** :star2: 或 **Fork**​ :fork_and_knife:​。

如果你发现了错误或是想要加入协作，请参阅 [Wiki 协作说明](https://github.com/Maecenas/document-style-guide/issues/1)。

# 标点符号

> BY [Maecenas](https://www.github.com/Maecenas)
>
> 这是一篇在[阮一峰](https://github.com/ruanyf)的[《中文技术文档的写作规范》](http://www.ruanyifeng.com/blog/2016/10/document_style_guide.html)基础上演绎的文章，原文内容采用的协议为公共领域（public domain）。除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。

## 原则

- 中文语句的标点符号，均应该采取全角符号，这样可以保证视觉的一致。
- 如果整句为英文，则该句使用英文/半角标点。
- 句号、问号、叹号、逗号、顿号、分号和冒号不得出现在一行之首。

> 不明白什么是全角（全形）与半角（半形）符号？请查看维基百科词条『[全角和半角](http://zh.wikipedia.org/wiki/%E5%85%A8%E5%BD%A2%E5%92%8C%E5%8D%8A%E5%BD%A2)』。

## 句号

中文语句中的结尾处应该用全角句号（`。`）。

句子末尾用括号加注时，句号应在括号之外。

```
错误：关于文件的输出，请参照第 1.3 节（见第 26 页。）

正确：关于文件的输出，请参照第 1.3 节（见第 26 页）。
```

## 逗号

逗号`，`表示句子内部的一般性停顿。

注意避免“一逗到底”，即整个段落除了结尾，全部停顿都使用逗号。

## 顿号

句子内部的并列词，应该用全角顿号(`、`) 分隔，而不用逗号，即使并列词是英语也是如此。

```
错误：我最欣赏的科技公司有 Google, Facebook, 腾讯, 阿里和百度等。

正确：我最欣赏的科技公司有 Google、Facebook、腾讯、阿里和百度等。
```

英文句子中，并列词语之间使用半角逗号（`,`）分隔。

```
例句：Microsoft Office includes Word, Excel, PowerPoint, Outlook and other components.
```

## 分号

分号`；`表示复句内部并列分句之间的停顿。

## 引号

引用时，应该使用单引号（`「 」`）。

```
例句：许多人都认为客户服务的核心是「友好」和「专业」。
```

引号里面还要用引号时，外面一层用单引号，里面一层再用双引号（`『 』`），如有需求再迭代使用。

```
例句：鲍勃解释道：「我要放音乐，可萨利说，『不行！』。」
```

注意：对简体中文是否应当使用直角引号有争议。无论是否遵循下述规则，从语法的角度来讲都是**正确**的。

> 用法：「老师，『有条不紊』的『紊』是什么意思？」
> 
> 对比：“老师，‘有条不紊’的‘紊’是什么意思？”

## 圆括号

补充说明时，使用全角圆括号`（）`，括号前后不加空格。

```
例句：请确认所有的连接（电缆和接插件）均安装牢固。
```

## 冒号

全角冒号（`：`）常用在需要解释的词语后边，引出解释和说明。

```
例句：请确认以下几项内容：时间、地点、活动名称，以及来宾数量。
```

表示时间时，应使用半角冒号（`:`）。

```
例句：早上 8:00
```

## 省略号

省略号`……`表示语句未完、或者语气的不连续。它占两个汉字空间、包含六个省略点，不要使用`。。。`或`...`等非标准形式。

省略号不应与“等”这个词一起使用。

```
错误：我们为会餐准备了香蕉、苹果、梨…等各色水果。

正确：我们为会餐准备了各色水果，有香蕉、苹果、梨……

正确：我们为会餐准备了香蕉、苹果、梨等各色水果。
```

## 感叹号

应该使用平静的语气叙述，尽量避免使用感叹号`！`。

不得多个感叹号连用，比如`！！`和`!!!`。

## 破折号

破折号`————`一般用于进一步解释。

破折号应占两个汉字的位置。如果破折号本身只占一个汉字的位置，那么前后应该留出一个半角空格。

```
例句：直觉————尽管它并不总是可靠的————告诉我，这事可能出了些问题。

例句：直觉 —— 尽管它并不总是可靠的 —— 告诉我，这事可能出了些问题。
```

## 连接号

连接号用于连接两个类似的词。

以下场合应该使用直线连接号（`-`），占一个半角字符的位置。

- 两个名词的复合
- 图表编号

```
例句：氧化-还原反应

例句：图 1-1
```

以下场合应该使用波浪连接号（`～`），占一个全角字符的位置。

- 数值范围（例如日期、时间或数字）

```
例句：2009 年～2011 年
```

注意，波浪连接号前后两个值都应该加上单位。

波浪连接号也可以用汉字“至”代替。

```
例句：周围温度：-20°C 至 -10°C
```

对完整的英文整句和特殊名词，內容使用半角标点

```
正确：乔布斯那句话是怎么说的？「Stay hungry, stay foolish.」
正确：推荐你阅读《Hackers & Painters: Big Ideas from the Computer Age》，非常的有趣。

错误：乔布斯那句话是怎么说的？「Stay hungry，stay foolish。」
错误：推荐你阅读《Hackers＆Painters：Big Ideas from the Computer Age》，非常的有趣。
```

这篇文章是[**「document-style-guide」**](https://github.com/Maecenas/document-style-guide/)的一部分，点击 [**目录**](https://github.com/Maecenas/document-style-guide/wiki/) 查看所有章节。

如果你觉得文章对你有帮助，欢迎点击右上角的 **Star** :star2: 或 **Fork**​ :fork_and_knife:​。

如果你发现了错误或是想要加入协作，请参阅 [Wiki 协作说明](https://github.com/Maecenas/document-style-guide/issues/1)。

# 文档体系

> BY [Maecenas](https://www.github.com/Maecenas)
>
> 这是一篇在[阮一峰](https://github.com/ruanyf)的[《中文技术文档的写作规范》](http://www.ruanyifeng.com/blog/2016/10/document_style_guide.html)基础上演绎的文章，原文内容采用的协议为公共领域（public domain）。除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。

## 结构

软件手册是一部完整的书，建议采用下面的结构。

- **简介**（Introduction）： [必备] [文件] 提供对产品和文档本身的总体的、扼要的说明
- **快速上手**（Getting Started）：[可选] [文件] 如何最快速地使用产品
- **入门篇**（Basics）： [必备] [目录] 又称”使用篇“，提供初级的使用教程
  - **环境准备**（Prerequisite）：[必备] [文件] 软件使用需要满足的前置条件
  - **安装**（Installation）：[可选] [文件] 软件的安装方法
  - **设置**（Configuration）：[必备] [文件] 软件的设置
- **进阶篇**（Advanced)：[可选] [目录] 又称”开发篇“，提供中高级的开发教程
- **API**（Reference）：[可选] [目录|文件] 软件 API 的逐一介绍
- **FAQ**：[可选] [文件] 常见问题解答
- **附录**（Appendix）：[可选] [目录] 不属于教程本身、但对阅读教程有帮助的内容
  - **Glossary**：[可选] [文件] 名词解释
  - **Recipes**：[可选] [文件] 最佳实践
  - **Troubleshooting**：[可选] [文件] 故障处理
  - **ChangeLog**：[可选] [文件] 版本说明
  - **Feedback**：[可选] [文件] 反馈方式

下面是两个真实范例，可参考。

- [Redux 手册](http://redux.js.org/index.html)
- [Atom 手册](http://flight-manual.atom.io/)

## 文件名

文档的文件名不得含有空格。

文件名必须使用半角字符，不得使用全角字符。这也意味着，中文不能用于文件名。

```
错误： 名词解释.md

正确： glossary.md
```

文件名建议只使用小写字母，不使用大写字母。

```
错误：TroubleShooting.md

正确：troubleshooting.md 
```

为了醒目，某些说明文件的文件名，可以使用大写字母，比如`README`、`LICENSE`。

文件名包含多个单词时，单词之间建议使用半角的连词线（`-`）分隔。

```
不佳：advanced_usage.md

正确：advanced-usage.md
```

这篇文章是[**「document-style-guide」**](https://github.com/Maecenas/document-style-guide/)的一部分，点击 [**目录**](https://github.com/Maecenas/document-style-guide/wiki/) 查看所有章节。

如果你觉得文章对你有帮助，欢迎点击右上角的 **Star** :star2: 或 **Fork**​ :fork_and_knife:​。

如果你发现了错误或是想要加入协作，请参阅 [Wiki 协作说明](https://github.com/Maecenas/document-style-guide/issues/1)。

# 谁在这样做？

> BY [Maecenas](https://www.github.com/Maecenas)
>
> 这是一篇在 [sparanoid](https://www.github.com/sparanoid) 的[中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)基础上演绎的文章，原文内容采用的协议为 WTFPL。除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。

网站 | 文案 | UGC
:-- | :-- | :--
[Apple 中国](http://www.apple.com/cn/) | Yes | N/A
[Apple 香港](http://www.apple.com/hk/) | Yes | N/A
[Apple 台湾](http://www.apple.com/tw/) | Yes | N/A
[Microsoft 中国](http://www.microsoft.com/zh-cn/) | Yes | N/A
[Microsoft 香港](http://www.microsoft.com/zh-hk/) | Yes | N/A
[Microsoft 台湾](http://www.microsoft.com/zh-tw/) | Yes | N/A
[LeanCloud](https://leancloud.cn/) | Yes | N/A
[知乎](https://www.zhihu.com/) | Yes | 部分用户达成
[V2EX](https://www.v2ex.com/) | Yes | Yes
[SegmentFault](https://segmentfault.com/) | Yes | 部分用户达成
[Apple4us](http://apple4us.com/) | Yes | N/A
[豌豆荚](https://www.wandoujia.com/) | Yes | N/A
[Ruby China](https://ruby-china.org/) | Yes | 标题达成
[PHPHub](https://phphub.org/) | Yes | 标题达成
[少数派](http://sspai.com/) | Yes | N/A

这篇文章是[**「document-style-guide」**](https://github.com/Maecenas/document-style-guide/)的一部分，点击 [**目录**](https://github.com/Maecenas/document-style-guide/wiki/) 查看所有章节。

如果你觉得文章对你有帮助，欢迎点击右上角的 **Star** :star2: 或 **Fork**​ :fork_and_knife:​。

如果你发现了错误或是想要加入协作，请参阅 [Wiki 协作说明](https://github.com/Maecenas/document-style-guide/issues/1)。

# 工具

> BY [Maecenas](https://www.github.com/Maecenas)
>
> 这是一篇在 [sparanoid](https://www.github.com/sparanoid) 的[中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)基础上演绎的文章，原文内容采用的协议为 WTFPL。除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。

| 仓库                                                                                                                            | 语言            |
|---------------------------------------------------------------------------------------------------------------------------------|-----------------|
| [vinta/paranoid-auto-spacing](https://github.com/vinta/paranoid-auto-spacing)                                                   | JavaScript      |
| [huei90/pangu.node](https://github.com/huei90/pangu.node)                                                                       | Node.js         |
| [huacnlee/auto-correct](https://github.com/huacnlee/auto-correct)                                                               | Ruby            |
| [sparanoid/space-lover](https://github.com/sparanoid/space-lover)                                                               | PHP (WordPress) |
| [nauxliu/auto-correct](https://github.com/NauxLiu/auto-correct)                                                                 | PHP             |
| [ricoa/copywriting-correct](https://github.com/ricoa/copywriting-correct)                                                       | PHP             |
| [hotoo/pangu.vim](https://github.com/hotoo/pangu.vim)                                                                           | Vim             |
| [sparanoid/grunt-auto-spacing](https://github.com/sparanoid/grunt-auto-spacing)                                                 | Node.js (Grunt) |
| [hjiang/scripts/add-space-between-latin-and-cjk](https://github.com/hjiang/scripts/blob/master/add-space-between-latin-and-cjk) | Python          |

这篇文章是[**「document-style-guide」**](https://github.com/Maecenas/document-style-guide/)的一部分，点击 [**目录**](https://github.com/Maecenas/document-style-guide/wiki/) 查看所有章节。

如果你觉得文章对你有帮助，欢迎点击右上角的 **Star** :star2: 或 **Fork**​ :fork_and_knife:​。

如果你发现了错误或是想要加入协作，请参阅 [Wiki 协作说明](https://github.com/Maecenas/document-style-guide/issues/1)。

# 参考链接


> BY [Maecenas](https://www.github.com/Maecenas)
>
> 除另行注明，这个项目中的所有内容采用[知识共享署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可。


- [**中文技术文档的写作规范**](http://www.ruanyifeng.com/blog/2016/10/document_style_guide.html), by 阮一峰
- [产品手册中文写作规范](http://wenku.baidu.com/view/23cc1a6527d3240c8447efbf.html), by 华为
- [写作规范和格式规范](http://docs.daocloud.io/write-docs/format), by DaoCloud
- [技术写作技巧在日汉翻译中的应用](http://www.hitachi-tc.co.jp/company/thesis/thesis.pdf), by 刘方
- [简体中文规范指南](https://www.lengoo.de/documents/styleguides/lengoo_styleguide_ZH.pdf), by lengoo
- [文档风格指南](https://open.leancloud.cn/copywriting-style-guide.html), by LeanCloud
- [豌豆荚文案风格指南](https://docs.google.com/document/d/1R8lMCPf6zCD5KEA8ekZ5knK77iw9J-vJ6vEopPemqZM/edit), by 豌豆荚
- [中文排版需求](http://w3c.github.io/clreq/), by W3C
- [为什么文件名要小写？](http://www.ruanyifeng.com/blog/2017/02/filename-should-be-lowercase.html), by 阮一峰
- [Google Developer Documentation Style Guide](https://developers.google.com/style/), by Google

- [**中文文案排版指北**](https://github.com/sparanoid/chinese-copywriting-guidelines), by sparanoid
- [Guidelines for Using Capital Letters](http://grammar.about.com/od/punctuationandmechanics/a/Guidelines-For-Using-Capital-Letters.htm) - ThoughtCo.
- [Letter case](http://en.wikipedia.org/wiki/Letter_case) - Wikipedia
- [Punctuation ](http://www.oxforddictionaries.com/words/punctuation)- Oxford Dictionaries
- [Punctuation](https://owl.english.purdue.edu/owl/section/1/6/) - The Purdue OWL
- [How to Use English Punctuation Corrently](http://www.wikihow.com/Use-English-Punctuation-Correctly) - wikiHow
- [格式](https://zh.opensuse.org/index.php?title=Help:%E6%A0%BC%E5%BC%8F) - openSUSE
- [全角和半角](http://zh.wikipedia.org/wiki/%E5%85%A8%E5%BD%A2%E5%92%8C%E5%8D%8A%E5%BD%A2) - 维基百科
- [引号](http://zh.wikipedia.org/wiki/%E5%BC%95%E8%99%9F) - 维基百科
- [疑问惊叹号](http://zh.wikipedia.org/wiki/%E7%96%91%E5%95%8F%E9%A9%9A%E5%98%86%E8%99%9F) - 维基百科

这篇文章是[**「document-style-guide」**](https://github.com/Maecenas/document-style-guide/)的一部分，点击 [**目录**](https://github.com/Maecenas/document-style-guide/wiki/) 查看所有章节。

如果你觉得文章对你有帮助，欢迎点击右上角的 **Star** :star2: 或 **Fork**​ :fork_and_knife:​。

如果你发现了错误或是想要加入协作，请参阅 [Wiki 协作说明](https://github.com/Maecenas/document-style-guide/issues/1)。


