#C语言学习

C语言是一门很强大的语言，包括C++，C#，Java，JavaScript等语法，都和C语言类似，我们称之为类C语言。所以学好了C语言，再学习其他编程语言就很容易上手了。下面我们来介绍C语言

## 一、C语言的IDE
C语言在windows平台可以用微软的Visual Studio作为开发的IDE，当然还有跨平台的Qt，CodeBlocks，由于咱们是iOS开发，所以选择的IDE是Xcode。当然还有轻量级的,vscode作为IDE(需要安装插件）当然还有神器，sublime text 加上插件，还有Vim加上插件的大神。当然还有牛逼的大神会选择Emacs作为开发工具。但是由于学习成本和以后学习方便，建议使用xcode作为开发工具。


## 二、C语言程序结构
C语言最小的程序结构组成是单位是函数
当然C程序还包括以下部分

* 预处理器指令
* 函数
* 变量
* 语句和表达式
* 注释

```c
#include <stdio.h> // 预处理器指令

// 这是注释

int main(){//main 函数 程序的主入口

    printf("hello word. i am c language!");//这是一个语句
}

```
在xcode中编译会显示 

```console
hello world, i am c language!
```

c程序语句一般由五个部分组成
分号、注释、标识符、关键字、空格

## 三、C语言数据类型
###1、基本数据类型
* 整型
char、unsigned char 、signed char 、int 、unsigned int 、short、unsigned short、long 、unsigned long