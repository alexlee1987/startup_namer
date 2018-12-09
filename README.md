# startup_namer

&emsp;&emsp;Flutter是Google的移动UI框架，可以快速在iOS和Android上构建高质量的原生用户界面，而且2018年12月5日Flutter 1.0版本正式发布。该应用是基于Flutter 1.0即最新稳定版本开发的跨平台应用，该应用功能是为一个创业公司生成建议的名称，该应用主要目的是通过实现简单的Demo进一步学习和使用Flutter框架。

&emsp;&emsp;该项目用到和实现的Flutter技术如下：

- 从头开始创建一个Flutter应用程序;
- 编写 Dart 代码实现界面功能;
- 利用外部的第三方库：english_words.dart；
- 实现一个有状态的widget（RandomWordsState），并为应用增加交互（实现了点击添加和取消收藏）；
- 用ListView和ListTiles创建一个延迟加载的无限滚动列表；
- 创建了一个路由Navigator并添加了在主路由和新路由之间跳转逻辑；
- 实现了使用主题更改应用UI外观的功能。


&emsp;&emsp;该应用为学习Flutter过程中实现的第一个应用，在接入Flutter框架中遇到的问题及解决方法：

1.先手动安装的Flutter工具，然后再AndroidStudio上面新建项目，提示指定Flutter SDK目录或安装Flutter SDK，这个地方要记得引入手动安装的Flutter SDK的根目录，否则会有重复安装的问题；

2.编译工程时，一直停留在"initializing gradle"提示界面，重启和清AndroidStudio内存都没有用，查看项目引用的gradle版本是gradle-4.10.2-all，怀疑是本地下载gradle版本出错，在官网下载gradle-4.10.2-all.zip包放到本地greadle安装目录下，重新编译工程，通过，顺利编译成功。