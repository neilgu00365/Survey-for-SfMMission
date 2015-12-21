
##Pages for SfM and PCL infos
******************************************************************************************
#SfM info#

[Mastering_OpenCV/Book](http://image2measure.net/files/Mastering_OpenCV.pdf)   

[Multiple View Geometry.ppt](http://users.cecs.anu.edu.au/~hartley/Papers/CVPR99-tutorial/tutorial.pdf)  

[Multiple View Geometry/Book]  
ftp://vista.eng.tau.ac.il/dropbox/aviad/Hartley,%20Zisserman%20-%20Multiple%20View%20Geometry%20in%20Computer%20Vision.pdf

[Visual 3D Modeling from Images/Book](http://www.cs.unc.edu/~marc/tutorial.pdf)


[Computer Vision : Algorithm and Application/Book]  
ftp://vista.eng.tau.ac.il/dropbox/aviad/Szeliski%20-%20Computer%20Vision%20Algorithms%20and%20Applications.pdf

[Bundler: Structure from Motion (SfM) for Unordered Image Collections](http://www.cs.cornell.edu/~snavely/bundler/)

[BigSFM: Reconstructing the World from Internet Photos](http://www.cs.cornell.edu/projects/bigsfm/)

[OpenMVG](https://github.com/openMVG/openMVG/tree/master/src/openMVG_Samples)

[www.theia-sfm.org](http://www.theia-sfm.org/api.html)

[LSD-SLAM: Large-Scale Direct Monocular SLAM](https://vision.in.tum.de/research/vslam/lsdslam?redirect=1)

[Dense Visual SLAM](https://vision.in.tum.de/data/software/dvo)

[Robust Global Translations with 1DSfM //databese](http://www.cs.cornell.edu/projects/1dsfm/)

[Multi-view stereo Database](http://cvlab.epfl.ch/data/strechamvs)  

--------------------------------------

##Bundle Adjustment

[Changchang Wu](http://ccwu.me/)

[VisualSFM : A Visual Structure from Motion System](http://ccwu.me/vsfm/doc.html)

[Towards Linear-time Incremental Structure from Motion](http://ccwu.me/vsfm/vsfm.pdf)

[Structure from Motion Using Structure-less Resection](https://www.cs.unc.edu/~ezheng/resources/structure-less_sfm/67_final.pdf)

[Multicore Bundle Adjustment](http://grail.cs.washington.edu/projects/mcba/)

[A Generic Sparse Bundle Adjustment C/C++ Package Based on the Levenberg-Marquardt Algorithm](http://users.ics.forth.gr/~lourakis/sba/)

[Structure from motion](http://mi.eng.cam.ac.uk/~cipolla/publications/contributionToEditedBook/2008-SFM-chapters.pdf)

[Multibody Structure-from-Motion in Practice](https://www1.ethz.ch/igp/photogrammetry/publications/pdf_folder/ozden10pami.pdf)

[Generic and Real Time Structure from Motion using Local Bundle Adjustment](http://maxime.lhuillier.free.fr/pIvc09.pdf)

[Incremental Motion Estimation Through Local Bundle Adjustment](http://research.microsoft.com/pubs/69944/tr-2001-54.pdf)

[Dynamic Weighting of Laser Tracker Measurements for Bundle Adjustment](http://www.leica-geosystems.fr/fr/bundle_sandwith.pdf)

[Bundle Adjustment: Sparse Estimation in Multi-View Geometry](https://cseweb.ucsd.edu/classes/fa04/cse252c/manmohan1.pdf)

[Incremental Light Bundle Adjustment](http://www.cc.gatech.edu/~dellaert/ftp/Indelman12bmvc.pdf)

[3次元復元のためのバンドル調整の実装と評価](http://www.iim.cs.tut.ac.jp/~kanatani/papers/budjust.pdf)

[Bundle Adjustment — A Modern Synthesis](https://lear.inrialpes.fr/pubs/2000/TMHF00/Triggs-va99.pdf)

[Structure-and-Motion Pipeline on a Hierarchical Cluster Tree](http://www.3dflow.net/wp-content/uploads/2012/02/3dim09.pdf)

[BundlerによるStructure from MotionでKAZE局所特徴量を使ってみた](http://daily.belltail.jp/?p=1387)

============================================================================================
#PCL info#

[PCL点云可视化及滤波处理](http://blog.csdn.net/kh1445291129/article/details/39940439)
(http://cdn.verydemo.com/demo_c316_i102814.html)  

[点云库PCL学习教程.pdf](http://yun.baidu.com/share/link?uk=3037564920&shareid=63756728&third=0&adapt=pc&fr=ftw) 

[【干货】国外程序员整理的 C++ 资源大全](http://www.csdn.net/article/2014-10-24/2822269-c) 

[Building Point Cloud Library with Visual Studio 2012/2013/2015](http://unanancyowen.com/?p=712)  

[PCL库初步使用（1）：小试牛刀](http://blog.csdn.net/vbskj/article/details/7819828)  

[PCL学习笔记（1）：pcl1.6.0+vs2010环境配置以及第一个pcl程序](http://blog.csdn.net/chentravelling/article/details/43451589)  

[PCL Visualization overview](http://pointclouds.org/documentation/overview/visualization.php) 

[【点云可视化】如何实现点云的多窗口显示](http://www.pclcn.org/bbs/forum.php?mod=viewthread&tid=348) 


#[PCL Config](http://pointclouds.org/documentation/tutorials/compiling_pcl_posix.php)

■Appendix4 - PCL (Point Cloud Library)のビルド
$ sudo apt-get -y install libeigen3-dev
$ sudo apt-get -y install libflann-dev
$ sudo apt-get install libboost-all-dev
$ sudo apt-get install libqt4-dev libvtk5-qt4-dev
$ sudo apt-get install openni-dev
$ sudo apt-get install libusb-1.0-0-dev
$ mkdir pcl
$ cd pcl
$ tar zxvf pcl-pcl-1.7.2.tar.gz
$ cd pcl-pcl-1.7.2
$ mdkir build
$ cd build
$ cmake -DCMAKE_BUILD_TYPE=Release ..
$ make -j2
$ sudo make install

============================================================================================
###[Qt5 install](http://sysads.co.uk/2014/05/install-qt-5-3-ubuntu-14-04/)

============================================================================================
# Config_file  
For installing sth on PC  

======================================================================
依赖库安装(OpenCV)

■Appendix3 - opencvのビルド
● 必要ソフトウェアのインストール
> Build Tools
$ sudo apt-get -y install build-essential checkinstall cmake pkg-config yasm
> GUI
$ sudo apt-get -y install libqt4-dev libgtk2.0-dev
> Media & Video
$ sudo apt-get -y install libjpeg-dev libpng-dev libtiff5-dev libjasper-dev
$ sudo apt-get -y install libavcodec-dev libavformat-dev libswscale-dev libgstreamer0.10-dev libgstreamer-plugins-base0.10-dev libv4l-dev libxine-dev
$ sudo apt-get -y install libfaac-dev libmp3lame-dev libopencore-amrnb-dev libopencore-amrwb-dev libtheora-dev libvorbis-dev libxvidcore-dev
$ sudo apt-get -y install x264 v4l-utils
> Parallelism and linear algebra libraries
$ sudo apt-get -y install libtbb-dev libeigen3-dev
> Python
$ sudo apt-get -y install python-dev python-numpy
---------------------------------------------------------------------------------------
● Opencv 2.4.11 のソースファイルの入手
 http://opencv.org/downloads.html
   VAERSION 2.4.11,  OpenCV for Linux/Mac を選択。
   (opencv-2.4.11.zip)

● Opencv のbuild
* ~/opencv 以下に、opencvのソースを解凍したとします。
* release版をビルドし、/usr/localにインストールする場合です。
* 演算量算出のときは、ローカルなフォルダにインストールします。
  その場合は、 -DCMAKE_INSTALL_PREFIXの設定値を変更します。

$ cd ~/opencv2/opencv-2.4.11
$ mkdir release
$ cd release
$ cmake \
    -DCMAKE_BUILD_TYPE=RELEASE \
    -DCMAKE_INSTALL_PREFIX=/usr/local \
    -DBUILD_EXAMPLES=ON \
    -DINSTALL_C_EXAMPLES=ON \
    -DINSTALL_PYTHON_EXAMPLES=ON \
    -DWITH_1394=OFF \
    -DWITH_OPENGL=ON \
    -DWITH_QT=ON \
    -DWITH_TBB=ON \
    -DWITH_V4L=ON \
    -DWITH_XINE=ON \
    ..
$ make
$ sudo make install
$ sudo sh -c 'echo "/usr/local/lib" > /etc/ld.so.conf.d/opencv.conf'
$ sudo ldconfig

------------------------------------------------------------------------------------

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



