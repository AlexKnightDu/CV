# CV
个人简历  

## 教育经历
上海交通大学 图像通信与网络工程研究所 电子系 - 在读硕士研究生    
上海交通大学 计算机系 - 工学学士 &nbsp;  GPA : 3.8/4.3 (前30%) 

## 项目经历
- 神经母细胞瘤CT图像分割：未来媒体协同中心与合作医院的研究项目，根据患者的CT图像进行病灶区域的像素级分割，在主流模型U-Net上进行改进，首先用一个特征提取网络得到图像中病灶的概率分布，然后进行候选区域的筛选，得到病灶可能存在的候选区域后再缩放后交由分割网络进行分割。目前已经取得更优结果，并进一步在空间上下文（3D U-Net)上进行尝试。负责想法构思，代码实现以及实验测试全部内容。
- 近似计算：先进体系结构实验室项目，通过对属较大的神经网络来提升效率。具体实现通过同时训练不同大小的网络，并根据大小网络的预测结果来训练分类器，从而使得分类器可以区分输入数据是否可近似，起到类似路由的作用。负责部分代码实现与实验测试内容。
- 创业平台开发：零号湾园区项目，实现苗圃事务管理、公共设施管理等业务，整体上使用了VUE+Spring，也采用了饿了么前端库等。具体在已搭建好的基础框架上，通过填充各模块（Entity）对应的前后端部分实现具体业务逻辑。主要负责创业项目申请，苗圃入住，会议室管理等业务模块。
- SLAM优化项目：先进体系结构实验室偏工程项目，将Bundle adjustment的部分计算过程迁移至GPU上，测试性能，具体主要参考okvis框架，主要负责测试以及调整。
- 视频内容插入：在视频固定位置插入内容，类似于广告插入，针对视频的不同帧使用SIFT挑选特征点，并用最小二乘根据两帧之间特征点的变化计算得到投影变换，对插入内容进行同样的变换后覆盖到对应位置，从而实现插入内容跟随视频场景进行变化。
- Vdisk爬虫：微盘电子书爬取，通过Beautiful Soup分析网页正则匹配到电子书链接，存到MySQL中，然后在网络空闲时解析链接得到实际url并使用aria2并行下载。
- 分布式框架性能比较:信息论与编码实验室偏工程项目，对比Dask与Spark两个分布式框架在一些大图像(SKA射电望远镜数据)处理问题上的性能，负责代码调试与实验。
- RayTracing渲染：图像学课程作业，实现基本的光线追踪渲染以及常见的插值算法。
- SimPL解释器：程序设计语言作业，在给定框架下（已实现Parsing）使用Java实现基本的解释器，并实现了最基本条件下的多态，垃圾回收以及惰性求值等特性。
- 小车：工科创IIB和IIIC作业，IIB通过摄像头实时采集图像，通过meanshift得到带标记小车位置，对地图进行模糊和二值化等处理得到轨迹，从而对小车进行控制。主要负责小车位置寻找。IIIC通过两部手机之间的wifi连接实现对小车的控制和图像回传。主要负责图传部分的代码编写。


## 技术背景
- 主要使用MacOS，根据不同场景使用Kali, Arch, CentOS与Ubuntu，熟悉Vim，对Git有了解，对awk,sed有一点了解
- 比较熟悉Python，用过Java，C/C++，对JavaScript，SQL，MATLAB(R)有了解，对Lisp，Haskell有一点了解。
- 对机器学习，图形学，信息安全与密码学有过学习
- 对网页以及后端开发，计算机视觉，SLAM，Cuda有一点了解
- 对MSP（开发板），维修电脑/机械键盘有一点了解


## 个人简述
喜欢码代码，喜欢捣鼓和尝试新的事情，爱好游泳，指弹和摄影等，在写过很多代码后愈发感受到了理论基础的重要，所以尽可能修了各个方向的专业课程，看了很多的书，也留下了许多还未填补的坑，最开心的事情之一就是看着这些坑被一个个填满。


