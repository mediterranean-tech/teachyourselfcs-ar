# 自学计算机科学

> 本文档是对[TeachYourselfCS](https://teachyourselfcs.com)内容的中文翻译，原作者为[Ozan Onay](https://twitter.com/oznova_)和[Myles Byrne](https://twitter.com/quackingduck)。如需了解翻译相关信息或帮助改进翻译，请参见[本文档结尾](#这份指引是谁翻译的)。
>
> This document is a Chinese translation of [TeachYourselfCS](https://teachyourselfcs.com), which is written by [Ozan Onay](https://twitter.com/oznova_) and [Myles Byrne](https://twitter.com/quackingduck). For more information about this translation, please refer to [the end of this document](#这份指引是谁翻译的).

如果你是一个自学成才的工程师，或者从编程培训班毕业，那么你很有必要学习计算机科学。幸运的是，不必为此花上数年光阴和不菲费用去攻读一个学位：仅仅依靠自己，你就可以获得世界一流水平的教育💸。

互联网上，到处都有许多的学习资源，然而精华与糟粕并存。你所需要的，不是一个诸如“200+免费在线课程”的清单，而是以下问题的答案：

*   你应当学习**哪些科目**，为什么？
*   对于这些科目，**最好的书籍或者视频课程**是什么？

在这份指引中，我们尝试对这些问题做出确定的回答。

## 简而言之

大致按照列出的顺序，借助我们所建议的教材或者视频课程（但是最好二者兼用），学习如下的九门科目。目标是先花100到200个小时学习完每一个科目，然后在你职业生涯中，不时温习其中的精髓🚀。

| 科目                                      | 为何要学？                                                                             | 最佳书籍                                                                                                                                      | 最佳视频                          |
|-------------------------------------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------|
| **[编程](#编程)**                         | 不要做一个“永远没彻底搞懂”诸如递归等概念的程序员。                                     | _[《计算机程序的构造和解释》](https://book.douban.com/subject/1148282/)_                                                                      | Brian Harvey’s Berkeley CS 61A    |
| **[计算机架构](#计算机架构)**             | 如果你对于计算机如何工作没有具体的概念，那么你所做出的所有高级抽象都是空中楼阁。       | _[《计算机组成与设计》](https://book.douban.com/subject/26604008/)_                                                                           | Berkeley CS 61C                   |
| **[算法与数据结构](#算法和数据结构)**     | 如果你不懂得如何使用栈、队列、树、图等常见数据结构，遇到有难度的问题时，你将束手无策。 | _[《算法设计手册》](https://book.douban.com/subject/4048566/)_                                                                                | Steven Skiena’s lectures          |
| **[数学知识](#数学知识)**                 | 计算机科学基本上是应用数学的一个“失控的”分支，因此学习数学将会给你带来竞争优势。       | _[《计算机科学中的数学》](https://book.douban.com/subject/33396340/)_                                                                         | Tom Leighton’s MIT 6.042J         |
| **[操作系统](#操作系统)**                 | 你所写的代码，基本上都由操作系统来运行，因此你应当了解其运作的原理。                   | _[《操作系统导论》](https://book.douban.com/subject/33463930/)_                                                                               | Berkeley CS 162                   |
| **[计算机网络](#计算机网络)**             | 互联网已然势不可挡：理解工作原理才能解锁全部潜力。                                     | _[《计算机网络：自顶向下方法》](https://book.douban.com/subject/30280001/)_                                                                   | Stanford CS 144                   |
| **[数据库](#数据库)**                     | 对于多数重要程序，数据是其核心，然而很少人理解数据库系统的工作原理。                   | _[《Readings in Database Systems》](https://book.douban.com/subject/2256069/) （暂无中译本）_                                                 | Joe Hellerstein’s Berkeley CS 186 |
| **[编程语言与编译器](#编程语言与编译器)** | 若你懂得编程语言和编译器如何工作，你就能写出更好的代码，更轻松地学习新的编程语言。     | _[《编译原理》](https://book.douban.com/subject/3296317/)_                                                                                    | Alex Aiken’s course on Lagunita   |
| **[分布式系统](#分布式系统)**             | 如今，_多数_ 系统都是分布式的。                                                        | _《分布式系统原理与范型》（[中文第二版](https://book.douban.com/subject/3108801/)，[英文第三版](https://book.douban.com/subject/26979326/)）_ | MIT 6.824                          |

## 为什么要学习计算机科学？

