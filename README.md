# 以重构为名，开发现代高效C++应用

<a href=""><img src="cover.png" height="256px" align="right"></a>

* 作者：Dmitry Danilov
* 译者：陈晓伟
* 出版于: 2024年7月

> [!IMPORTANT]
> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> — 云风，程序员修炼之道第2版译者

> [!NOTE]
> 译版在Release中提供生成好的PDF文件以供下载，若需要其他格式请自行安装第三方工具(比如：Calibre)进行转换

> [!TIP]
> 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html
>
>  * 禁用拼写检查：https://blog.csdn.net/weixin_39278265/article/details/87931348
>
>  * 使用xelatex编译时需要添加`-shell-escape`和`-8bit`选项，例如：
>
>    `xelatex -synctex=1 -interaction=nonstopmode -shell-escape -8bit "book".tex`
>
>  * 为了内容中表格和目录索引能正常生成，至少需要连续编译两次
>
>  * Latex中的中文字体([思源宋体](https://github.com/notofonts/noto-cjk/releases))和英文字体([Hack](https://github.com/source-foundry/Hack-windows-installer/releases/tag/v1.6.0))，需要安装后自行配置。如何配置请参考主book/css.tex顶部关于字体的信息。
>
> vscode中配置LaTeX：https://blog.csdn.net/Ruins_LEE/article/details/123555016

## 本书概述

**关于本书**

高级语言盛行的时代，C++ 依然从嵌入式系统至分布式云原生系统中的各领域中大量存在。每当需要支持复杂数据结构的高性能工具时，C++ 总是站在最前线。C++也在过去二十年里，一直处于积极进化过程中。

本书是一本C++工程的全面指南，展示了如何使用 C++ 的现代特性与方法、标准库、Boost 库集合，以及微软的指南支持库来实现 SOLID 原则，并重构遗留代码。书中首先描述了编写干净代码的基本要素，并讨论了 C++ 中的面向对象编程。将探索软件测试的设计原则，并通过使用如 Google Test 这样的流行单元测试框架的例子进行学习。本书还将应用自动化工具进行静态和动态代码分析，比如使用 Clang 工具。

阅读完本书后，读者们将能够熟练运用行业认可的编码实践，设计出清晰、可持续，且可读性高的 C++ 代码。

**内容包括**

* 利用C++丰富的类型系统编写安全优雅的代码。
* 使用C++的独特特性创建面向对象的高级设计。
* 通过元编程减少代码重复。
* 在单元测试的帮助下安全地重构代码。
* 使用clang-format确保代码遵循一致的格式规范。
* 通过clang-tidy自动应用现代C++特性的使用，促进代码现代化。
* 使用Clang AddressSanitizer和ThreadSanitizer捕捉复杂的错误，如内存泄漏和数据竞争。

**适读人群**

本书对有经验的C++开发者最为有益，但也适合技术领导者、软件架构师和高级软件工程师阅读。对于希望通过使用现代C++特性及自动化工具来节省成本并提高软件开发流程效率的人来说，这本书是一个极佳的选择。

## 作者简介

Dmitry Danilov是一位拥有超过15年C++经验的工程师和团队经理。在他的职业生涯中，他开发了网络嗅探器和分析器、音视频流解决方案、电信领域的底层嵌入式应用，以及分布式系统。

Dmitry最初来自乌克兰敖德萨，并在那里从敖德萨国立理工大学获得了计算机工程硕士学位。他现在居住在以色列特拉维夫，继续自己的技术职业生涯。

除了专业工作外，Dmitry还通过他的博客(https://ddanilov.me) 积极分享知识，并参与各类技术社区活动，包括Core C++会议和Core C++小组在以色列举办的交流会，以此展现他对知识分享和社区互动的热情。

## 本书相关

* Github翻译地址：https://github.com/xiaoweiChen/Refactoring-with-Cpp



