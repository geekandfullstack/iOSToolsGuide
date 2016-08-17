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

* auto
 默认存储类型
* register
register 存储类用于定义存储在寄存器中而不是 RAM 中的局部变量。这意味着变量的最大尺寸等于寄存器的大小（通常是一个词），且不能对它应用一元的 '&' 运算符（因为它没有内存位置）。

* static 重点掌握

static 存储类指示编译器在程序的生命周期内保持局部变量的存在，而不需要在每次它进入和离开作用域时进行创建和销毁。因此，使用 static 修饰局部变量可以在函数调用之间保持局部变量的值。

static 修饰符也可以应用于全局变量。当 static 修饰全局变量时，会使变量的作用域限制在声明它的文件内。

在 C 编程中，当 static 用在类数据成员上时，会导致仅有一个该成员的副本被类的所有对象共享。

* extern
extern 存储类用于提供一个全局变量的引用，全局变量对所有的程序文件都是可见的。当您使用 'extern' 时，对于无法初始化的变量，会把变量名指向一个之前定义过的存储位置。

当您有多个文件且定义了一个可以在其他文件中使用的全局变量或函数时，可以在其他文件中使用 extern 来得到已定义的变量或函数的引用。可以这么理解，extern 是用来在另一个文件中声明一个全局变量或函数。

##七、C运算符
 略

##八、C判断

* if

* if...else

* switch

* 三目  ？：；


##九、循环

* while循环

* for循环（最常用）

* do...while循环

控制语句

* break
* continue
* goto(最好不要使用)

##十、C函数
一般形式
```C
return_type function_name( parameter list ) { body of the function }

```

调用函数


##十一、C作用域

* 全局变量

* 局部变量

##十二、C数组

```C


type arrayName [ arraySize ];

```

多维数组
##十三、C指针

指针是一个变量，其值为另一个变量的地址，即，内存位置的直接地址。就像其他变量或常量一样，您必须在使用指针存储其他变量地址之前，对其进行声明。

```C
type *var-name;
```

C 中的 NULL 指针


###tips:
数组和指针是C语言中比较容易混淆的概念，特别是数组指针，指针数组，二维数组等。面试会经常问到

##十四、C字符串


##十五、C结构体（也是c语言的难点）
C 数组允许定义可存储相同类型数据项的变量，结构是 C 编程中另一种用户自定义的可用的数据类型，它允许您存储不同类型的数据项。

##十六、C共用体
基本上很少使用了，在嵌入式开发中会用到

##十七、C typeof

C 语言提供了 typedef 关键字，您可以使用它来为类型取一个新的名字。下面的实例为单字节数字定义了一个术语 BYTE

```C
typedef unsigned char BYTE;
```

##十八、C 输入和输出

* 标准文件
stdin  标准输入
stdout 标准输出
stderr 标准错误

* getchar() & putchar()函数

* gets & puts

* scanf & pritf


##十九、C文件读写

* 打开文件
fopen()

* 关闭文件
fclose()

* 写入文件
fputc()

* 读取文件
fgetc


##二十、C预处理文件

| 指令 | 描述 || --- | --- || #define | 定义宏 || #include | 包含一个源代码文件 || #undef | 取消已经定义的宏 || #ifdef | 如果宏已经定义，则返回真 || #ifndef | 如果宏没有定义，则返回真 || #if | 如果给定条件为真，则编译下面代码 || #else | #if的替代方案 || #elif | 如果前面的 #if 给定条件不为真，当前条件为真，则编译下面代码 || #endif | 结束一个 #if……#else 条件编译块 || #error | 当遇到标准错误时，输出错误消息 || #pragma | 使用标准化方法，向编译器发布特殊的命令到编译器中 |



##二十一、C 头文件

头文件是扩展名为 .h 的文件，包含了 C 函数声明和宏定义，被多个源文件中引用共享。有两种类型的头文件：程序员编写的头文件和编译器自带的头文件。

#include <file>
#include "file"

##二十二、C 内存管理

* calloc

* free

* malloc

* realloc








