# Config_file
For installing sth on PC
======================================================================
依赖库安装

更新源
sudo apt-get update 
更新已安装的包
sudo apt-get upgrade 
安装所需的依赖库
sudo apt-get install build-essential libgtk2.0-dev libjpeg-dev libtiff4-dev libjasper-dev libopenexr-dev cmake python-dev python-numpy python-tk libtbb-dev libeigen2-dev yasm libfaac-dev libopencore-amrnb-dev libopencore-amrwb-dev libtheora-dev libvorbis-dev libxvidcore-dev libx264-dev libqt4-dev libqt4-opengl-dev sphinx-common texlive-latex-extra libv4l-dev libdc1394-22-dev libavcodec-dev libavformat-dev libswscale-dev

安装OpenCV
OpenCV官网下载稳定的安装包，opencv-2.4.10.zip，我下载的版本。
首先需要提供gcc 4.4.x及以上到编译器支持，以及CMAKE编译工具。要确保自己的机器安装好。
解包
unzip opencv-2.4.10.zip
切换到解压目录
cd opencv-2.4.10/
编译
cmake .
make
sudo make install

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
配置一下环境变量
sudo vim /etc/bash.bashrc
文件的最后增加一下内容
PKG_CONFIG_PATH=$PKG_CONFIG_PATH:/usr/local/lib/pkgconfig

export PKG_CONFIG_PATH
source /etc/bash.bashrc

菜单栏Settings->Complier, gcc编译器选项下找到Linker Settingtab页，添加库文件，将/usr/local/lib/ 下向这样的文件'libopncv_*.so'添加到此处。
切换到Search directories在该页下找到，Compilertab页，添加这个目录/usr/local/include/opencv2

[opencv+codeblocks configration](http://www.cnblogs.com/zjhnl/archive/2012/09/09/2677285.html)
------------------------------------------------------------------------------------------
==========================================================================================
#SfM environment config 
[Cloud Point Library (CPL)](http://pointclouds.org/)(http://pointclouds.org/downloads/linux.html)
[WIN7(32位)VS2010+openCV 2.4.10+PCL 1.6.0+CUDA 6.5.14+ CMake 3.2.1+ SSBA-3.0 配置 ](http://blog.csdn.net/u012989207/article/details/44955937)

==========================================================================================
******************************************************************************************

##Pages for SfM and PCL infos
==========================================================================================
#PCL info#

[PCL点云可视化及滤波处理]（http://blog.csdn.net/kh1445291129/article/details/39940439）(http://cdn.verydemo.com/demo_c316_i102814.html)  
[点云库PCL学习教程.pdf](http://yun.baidu.com/share/link?uk=3037564920&shareid=63756728&third=0&adapt=pc&fr=ftw) 
[【干货】国外程序员整理的 C++ 资源大全](http://www.csdn.net/article/2014-10-24/2822269-c) 
[Building Point Cloud Library with Visual Studio 2012/2013/2015](http://unanancyowen.com/?p=712)  
[PCL库初步使用（1）：小试牛刀](http://blog.csdn.net/vbskj/article/details/7819828)  
[PCL学习笔记（1）：pcl1.6.0+vs2010环境配置以及第一个pcl程序](http://blog.csdn.net/chentravelling/article/details/43451589)  
[PCL Visualization overview](http://pointclouds.org/documentation/overview/visualization.php) 
[【点云可视化】如何实现点云的多窗口显示](http://www.pclcn.org/bbs/forum.php?mod=viewthread&tid=348) 


#[PCL Config](http://pointclouds.org/documentation/tutorials/compiling_pcl_posix.php)



============================================================================================
#SfM info#

[Mastering_OpenCV.pdf](http://image2measure.net/files/Mastering_OpenCV.pdf) 

============================================================================================
[Qt5 install](http://sysads.co.uk/2014/05/install-qt-5-3-ubuntu-14-04/)
