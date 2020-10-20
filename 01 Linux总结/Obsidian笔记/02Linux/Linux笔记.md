## <font color=Crimson size=4>Linux</font>

**1. 查看linux下的opencv安装版本：**
* <kbd>`pkg-config --modversion opencv`</kbd>

**2. 查看linux下的opencv安装库：**
* `pkg-config --libs opencv`

**3. 查看linux下的opencv安装路径，并将结果存在 /home/ubuntu/Desktop/opencv_find.txt的文件中：**
* `sudo find / -iname "*opencv*" > ~/find.txt`

**4. Linux查看系统剩余空间**

1. 查看系统整体空间剩余情况

* `df -h`

* `sudo fdisk -l`
2. 查看每个文件夹的占用情况
* `du -sh *`
3. 查看当前文件夹下有多少文件
* `ls |wc -l`

**5. 更新数据库文件(根据/etc/updatedb.conf 的设定去搜寻系统硬盘内的文件名,并更新 /var/lib/mlocate 内的数据库文件)**
* `updatedb`

**6. 利用g++编译器编译程序,并添加opencv库:**
* `` g++ test.cpp -o ocvtest `pkg-config opencv --cflags --libs` ``

**7. 利用g++编译器编译程序,并添加opencv库，并添加调试:**
* `` g++ -g test.cpp -o ocvtest `pkg-config opencv --cflags --libs` ``

**8. 获取文件夹目录**
1. 获取当前文件夹目录
* `$PWD`
* `pwd`
2. 获取上一级目录
* `dirname "$PWD"`
* `` dirname `pwd` ``
3. 当前文件夹名
* `basename "$PWD"`
* `` basename `pwd` ``

**9. 终端打开文件(等同于双击)**
* `xdg-open /data/Haro/学习/01编程/01C_C++/01书籍/C++谭浩强.pdf`

**10. 从windows到linux的文本转码**
* `iconv -f gbk -t utf-8 安装密钥.txt -o 安装密钥1.txt`

**11. 查看可执行文件example需要的lib库**
* `ldd example`

**12. 查看文件类型**
![](https://raw.githubusercontent.com/harozhong/PictureBed/master/img/%E6%9F%A5%E7%9C%8B%E6%96%87%E4%BB%B6%E7%B1%BB%E5%9E%8B.png)

##### **13.Linux后台进程管理**
- [Linux后台进程管理以及ctrl+z（挂起）、ctrl+c（中断）、ctrl+\（退出）和ctrl+d（EOF）的区别](https://www.cnblogs.com/jiangzhaowei/p/8971265.html)