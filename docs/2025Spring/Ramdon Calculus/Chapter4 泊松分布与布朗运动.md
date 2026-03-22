## 三、布朗运动
#### 1. 定义
$$#### （一）布朗运动的定义及数字特征 考虑一直线上的简单对称的随机游动，设质点每隔\(\Delta t\)时间等概率地向左或向右移动距离\(\Delta x\)，且每次移动相互独立，记 \[X_i = \begin{cases} 1, & \text{第}i\text{次质点右移},\\ - 1, & \text{第}i\text{次质点左移}. \end{cases} i = 1,2,\cdots\] \(X(t)\)表示时刻\(t\)质点的位置，则有 \[X(t)=\Delta x(X_1 + X_2+\cdots+X_{[\frac{t}{\Delta t}]})\] 设\(\Delta x=\sigma\sqrt{\Delta t}\)，当\(\Delta t\rightarrow0\)$$
$$(1) \(E[X(t)] = 0\)，\(D[X(t)]=\sigma^2t\) 由中心极限定理，\(X(t)\sim N(0,\sigma^2t)\) (2) \(\{X(t),t\geq0\}\)是平稳独立增量过程，即 \(0\leq s < t\)，\(X(t)-X(s)\sim N(0,\sigma^2(t - s))\)$$

$$$$
- 常用极限：[【高等数学】常用极限、求导、级数_极限求导lim公式-CSDN博客](https://blog.csdn.net/lafea/article/details/115031060)
- 洛必达： [洛必达法则_百度百科](https://baike.baidu.com/item/%E6%B4%9B%E5%BF%85%E8%BE%BE%E6%B3%95%E5%88%99/7646700)
	- [【洛必达】一篇文章，给高中生讲清楚洛必达 - 知乎](https://zhuanlan.zhihu.com/p/107077095)

---
- References
	- [3 泊松过程 | 应用随机过程](https://www.math.pku.edu.cn/teachers/lidf/course/stochproc/stochprocnotes/html/_book/poisson.html)
	- [05.第三章 Poisson过程(3)_非齐次泊松过程-CSDN博客](https://blog.csdn.net/jingye333/article/details/108434989)