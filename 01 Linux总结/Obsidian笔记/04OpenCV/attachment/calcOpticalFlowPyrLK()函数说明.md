<td bgcolor=DimGray>

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
</td>