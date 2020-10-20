[参考博客](https://blog.csdn.net/cocoaqin/article/details/78163171)

步骤总结
1.下载并解压OpenCV的库文件（win和linux通用）
2.安装cmake和相关依赖库：
sudo apt-get install cmake 

sudo apt-get install build-essential

sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev

sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev
3.mkdir build
   cd build

4.执行命令
cmake -D CMAKE_BUILD_TYPE=Release -D CMAKE_INSTALL_PREFIX=/usr/local ..
（查/blog：cmake语法）
其中cmake可以增加一些编译选项，指定要编译的库。也可以使用cmake_gui
[参考博客]( https://www.cnblogs.com/arkenstone/p/6490017.html)

5.执行
sudo make(时间较长)
sudo make install

6.设置Linux环境变量
参考[博客](https://blog.csdn.net/cocoaqin/article/details/78163171)

遇到问题：
编译OpenCV的简单Demo的时候，出现问题：找不到ippicv库
解决方法：参照[博客](https://www.linuxidc.com/Linux/2017-10/147620.html)

方法是[下载一个ippicv库](https://blog.csdn.net/huangkangying/article/details/53406370)

将其中的libippicv.a静态库文件放到/usr/local/lib下即可。（貌似在makefile编译的时候，没有区分是静态还是动态库）

* **问题：** 运行```g++ -g example.cpp -o example `pkg-config opencv --cflags --libs` ```出现错误：`/usr/bin/ld: cannot find -lippicv`
* **解决：** 将对应版本的opencv安装包中的`libippicv.a`文件放入对应opencv安装路径的`.../lib/`中。