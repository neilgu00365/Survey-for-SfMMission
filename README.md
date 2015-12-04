# Config_file
For installing sth on PC
======================================================================
依赖库安装

#更新源
$ sudo apt-get update 
#更新已安装的包
$ sudo apt-get upgrade 
# 安装所需的依赖库
$ sudo apt-get install build-essential libgtk2.0-dev libjpeg-dev libtiff4-dev libjasper-dev libopenexr-dev cmake python-dev python-numpy python-tk libtbb-dev libeigen2-dev yasm libfaac-dev libopencore-amrnb-dev libopencore-amrwb-dev libtheora-dev libvorbis-dev libxvidcore-dev libx264-dev libqt4-dev libqt4-opengl-dev sphinx-common texlive-latex-extra libv4l-dev libdc1394-22-dev libavcodec-dev libavformat-dev libswscale-dev

安装OpenCV

OpenCV官网下载稳定的安装包，opencv-2.4.10.zip，我下载的版本。

首先需要提供gcc 4.4.x及以上到编译器支持，以及CMAKE编译工具。要确保自己的机器安装好。

#解包
$ unzip opencv-2.4.10.zip
#切换到解压目录
$ cd opencv-2.4.10/
#编译
$ cmake .
$ make
$ sudo make install

安装成功之后在你的机器目录/usr/local/include/下有两个目录（opencv和opencv2），以及在/usr/local/lib/下的一些库文件libopencv_开头的库文件。

======================================================

配置Linux.openCV参数设置
在/etc/ld.so.conf.d/opencv.conf文件中加入一行：/usr/local/lib ,

可能会没有opencv.conf这个文件，那我们就自己创建一个:

sudo gedit /etc/ld.so.conf.d/opencv.conf。

使用下面这条命令：

sudo ldconfig         

在 /etc/ bash.bashrc中加入:（sudo gedit /etc /bash.bashrc以root进入才能修改）
PKG_CONFIG_PATH=$PKG_CONFIG_PATH:/usr/local/lib/pkgconfig
export PKG_CONFIG_PATH

======================================================


#配置一下环境变量
$ sudo vim /etc/bash.bashrc
#文件的最后增加一下内容
PKG_CONFIG_PATH=$PKG_CONFIG_PATH:/usr/local/lib/pkgconfig

export PKG_CONFIG_PATH
$ source /etc/bash.bashrc


菜单栏Settings->Complier, gcc编译器选项下找到Linker Settingtab页，添加库文件，将/usr/local/lib/ 下向这样的文件'libopncv_*.so'添加到此处。
切换到Search directories在该页下找到，Compilertab页，添加这个目录/usr/local/include/opencv2

opencv+codeblocks configration
http://www.cnblogs.com/zjhnl/archive/2012/09/09/2677285.html
------------------------------------------------------------------------------------------

