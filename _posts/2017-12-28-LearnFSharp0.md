---
layout: post
title: 环境搭建 |> 可爱的 F# 0
---
如标题所示，今天我们来简单学习一下关于F#的特性和环境搭建。
<!--more-->
# 关于 F\#
F#就是微软主导开发的一个运行在 CLR 上的 .NET 语言，是 ML language family 的一员，因此和同为 ML language family 的 OCaml 同根同源，相当相似。因此他也继承了 ML 系的特点。

* 函数式编程的能力
* 从 OCaml 那里继承的~~没什么卵用~~的 OOP（面向对象编程）
* ~~恶心而丑陋的语法~~

同时作为微软的~~假的~~亲儿子，他可以很方便的调用 C# 和其他 .NET 的库。也可以通过 .NET Core 和 Mono 来跨平台。

F#也是一门开源的语言，您可以在他们的 [GitHub](https://github.com/fsharp) 组织中找到相关信息

F# 大体而言便是如此了。
# 环境搭建
本文所处时代的 Visual Studio 版本为 Visual Studio 2017。故也许将来可能会有变化，请大家参照[微软的官方文档](https://docs.microsoft.com/zh-cn/dotnet/fsharp/get-started/get-started-visual-studio)。这里只是大概演示一下。

1. 首先打开 **Visual Studio Installer**
2. 点击 **修改**
3. 在 **.NET 桌面开发中**的**摘要-可选**中选择 **F# 桌面语言支持**

您如果想打开F#的REPL（读取、计算、打印、循环），也便是 **F# Interactive**。很简单，打开 Visual Studio，点击**视图-其他窗口-F# Interactive** 便可，再者可以使用快捷键<kbd>Ctrl+Alt+F</kbd>打开。

同时您也可以使用.NET Core中的F#，可以参考[微软的这篇文档](https://docs.microsoft.com/zh-cn/dotnet/fsharp/get-started/get-started-command-line)

您还可以试试 [Try F#](http://www.tryfsharp.org/)。用它来进行练手相当合适。
# 如何更好的拓展学习

1. 首先建议去 [F# 软件基金会（FSharp Software Foundation）](http://fsharp.org/)中阅读文档。
2. 去 Try F# 中试着自己写写代码。
3. 刷题可以有效提高你的水平，本人推荐 [Codewars](http://codewars.com/) 和 [HackerRank](https://www.hackerrank.com/)。

# 题外话
非常感谢您阅读完了本文，这里是一些题外话，您有兴趣的话可以阅读一下。
## 我是如何开始学习的 F\#
因为我是个软粉，当时也想学习 FP。草草看了看 Haskell，便想起了微软好像也有一门 FP 的语言，便开始学习了。
## F\# 可以干什么
首先，F# 毕竟是.NET语言，还是微软主导开发，其实 C# 能干什么，F#理论上就能干什么，那些 FP 的特性说不定还能带来更多的方便。再者，我们还可以学习 F\* 进行定理证明，我说不定将来也会写关于 F\* 的教程，当然这是后话了。最后您可以看看 F# 软件基金会的 USE F#，这里有 F# 能干的更多事情，从 Web 到 Android、iOS，甚至 GPU Code 都能驾驭。
## 为什么叫可爱的 F\#
因为在这个阶段 F# 都是可爱的，以后就不知道了呢。随着教程的深入，F# 可能会不再可爱。
## 是否推荐使用 F\# 作为 FP 的入门语言
说实话，不推荐。F# 并不是纯粹的 FP 语言，他还有很多 OOP 的特性，这就导致您甚至可以不怎么使用F#的 FP 功能，就用其中的 OOP 相关部分写出很多~~垃圾~~代码。因此入门 FP 的话我还是推荐 Haskell 这门纯粹的 FP 语言。
# 结束语
是的，本文就这么结束了，希望这篇教程能给您带来帮助。

本文尽量做到了详实，若还是有些许错误，还望通过[关于](\about)中的联系方式联系一下本人，非常感谢！

下一篇我们就要正式开始进入学习，主要讲讲关于F#的数据类型，并着手写一些函数。