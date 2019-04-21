---
layout: post
title: AP 计算机科学 A 考试的笔记 1
---
第一章的笔记，关于 Java 语言的特性介绍。
<!--more-->
# 前言
本文是关于简单的 Java 语言的特点的介绍，读完本文，您会对：

* 包和类（packages and classes）

* 类型和标识符（Types and identifiers）

* 运算符（Operators）

* 输入/输出（Input/output）

* 数的存储（Storage of numbers）

* 二进制和十六进制数（Binary and hexadecimal numbers）

* 控制结构（Control structure）

* 错误和异常（Errors and exceptions）

有大概的了解。本文是我的复习笔记，很多地方我会略写，大家可以阅读完之后去查阅更多资料。
# 正文
下面开始正文.
## Introductory Java Language Feature
The AP Computer Science course includes algorithms analysis, data structure, and the techniques and methods of modern programming, specifically, object-oriented programming.
### Packages and classes
The package `java.lang` contains many commonly used classes, which is automatically provided to all java programs.

If you want to use any other package in a program, you should use `import` statement.

For example, A function in a class, which class in a package called `packagename`. If you want to use all classes in this package, you should use the form

```java
import packagename.*;
```

If you merely want to import one class named `ClassName`, use

```java
import packagename.ClassName;
```

Java has a hierarchy of packages and subpackages. Select subpackage using the multiple dots. Such as:

```java
import packagename.subpackagename.ClassName;
```

A Java program must have at least one class,  the one contains the **main method**.

The java file comprises your program are called **source files**.

A **compiler** converts source code into machine-readable form called **bytecode**

Here is a typical source file for a Java program:

```java
/** Program FirstProg.java
    Start with a comment, giving the program name and a brief description of what the program dose.
*/
import package1.*;
import package2.subpackage;

public class FirstProg // note the file name is FirstProg.java
{
    public static type1 method1(parament list)
    {
        < code of method 1 >
    }

    public static type2 method2(parament list)
    {
        < code of method 2 >
    }
}
```
#### Javadoc Comments
The Javadoc comments `@param`, `@return` and `@throws` are part of the AP subset.

`@param`: remind you what varibles will be placed in paramenter list.

`@return`: remind you what things(such as a varible, a numbers or a string) will be returned.

`@throws`: remind you if satisfy some condition, what error would throw. 

# 后记
本文先到这里结束了，很感谢各位的阅读。这次的笔记个人感觉过于冗长了，几乎抄了半篇书，在之后的笔记记录中我会尝试精简自己的笔记。因为我的英语水平不高，所以如果有单词拼写或者语法错误，欢迎大家联系我，我会及时修改。感谢大家的斧正。

本章开始进入 Java 的知识点了。因为本文较长，所以分几次更新。——————2019年4月21日