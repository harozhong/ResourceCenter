<td bgcolor=DimGray>

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

</td>