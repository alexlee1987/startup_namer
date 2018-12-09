# startup_namer

Flutter应用：用Flutter最新稳定版本开发跨平台应用，该应用功能是为一个创业公司生成建议的名称。


该应用为学习Flutter过程中实现的第一个应用，在接入Flutter框架中遇到的问题及解决方法：

1.先手动安装的Flutter工具，然后再AndroidStudio上面新建项目，提示指定Flutter SDK目录或安装Flutter SDK，这个地方要记得引入手动安装的Flutter SDK的根目录，否则会有重复安装的问题；

2.编译工程时，一直停留在"initializing gradle"提示界面，重启和清AndroidStudio内存都没有用，查看项目引用的gradle版本是gradle-4.10.2-all，怀疑是本地下载gradle版本出错，在官网下载gradle-4.10.2-all.zip包放到本地greadle安装目录下，重新编译工程，通过，顺利编译成功。