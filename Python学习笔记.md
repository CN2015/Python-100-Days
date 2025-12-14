## ** 第一章 Python基础**

----------

**一、认识Python**

1.编程语言是用来定义计算机程序的语言，用来向计算机发出指令。 Python语言是一种**面向对象**的解释型高级编程语言。

#区分：编译型语言 和 解释型语言

解释型语言：使用专门的解释器对源码程序逐行解释成特定平台的机器并立即执行，是代码在执行时才被解释器一行行**动态翻译**和**轨行**，而不是在执行之前就完成翻译。
<img width="874" height="287" alt="image" src="https://github.com/user-attachments/assets/a83ff80c-e2bb-4bd5-9d19-eb23233a4e42" />

编译型语言：使用专门的编译器，针对特定的平台，将高级语言源代码一次性的编译成可被该平台硬件执行的机器码，并包装成该平台所能识别的可执行程序的格式。如：C语言、C++
<img width="874" height="287" alt="image" src="https://github.com/user-attachments/assets/f28952bb-749a-4dd8-9405-94e6f41a4ff6" />

区别：
1.编译性语言编译后就可以在平台运行，解释型语言在
运行期间才编译。
2.**一般来说**，编译型语言运行速度快。
3.解释型语言*跨平台特性*比编译型语言好。

2.Python是什么
Python是一种**面向对象**的**解释型**计算机程序设计语言。
Python是**强类型**的动态**脚本语言**。

**二、编写第一个Python程序**
```
print("Hello World!")
```
运行py文件推荐使用方式：右键点击代码空白处，选择Run
**二、Python常见bug**
```
print(“123”)
```
报错，中文引号
**注意**：Python中的符号都是要用英文模式下的
```
  print(123)
```
**注意**:print要顶格写，否则就报错
```
print (123)print (456)
```
两个print不能写在同一行，一个print必须单独写一行，错误信息中遇到**Syntax**说明语法有问题

<!--stackedit_data:
eyJoaXN0b3J5IjpbNTkzODY4MjM5LC0xMjIzNjk4NDVdfQ==
-->