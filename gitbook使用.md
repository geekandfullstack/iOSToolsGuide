#gitbook使用
gitbook是用markdown的形式，通过git的方式来控制版本。以后必然为程序员，乃至普通作家的写作的工具。下面来介绍gitbook的使用。
[gitbook官网](https://www.gitbook.com/)

##markdown
写Markdown的工具有很多，本人最喜欢用的工具mWeb，无奈mWeb并不支持git，当然本人还没有完全用好mWeb上的功能，比如说发布服务和图床功能，这个等过一段时间去研究。好了，说回gitbook，天啊，我以前怎么没觉得gitbook这么好用呢？其实主要是这一种思想，我觉得gitbook这种会是以后一种发布写书的一种新的模式。好了，废话不多说，下面我就来介绍如何将gitbook发布到github上，也可以用gitbook客户端来编写文字
##一，下载gitbook editor
[点我](https://www.gitbook.com/editor)本人是MBP，所以下载的是mac版的gitbook editor

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-50baa309c9c8b5d6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##二、打开gitbookeditor，新建一个book

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-4af2f81ac4b7c736.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##三、新建一个repository

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-c19473ad662c945a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-8f8624fd9eb1f6cb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##四、拷贝git地址一会儿用

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-608b8678405b2ddb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##五，命令行执行git命令
###1、切换到刚刚新建的gitbook目录下![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-f913508580ffd3fc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###2、执行以下命令

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-416828ba4e2c3999.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###3、再github上查看gitbook项目.已经成功

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-2793caca483a05ab.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###4、编辑文章，然后进行save和sync操作文章就会在github上更新了
##tips：如何删除github仓库

###1、找到仓库，点进去，点击settings

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-141fed7355bd6c36.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###2、找到 danger zone，点击delete this repository

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/701052-5736e6da8d5d762c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
