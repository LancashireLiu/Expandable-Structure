# 可展多面体机构

这个项目是未来技术学院本科二年级设计与建造Ⅱ课程的课程设计，我是本项目的组长。下面Readme文档简要介绍了本项目的过程，上方repository库中包含了项目的全过程以及报告等内容！

***

可展多面体机构是一种在实现其承载功能的前提下，能够大尺寸地改变几何形状与空间构型的结构。

可展多面积机构可以适应不同的应用需求，是空间可折展结构和大型可折展设备的关键技术。

![可展机构](https://github.com/LancashireLiu/Expandable-Structure/blob/main/pic%20and%20video/readmepic1.png)

单自由度可展多面体机构可以实现单一驱动下两个空间构型的切换，如上图中截角八面体和立方体之间的变换，在展开时可大幅增加工作空间与面积，在完全折叠状态下可减少储存和运输空间。对多面体展开与折叠构型进行分析，确定各顶点的运动副类型及方位，用以形成具有协调运动的多面体空间机构网格。

![可展机构](https://github.com/LancashireLiu/Expandable-Structure/blob/main/pic%20and%20video/readmepic2.png)

上图中中层的截角八面体和立方体之间的可展结构就是我们的项目。


为了保证机构在空间中运动是保持单自由度的，多面体每个连杆和正方形表面之间的连接转轴（称为转动副）需要是确定的。这种连杆机构称为Bricard机构，通过空间几何性质可以计算出这些转轴（转动副）和完全活动的顶点（称为球副）的空间坐标和角度。

![可展机构](https://github.com/LancashireLiu/Expandable-Structure/blob/main/pic%20and%20video/readmepic3.png)

> 机构初始状态为一截角八面体，其整体构造如图 1 所示。本机构以三重对称 Bricard 连杆机构为折展运动单元，采用 15 个转动副与 9 个球副。经计算，该可 展机构的自由度为 1。Bricard 机构如图 2 所示。原点的定义及坐标系的建立如图 3 所示。正方形 B 围绕 B1 关节轴线旋转，正方形 C 围绕 C2关节旋转，使 B4与 C2重合，C1 与 B1 重合（如图 4 所示），由于 Bricard 机构的三重对称性以及六 边形 D1D2E1E2F1F2与六边形A1A2C1C2B1B2结构相同，因此可得出其他点的运动 过程。其运动顺序如图 4 所示。

![可展机构](https://github.com/LancashireLiu/Expandable-Structure/blob/main/pic%20and%20video/readmepic3.png)

通过立体几何矩阵理论可以计算出所有结点在空间中的位置和转轴（转动副）的朝向向量。

![可展机构](https://github.com/LancashireLiu/Expandable-Structure/blob/main/pic%20and%20video/readmepic4.png)


之后用Solidworks进行建模，首先建立三个面的Bricard结构，然后用两个相同的Bricard结构拼接成最后的模型。

![可展机构](https://github.com/LancashireLiu/Expandable-Structure/blob/main/pic%20and%20video/readmepic5.png)

![可展机构](https://github.com/LancashireLiu/Expandable-Structure/blob/main/pic%20and%20video/readmepic6.png)

[运动学建模视频](https://github.com/LancashireLiu/Expandable-Structure/blob/main/pic%20and%20video/video1.mp4)

进行零件、静态和动力学建模后，我确定了实物大小，实物材料（表面使用亚克力板，转动副和球副3d打印，连杆不锈钢），使用建模出的数据打印和制作，拼装后得到实物。

![可展机构](https://github.com/LancashireLiu/Expandable-Structure/blob/main/pic%20and%20video/readmepic7.jpg)



