# 数据管理

当我们的数据进入了系统,如何管理这些数据就成了问题,数据管理是为了让可以使用数据的人可以有数据可用,可以快速找到需要的数据;同时确保数据的安全性和整个数据流转的性能.
因此数据管理是个偏向架构偏向工程的工作.需要对数据库,消息中间件,以及如何搭配使用这些工具有所了解;同时也要对数据的压缩, 加密,序列化保存有一定了解.

学习数据科学的人可能最开始会认为机器学习,算法是数科学的核心,但实际上一旦接触了实际工程就会发现数据管理才是数据科学的核心.算法其实是数据本身的一个表现,算法可以决定数据使用效果的上限,而数据管理可以决定使用效果的下限.


本篇是相关技术的个人最佳实践总结,将介绍如下内容:


+ 数据的标准化

+ 数据的生命周期

+ 数据的流转

  + 流数据与事件驱动

  + 存量数据的处理过程

+ 数据的保存

  + 分析型数据库与近期数据保存

  + 远期数据留档

+ 数据的监控