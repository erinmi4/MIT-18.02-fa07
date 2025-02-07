![[lec02.pdf]]


### 矩阵
- 通过改变坐标系统，使得从一个空间转化到另一个空间之中

#### 矩阵运算
- 不具备交换性
	- BX=将变换B应用于向量X

**附加矩阵的求法**
1. 求出余子式——将每一个元素去掉所在行，所在列，然后求矩阵获得的值，填入相同位置
2. 符号翻转——写出符号矩阵，最上方 + ， 然后每个周围的符号都是相反的，然后按照顺序修改余子式
3. 将结果求偏置矩阵 得到结果；


#### 平面方程
	- 平面方程是法向量和一系列点做点积，且点积为0 ， n = (a , b , c ) , 这些点就是 a = (x, y ,z ) . ax + by + cz = 0 

**如何找到法向量**
求出一个平面上任意两个向量的cross product 

**从平面方程来看矩阵方程**
- 矩阵上看
	- 将三个向量从 X 坐标上变换得到 U
- 从几何上看
	- 三个平面的交集

其中有三种情况
1. P1交与P2的直线，令其为L， L与P3相交于一个点。**唯一解**
2. L与P3平行。**没有解**
3. L在P3内部。**五穷解**

通过det（n1,n2,n3)  ？= 0
可以判断三者法向量的关系

1. det != 0 可以判断有唯一解
2. det = 0 是无解和无穷解之中一种。
![[Pasted image 20240911193052.png]]



### 直线方程
- 是P1相交与P2为L 直线


#### 如何表示一条直线
- 使用Q0 和 Q1 来确定方向。
- 不妨认为Q0为起点，Qt以时间为t在直线上移动。
![[Pasted image 20240911202328.png]]

#### 确定点和平面关系
将点带入平面方程。判断与结果的大小

#### 如何求得直线与平面交点
Qt带入平面方程
