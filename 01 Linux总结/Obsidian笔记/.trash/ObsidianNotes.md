
# <font color=Crimson size=4>目录</font>

<!-- TOC -->

- [<font color=Crimson size=4>目录</font>](#font-colorcrimson-size4目录font)
    - [<font color=Crimson size=4>Linux</font>](#font-colorcrimson-size4linuxfont)
    - [<font color=Crimson size=4>MarkDown</font>](#font-colorcrimson-size4markdownfont)
    - [<font color=Crimson size=4>C++</font>](#font-colorcrimson-size4cfont)
        - [<font color=LightCoral size=4>1. int main(int argc,char* argv[])详解</font>](#font-colorlightcoral-size41-int-mainint-argcchar-argv详解font)
        - [<font color=LightCoral size=4>2. Linux下C++ 创建文件夹</font>](#font-colorlightcoral-size42-linux下c-创建文件夹font)
        - [<font color=LightCoral size=4>3. C/C++ 中 static 的用法全局变量与局部变量</font>](#font-colorlightcoral-size43-cc-中-static-的用法全局变量与局部变量font)
        - [<font color=LightCoral size=4>4. 指针malloc分配空间与数组区别</font>](#font-colorlightcoral-size44-指针malloc分配空间与数组区别font)
        - [<font color=LightCoral size=4>5. 空指针和void *类型指针</font>](#font-colorlightcoral-size45-空指针和void-类型指针font)
        - [<font color=LightCoral size=4>6. C++ void*指针、多重指针void**和指针大小</font>](#font-colorlightcoral-size46-c-void指针多重指针void和指针大小font)
    - [<font color=Crimson size=4>线程相关</font>](#font-colorcrimson-size4线程相关font)
        - [<font color=LightCoral size=4>1. 线程信号量</font>](#font-colorlightcoral-size41-线程信号量font)
        - [<font color=LightCoral size=4>2. 线程创建C语言示例</font>](#font-colorlightcoral-size42-线程创建c语言示例font)
    - [<font color=Crimson size=4>总线通信相关</font>](#font-colorcrimson-size4总线通信相关font)
        - [<font color=LightCoral size=4>1. DBus通信</font>](#font-colorlightcoral-size41-dbus通信font)
    - [<font color=Crimson size=4>摄像机</font>](#font-colorcrimson-size4摄像机font)
        - [<font color=LightCoral size=4>1. 摄像机标定</font>](#font-colorlightcoral-size41-摄像机标定font)
        - [<font color=LightCoral size=4>2. 相机成像原理/四种坐标系</font>](#font-colorlightcoral-size42-相机成像原理四种坐标系font)
        - [<font color=LightCoral size=4>3. 内\外参矩阵和畸变矩阵</font>](#font-colorlightcoral-size43-内\外参矩阵和畸变矩阵font)
        - [<font color=LightCoral size=4>4. OPenCV相机标定函数ProjectPoints2</font>](#font-colorlightcoral-size44-opencv相机标定函数projectpoints2font)
        - [<font color=LightCoral size=4>5. 相机标定之棋盘标定/各类函数</font>](#font-colorlightcoral-size45-相机标定之棋盘标定各类函数font)
    - [<font color=Crimson size=4>图像处理</font>](#font-colorcrimson-size4图像处理font)
        - [<font color=LightCoral size=4>1. 车牌识别:</font>](#font-colorlightcoral-size41-车牌识别font)
        - [<font color=LightCoral size=4>2. 二值化:</font>](#font-colorlightcoral-size42-二值化font)
    - [<font color=Crimson size=4>OpenCV</font>](#font-colorcrimson-size4opencvfont)
        - [<font color=LightCoral size=4>1. 光流法calcOpticalFlowPyrLK()使用语法:</font>](#font-colorlightcoral-size41-光流法calcopticalflowpyrlk使用语法font)
        - [<font color=LightCoral size=4>2. 光流法calcOpticalFlowFarneback()</font>](#font-colorlightcoral-size42-光流法calcopticalflowfarnebackfont)
        - [<font color=LightCoral size=4>3. 角点检测函数goodFeaturesToTrack</font>](#font-colorlightcoral-size43-角点检测函数goodfeaturestotrackfont)
        - [<font color=LightCoral size=4>4. 移动目标检测</font>](#font-colorlightcoral-size44-移动目标检测font)
        - [<font color=LightCoral size=4>5. cvSetImageROI</font>](#font-colorlightcoral-size45-cvsetimageroifont)
        - [<font color=LightCoral size=4>6. cvAddWeighted</font>](#font-colorlightcoral-size46-cvaddweightedfont)
        - [<font color=LightCoral size=4>7. cvCreateImage</font>](#font-colorlightcoral-size47-cvcreateimagefont)
        - [<font color=LightCoral size=4>8. cvResize</font>](#font-colorlightcoral-size48-cvresizefont)
        - [<font color=LightCoral size=4>9. cvReleaseImage</font>](#font-colorlightcoral-size49-cvreleaseimagefont)
        - [<font color=LightCoral size=4>10. Mat和IPLImage的区别</font>](#font-colorlightcoral-size410-mat和iplimage的区别font)
        - [<font color=LightCoral size=4>11. CVMAT操作</font>](#font-colorlightcoral-size411-cvmat操作font)
        - [<font color=LightCoral size=4>12. opencv MAT数据操作</font>](#font-colorlightcoral-size412-opencv-mat数据操作font)
        - [<font color=LightCoral size=4>13. CV_MAT_ELEM</font>](#font-colorlightcoral-size413-cv_mat_elemfont)
        - [<font color=LightCoral size=4>14. 提取二值图像轮廓</font>](#font-colorlightcoral-size414-提取二值图像轮廓font)
        - [<font color=LightCoral size=4>15. boundingRect、minAreaRect的用法</font>](#font-colorlightcoral-size415-boundingrectminarearect的用法font)
        - [<font color=LightCoral size=4>16. getRotationMatrix2D的用法</font>](#font-colorlightcoral-size416-getrotationmatrix2d的用法font)
        - [<font color=LightCoral size=4>17. Mat类型数据创建总结</font>](#font-colorlightcoral-size417-mat类型数据创建总结font)
        - [<font color=LightCoral size=4>18. OTSU算法（大津法）</font>](#font-colorlightcoral-size418-otsu算法大津法font)
        - [<font color=LightCoral size=4>16. </font>](#font-colorlightcoral-size416-font)
    - [<font color=Crimson size=4>VScode</font>](#font-colorcrimson-size4vscodefont)
        - [<font color=LightCoral size=4>VScode教程</font>](#font-colorlightcoral-size4vscode教程font)
    - [<font color=Crimson size=4>CANoe</font>](#font-colorcrimson-size4canoefont)
        - [<font color=LightCoral size=4>CANoe教程</font>](#font-colorlightcoral-size4canoe教程font)
    - [图书](#图书)

<!-- /TOC -->

---------------------------------------------------------------

## <font color=Crimson size=4>Linux</font>
<details>
<summary>语法内容</summary>

<table><tr><td bgcolor=DimGray Gainsboro>

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


</td></tr></table>
</details>
<br>

<font color=gray size=2>*[返回目录](#font-colorcrimson-size4目录font)*</font>

---------------------------------------------------------------

## <font color=Crimson size=4>MarkDown</font>

<details>
<summary>语法内容</summary>

<table><tr><td bgcolor=DimGray>

```markdown
Markdown 标题：
# 这是 H1
## 这是 H2
### 这是 H3

Markdown 列表：
- 列表项目
1. 列表项目

*斜体*或_斜体_
**粗体**
***加粗斜体***
~~删除线~~

Markdown 插入链接：
[链接文字](链接网址 "标题")

Markdown 插入图片：
![alt text](/path/to/img.jpg "Title")

Markdown 插入代码块：
    ```python
    #!/usr/bin/python3
    print("Hello, World!");
    ```

Markdown 引用：
> 引用内容

Markdown 分割线：
---

Markdown 换行：
<br>

Markdown 段首缩进：
&ensp; or &#8194; 表示一个半角的空格
&emsp; or &#8195;  表示一个全角的空格
&emsp;&emsp; 两个全角的空格（用的比较多）
&nbsp; or &#160; 不断行的空白格

Markdown 文本折叠：
<details>
<summary>语法内容</summary>
content
</details>

Markdown 文本字体格式修改：
<font color=gray size=2>content</font>

Markdown 当前文件夹下图片：
![](./picture/example.png '描述')
```

</td></tr></table>
</details>

<details>
<summary>参考链接</summary>
<table><tr><td bgcolor=#333333>

* [MARKDOWN中修改字体和颜色](https://blog.csdn.net/qq_35896136/article/details/104379671)
* [MarkDown语法总结](https://www.cnblogs.com/linbudu/p/11367763.html)

</td></tr></table>
</details>

<br>

*[返回目录](#font-colorcrimson-size4目录font)*

-------------------------------------------------------------

## <font color=Crimson size=4>C++</font>

### <font color=LightCoral size=4>1. int main(int argc,char* argv[])详解</font>
* [int main(int argc,char* argv[])详解](https://www.cnblogs.com/avril/archive/2010/03/22/1691477.html)

### <font color=LightCoral size=4>2. Linux下C++ 创建文件夹</font>
* [Linux下C++ 创建文件夹](https://blog.csdn.net/Sway_2012/article/details/8651477)

### <font color=LightCoral size=4>3. C/C++ 中 static 的用法全局变量与局部变量</font>
* [C/C++ 中 static 的用法全局变量与局部变量](https://www.runoob.com/w3cnote/cpp-static-usage.html)

### <font color=LightCoral size=4>4. 指针malloc分配空间与数组区别</font>
* [指针malloc分配空间与数组区别](https://blog.csdn.net/qq361294382/article/details/52027448)

### <font color=LightCoral size=4>5. 空指针和void *类型指针</font>
* [空指针和void *类型指针](https://blog.csdn.net/luo_technically/article/details/52714389)

### <font color=LightCoral size=4>6. C++ void*指针、多重指针void**和指针大小</font>
* [C++ void*指针、多重指针void**和指针大小](https://blog.csdn.net/Gordennizaicunzai/article/details/78007584)

*[返回目录](#font-colorcrimson-size4目录font)*

-------------------------------------------------------------

## <font color=Crimson size=4>线程相关</font>
### <font color=LightCoral size=4>1. 线程信号量</font>
* [信号量sem_init,sem_wait,sem_post](https://blog.csdn.net/u013457167/article/details/78318932)

### <font color=LightCoral size=4>2. 线程创建C语言示例</font>
<details>
<summary>原文内容</summary>
<table><tr><td bgcolor=DimGray>

```C
#include <stdio.h>
#include <unistd.h>
#include <stdlib.h>
#include <string.h>
#include <pthread.h>
#include <semaphore.h>

  sem_t sem;

  void func1(void* arg)
  {
      for(int i=1;i<=10;i++)
      {
          sem_wait(&sem);
          int *running=arg;
          printf("pthread1--%d\n",i);
          printf("%d\n",*running);
      }
  }

  void func2(void* arg)
  {
      printf("pthread2\n");
      sem_post(&sem);
  }

  int main()
  {
      sem_init(&sem,0,1);
      pthread_t thread[2];
      int a=5;
      pthread_create(&(thread[0]),NULL,(void*)func1,(void*)&a);
      printf("main thread 1\n");
      sleep(3);
      pthread_create(&(thread[1]),NULL,(void*)func2,(void*)&a);
      printf("main thread 2\n");
      printf("step3\n");
      pthread_join(thread[1],NULL);
      printf("step4\n");
      pthread_join(thread[0],NULL);
      printf("step5\n");
      sem_destroy(&sem);
      printf("step6\n");
      return 0;
  }

```
</td></tr></table>
</details>

*[返回目录](#font-colorcrimson-size4目录font)*

-------------------------------------------------------------

## <font color=Crimson size=4>总线通信相关</font>
### <font color=LightCoral size=4>1. DBus通信</font>
* [DBUS基础知识](https://www.cnblogs.com/wzh206/archive/2010/05/13/1734901.html)
* [和菜鸟一起学linux之DBUS基础学习记录](https://blog.csdn.net/eastmoon502136/article/details/10044993)
* [DBus学习笔记](https://blog.csdn.net/lizzywu/article/details/7651441)

*[返回目录](#font-colorcrimson-size4目录font)*

-------------------------------------------------------------

## <font color=Crimson size=4>摄像机</font>

### <font color=LightCoral size=4>1. 摄像机标定</font>
* [单目摄像头标定与畸变矫正（C++，opencv）](https://zhuanlan.zhihu.com/p/55648494?utm_source=wechat_timeline)

### <font color=LightCoral size=4>2. 相机成像原理/四种坐标系</font>
* [相机成像原理：世界坐标系、相机坐标系、图像坐标系、像素坐标系之间的转换](https://blog.csdn.net/chentravelling/article/details/53558096)

### <font color=LightCoral size=4>3. 内\外参矩阵和畸变矩阵</font>
* [相机标定（1）内\外参矩阵和畸变矩阵](https://blog.csdn.net/qq_30815237/article/details/87530011)

### <font color=LightCoral size=4>4. OPenCV相机标定函数ProjectPoints2</font>
* [OPenCV相机标定函数](https://blog.csdn.net/haima1998/article/details/81056773)

### <font color=LightCoral size=4>5. 相机标定之棋盘标定/各类函数</font>
* [相机标定之棋盘标定](https://blog.csdn.net/qq_38241538/article/details/83152265)

*[返回目录](#font-colorcrimson-size4目录font)*

-------------------------------------------------------------

## <font color=Crimson size=4>图像处理</font>

### <font color=LightCoral size=4>1. 车牌识别:</font>
* [非常详细的讲解车牌识别easypr](https://blog.csdn.net/qq_31186123/article/details/78661566)
* [EasyPR--一个开源的中文车牌识别系统](https://www.cnblogs.com/subconscious/p/3979988.html)
* [《Mastering Opencv ...读书笔记系列》车牌识别（I）](https://blog.csdn.net/jinshengtao/article/details/17883075)
* [《Mastering Opencv ...读书笔记系列》车牌识别（II）](https://blog.csdn.net/jinshengtao/article/details/17954427)

### <font color=LightCoral size=4>2. 二值化:</font>
* [二值化图像切割，让机器人视觉识别变得简单高效](https://mp.weixin.qq.com/s?__biz=MzA3ODg5MTIxOQ==&mid=2651205111&idx=1&sn=ab39b5341264312f42f654c92de6dfc4&chksm=84495c4bb33ed55d9e62e3f8b5c5deaddb178479f671f2ccf0048ed55b9aa7d9b55dae2674d1&scene=21#wechat_redirect)

*[返回目录](#font-colorcrimson-size4目录font)*

-------------------------------------------------------------

## <font color=Crimson size=4>OpenCV</font>

### <font color=LightCoral size=4>1. 光流法calcOpticalFlowPyrLK()使用语法:</font>
* [光流法原理1](https://blog.csdn.net/AP1005834/article/details/51226660)

* [光流法原理2](https://blog.csdn.net/crzy_sparrow/article/details/7407604)

* [函数使用方法原文1](https://blog.csdn.net/qq_21770839/article/details/101054757)
<details>
<summary>原文内容</summary>
<table><tr><td bgcolor=DimGray>

```C++
calcOpticalFlowPyrLK()
void cv::calcOpticalFlowPyrLK ( InputArray prevImg,
		InputArray nextImg,
		InputArray prevPts,
		InputOutputArray nextPts,
		OutputArray status,
		OutputArray err,
		Size winSize = Size(21, 21),
		int maxLevel = 3,
		TermCriteria criteria = TermCriteria(TermCriteria::COUNT+TermCriteria::EPS, 30, 0.01),
		int flags = 0,
		double minEigThreshold = 1e-4
	)

/****************************参数：****************************************

    prevImg ：buildOpticalFlowPyramid构造的金字塔或第一个8位输入图像
    nextImg ：与prevImg相同大小和相同类型的金字塔或第二个输入图像
    prevPts ：需要找到流的2D点的矢量(vector of 2D points for which the flow needs to be found;);点坐标必须是单精度浮点数。
    nextPts ：输出二维点的矢量（具有单精度浮点坐标），包含第二图像中输入特征的计算新位置;当传递OPTFLOW_USE_INITIAL_FLOW标志时，向量必须与输入中的大小相同。
    status ：输出状态向量（无符号字符）;如果找到相应特征的流，则向量的每个元素设置为1，否则设置为0。
    err ：输出误差的矢量; 向量的每个元素都设置为相应特征的误差，误差度量的类型可以在flags参数中设置; 如果未找到流，则未定义误差（使用status参数查找此类情况）。
    winSize ：每个金字塔层的搜索窗口的大小。
    maxLevel ：基于0的最大金字塔等级数;如果设置为0，则不使用金字塔（单级），如果设置为1，则使用两个级别，依此类推;如果将金字塔传递给输入，那么算法将使用与金字塔一样多的级别，但不超过maxLevel。
    criteria ：参数，指定迭代搜索算法的终止条件（在指定的最大迭代次数criteria.maxCount之后或当搜索窗口移动小于criteria.epsilon时）。
    flags ：操作标志：
        OPTFLOW_USE_INITIAL_FLOW使用初始估计，存储在nextPts中;如果未设置标志，则将prevPts复制到nextPts并将其视为初始估计。
        OPTFLOW_LK_GET_MIN_EIGENVALS使用最小特征值作为误差测量（参见minEigThreshold描述）;如果没有设置标志，则将原稿周围的色块和移动点之间的L1距离除以窗口中的像素数，用作误差测量。
    minEigThreshold ：算法计算光流方程的2x2正常矩阵的最小特征值，除以窗口中的像素数;如果此值小于minEigThreshold，则过滤掉相应的功能并且不处理其流程，因此它允许删除坏点并获得性能提升。
*/
//该函数实现了金字塔中Lucas-Kanade光流的稀疏迭代版本。

```
</table></tr></td>
</details>

```C++
Mat_<int> layerSizes(1, 3);
layerSizes(0, 0) = data.cols;
layerSizes(0, 1) = 20;
layerSizes(0, 2) = responses.cols;
```
* [函数使用方法原文2](https://blog.csdn.net/qq_29541381/article/details/80154329)

### <font color=LightCoral size=4>2. 光流法calcOpticalFlowFarneback()</font>
* [Farneback 光流算法详解与 calcOpticalFlowFarneback 源码分析](https://blog.csdn.net/u011808673/article/details/80999716)

### <font color=LightCoral size=4>3. 角点检测函数goodFeaturesToTrack</font>
* [goodFeaturesToTrack——Shi-Tomasi角点检测](https://blog.csdn.net/dcrmg/article/details/52551637)

### <font color=LightCoral size=4>4. 移动目标检测</font>
* [光流法(optical flow)运动检测](https://blog.csdn.net/Lemon_jay/article/details/89476029)

### <font color=LightCoral size=4>5. cvSetImageROI</font>
* [利用cvSetImageROI截取/裁剪图片](https://blog.csdn.net/chentravelling/article/details/45331225)

### <font color=LightCoral size=4>6. cvAddWeighted</font>
* [OpenCV中cvAddWeighted和Alpha混合](https://blog.csdn.net/Augusdi/article/details/11523631)

### <font color=LightCoral size=4>7. cvCreateImage</font>
* [cvCreateImage函数说明](https://blog.csdn.net/breeze5428/article/details/30050327)

### <font color=LightCoral size=4>8. cvResize</font>
* [OpenCV中的图像尺寸调整cvResize](https://blog.csdn.net/dyzok88/article/details/41487925)

### <font color=LightCoral size=4>9. cvReleaseImage</font>
* [cvReleaseImage()函数说明](https://www.cnblogs.com/stemon/p/5037286.html)

### <font color=LightCoral size=4>10. Mat和IPLImage的区别</font>
* [Mat和IPLImage](https://blog.csdn.net/qq_37764129/article/details/81271660)

### <font color=LightCoral size=4>11. CVMAT操作</font>
* [CVMAT操作](https://www.cnblogs.com/mysunnyday/archive/2011/08/05/2128197.html)

### <font color=LightCoral size=4>12. opencv MAT数据操作</font>
* [opencv MAT数据操作](https://blog.csdn.net/huixingshao/article/details/46468131)

### <font color=LightCoral size=4>13. CV_MAT_ELEM</font>
* [CV_MAT_ELEM——获取矩阵元素和初始化矩阵](https://blog.csdn.net/u010361581/article/details/9253039)

### <font color=LightCoral size=4>14. 提取二值图像轮廓</font>
* [findContours函数的使用（基于Mat轮廓处理基础](https://blog.csdn.net/u012566751/article/details/77718752)
* [轮廓提取findContours和绘制drawContours](https://blog.csdn.net/fengye2two/article/details/79101968)
* [openCV之drawContours()绘制轮廓函数](https://blog.csdn.net/u011479336/article/details/91558864)

### <font color=LightCoral size=4>15. boundingRect、minAreaRect的用法</font>
* [OpenCV 中boundingRect、minAreaRect的用法区别](https://blog.csdn.net/u013925378/article/details/84563011)

### <font color=LightCoral size=4>16. getRotationMatrix2D的用法</font>
* [图像处理-几何图像变换-cv::getRotationMatrix2D(矩阵旋转与缩放)](https://blog.csdn.net/charce_you/article/details/100177792)

### <font color=LightCoral size=4>17. Mat类型数据创建总结</font>
* [Opencv显示创建Mat对象的七种方式](https://blog.csdn.net/qq_23880193/article/details/47903143)

### <font color=LightCoral size=4>18. OTSU算法（大津法）</font>
* [OpenCV实现OTSU算法（大津法）](https://blog.csdn.net/Stone_Wang_MZ/article/details/107470417)
* [用OpenCV实现Otsu算法](https://www.cnblogs.com/moon1992/p/5092726.html)

<details>
<summary>原文内容</summary>
<table><tr><td bgcolor=DimGray>

```C++
Mat_<int> layerSizes(1, 3);
layerSizes(0, 0) = data.cols;
layerSizes(0, 1) = 20;
layerSizes(0, 2) = responses.cols;
```
```C++
float labels[3][2] = {{0.9,0.1},{0.1,0.9},{0.9,0.1}};  
Mat labelsMat(3, 2, CV_32FC1, labels); 
```
```C++
Mat array = (Mat_<double>(3, 3) << 0, -1, 5, -1, 5, -1, 0, -1, 0);
```
```C++
Mat img(2, 2, CV_8UC3, Scalar(0, 255, 255));
```
```C++
int sz[3] = { 2, 2, 2 };
//3维的  为2*2*2的   元素全部为0
Mat array2(3, sz, CV_8UC1, Scalar(0));
```
```C++
Mat img;
img.create(4, 4, CV_8UC(2));
```
```C++
Mat array1 = Mat::eye(4, 4, CV_64F);
Mat array2 = Mat::ones(4, 4, CV_32F);
Mat array3 = Mat::zeros(4, 4, CV_8UC1);
```
* [OpenCV从Mat中提取某些行或列](https://blog.csdn.net/lichengyu/article/details/21407393)
```C++
Mat row = Img.rowRange(1,3).clone();
```

</table></tr></td>
</details>

### <font color=LightCoral size=4>16. </font>
* []()

<br>

*[返回目录](#font-colorcrimson-size4目录font)*

---------------------------------------------------------------
## <font color=Crimson size=4>VScode</font>
### <font color=LightCoral size=4>VScode教程</font>
* [linux系统下如何在vscode中调试C++代码](https://www.cnblogs.com/jiaxblog/p/9902535.html)
* [Ubuntu16.04 中 Vscode 如何断点调试C语言程序](https://www.cnblogs.com/feiffy/p/8627812.html)
* 调试要在编译时添加个<kbd>-g</kbd>命令

<br>

*[返回目录](目录)*

---------------------------------------------------------------
## <font color=Crimson size=4>CANoe</font>
### <font color=LightCoral size=4>CANoe教程</font>
* [CANoe教程资源汇总](https://zhuanlan.zhihu.com/p/45211631)
* [CANoe学习4—CAPL语言设计](https://zhuanlan.zhihu.com/p/128060866)


<br>

*[返回目录](#font-colorcrimson-size4目录font)*

---------------------------------------------------------------





## 图书
* [C++ primer plus](file:///data/Haro/学习/01编程/01C_C++/01书籍/C++谭浩强.pdf)

* xdg-open /data/Haro/学习/01编程/01C_C++/01书籍/C++谭浩强[pdf]


```mermaid
flowchat
st=>start: 开始
e=>end: 结束
op=>operation: 我的操作
cond=>condition: 确认？

st->op->cond
cond(yes)->e
cond(no)->op
```

<kbd>cond(no)->op</kbd>
