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

### tips:关键字
auto、else、long、switch、break、enum、register、typedef、case、extern、return、union、char、float、short、unsigned、const、for、signed、void、continue、goto、sizeof、volatile、default、if、static、while、do、int、struct、_Packed、double



## 三、C语言数据类型
###1、基本数据类型
* 整型
char、unsigned char 、signed char 、int 、unsigned int 、short、unsigned short、long 、unsigned long

* 浮点型
float、double、long double

* void 类型


## 四、C语言变量

### 1、声明
```c
type variable_list ;
```
### 2、定义如下 
```c
type variable_list = value;

```
### 3、C 中的左值（Lvalues）和右值（Rvalues）

C 中有两种类型的表达式：

左值（lvalue）：指向内存位置的表达式被称为左值（lvalue）表达式。左值可以出现在赋值号的左边或右边。

右值（rvalue）：术语右值（rvalue）指的是存储在内存中某些地址的数值。右值是不能对其进行赋值的表达式，也就是说，右值可以出现在赋值号的右边，但不能出现在赋值号的左边。

变量是左值，因此可以出现在赋值号的左边。数值型的字面值是右值，因此不能被赋值，不能出现在赋值号的左边。下面是一个有效的语句：

## 五、C语言常量
###1、定义常量

 * 使用#define 定义
 * 使用const关键字定义

## 六、C存储类


