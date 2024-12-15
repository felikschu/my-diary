## 2024.12.15
昨天学习了感知机算法以及部分的支持向量机算法。说实话学习过程中有一种深刻的感触：数学没白学。不仅没白学，而且还远远没学够。

例如最简单的感知机模型，就是解决一个线性可分数据集的二分类问题，而且分类结果也不一定是唯一的。这里面的学习算法就是随机梯度下降，是本学期运筹学课上的内容。此外，在上学期的数值分析中也学习过。
很多时候数学系的学生会抱怨说学了一大堆没用的知识，但是现在接触了大创和一些统计学习内容，才发现这些知识确实都是必要的，如果没有事先学过这些内容的话就会导致学习曲线异常陡峭，初学者就没法把握算法思想的脉络，
而是深陷在数学概念与数学推导中。

再比如说支持向量机，这里面对数学的要求就更高了。这里面使用了诸多凸优化工具，比如，在**线性支持向量机与硬间隔最大化**上，用到了拉格朗日对偶性，KTT条件等，这些都是运筹学课程上的内容。首先，它把一个原始最优化问题
表示为了广义拉格朗日函数的极小极大问题，然后再考虑这个极小极大问题的对偶问题，利用解对偶问题来替代原始问题。再比如，在**线性支持向量机与软间隔最大化**上，由于线性不可分，因此要引入一个松弛变量$\xi$,并在
目标函数中增加一个关于$\xi$的项作为补偿。