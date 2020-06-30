
# <font color=Crimson size=4>目录</font>

<!-- TOC -->

- [<font color=Crimson size=4>目录</font>](#font-colorcrimson-size4目录font)
    - [<font color=Crimson size=4>Linux</font>](#font-colorcrimson-size4linuxfont)
    - [<font color=Crimson size=4>MarkDown</font>](#font-colorcrimson-size4markdownfont)
    - [<font color=Crimson size=4>C++</font>](#font-colorcrimson-size4cfont)
        - [<font color=LightCoral size=4>1. int main(int argc,char* argv[])详解</font>](#font-colorlightcoral-size41-int-mainint-argcchar-argv详解font)
    - [<font color=Crimson size=4>线程相关</font>](#font-colorcrimson-size4线程相关font)
        - [<font color=LightCoral size=4>1. 线程信号量</font>](#font-colorlightcoral-size41-线程信号量font)
        - [<font color=LightCoral size=4>2. 线程创建C语言示例</font>](#font-colorlightcoral-size42-线程创建c语言示例font)
    - [<font color=Crimson size=4>OpenCV</font>](#font-colorcrimson-size4opencvfont)
        - [<font color=LightCoral size=4>1. 光流法calcOpticalFlowPyrLK()使用语法:</font>](#font-colorlightcoral-size41-光流法calcopticalflowpyrlk使用语法font)
        - [<font color=LightCoral size=4>2. 光流法calcOpticalFlowFarneback()</font>](#font-colorlightcoral-size42-光流法calcopticalflowfarnebackfont)
        - [<font color=LightCoral size=4>3. 角点检测函数goodFeaturesToTrack</font>](#font-colorlightcoral-size43-角点检测函数goodfeaturestotrackfont)
        - [<font color=LightCoral size=4>4. 移动目标检测</font>](#font-colorlightcoral-size44-移动目标检测font)
        - [<font color=LightCoral size=4>5. cvSetImageROI</font>](#font-colorlightcoral-size45-cvsetimageroifont)
        - [<font color=LightCoral size=4>6. cvAddWeighted</font>](#font-colorlightcoral-size46-cvaddweightedfont)
        - [<font color=LightCoral size=4>7. cvCreateImage</font>](#font-colorlightcoral-size47-cvcreateimagefont)
        - [<font color=LightCoral size=4>8. cvResize</font>](#font-colorlightcoral-size48-cvresizefont)
        - [<font color=LightCoral size=4>9. cvResize</font>](#font-colorlightcoral-size49-cvresizefont)
        - [<font color=LightCoral size=4>10. Mat和IPLImage的区别</font>](#font-colorlightcoral-size410-mat和iplimage的区别font)
        - [<font color=LightCoral size=4>11. CVMAT操作</font>](#font-colorlightcoral-size411-cvmat操作font)
    - [<font color=Crimson size=4>VScode</font>](#font-colorcrimson-size4vscodefont)
        - [<font color=LightCoral size=4>VScode教程</font>](#font-colorlightcoral-size4vscode教程font)
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

**7. 获取文件夹目录**
1. 获取当前文件夹目录
* `$PWD`
* `pwd`
2. 获取上一级目录
* `dirname "$PWD"`
* `` dirname `pwd` ``
3. 当前文件夹名
* `basename "$PWD"`
* `` basename `pwd` ``

**8. 终端打开文件(等同于双击)**
* `xdg-open /data/Haro/学习/01编程/01C_C++/01书籍/C++谭浩强.pdf`

**9. 从windows到linux的文本转码**
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

### <font color=LightCoral size=4>9. cvResize</font>
* [cvReleaseImage()函数说明](https://www.cnblogs.com/stemon/p/5037286.html)

### <font color=LightCoral size=4>10. Mat和IPLImage的区别</font>
* [Mat和IPLImage](https://blog.csdn.net/qq_37764129/article/details/81271660)

### <font color=LightCoral size=4>11. CVMAT操作</font>
* [CVMAT操作](https://www.cnblogs.com/mysunnyday/archive/2011/08/05/2128197.html)



<br>

*[返回目录](#font-colorcrimson-size4目录font)*

---------------------------------------------------------------
## <font color=Crimson size=4>VScode</font>
### <font color=LightCoral size=4>VScode教程</font>
* [linux系统下如何在vscode中调试C++代码](https://www.cnblogs.com/jiaxblog/p/9902535.html)
* [Ubuntu16.04 中 Vscode 如何断点调试C语言程序](https://www.cnblogs.com/feiffy/p/8627812.html)


<br>

*[返回目录](#font-colorcrimson-size4目录font)*

---------------------------------------------------------------


## 图书
* [C++ primer plus](file:///data/Haro/学习/01编程/01C_C++/01书籍/C++谭浩强.pdf)

* xdg-open /data/Haro/学习/01编程/01C_C++/01书籍/C++谭浩强[pdf]

[pdf]:fdhf

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
