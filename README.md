# Bachelor-Thesis--Chinese
Pei's Bachelor Thesis (in Chinese), first completed in May. 22nd, 2016

### Algorithm Test and A Digital Circuit Design of The DeSTIN Deep Learning Frame
#### Abstract
Our research is based on a brand new frame for deep machine learning(DML): the Deep SpatioTemporal Inference Network(DeSTIN). The DeSTIN is constructed based on the former work of Deep Belief Neural Network and Deep Neural Network. We adopt the online k-means clustering method for the neuron learning process, and with a network of clustering structure, we can extract the feature from different level, which can be used for latter pattern recogition.

The Strengthness of this algorithm is that:
1. It’s much faster and feasible comparing to other kinds of Deep Neural network;
2. It can extract the spatialtempral information effectively; 
3. It’s relatively easy for transplant to digital circuit. 

We first did some research on the algorithm hierarchy: how it can work on some normal learning database; and check it’s robustness and limitation on each kind of learning problem; then we finished the fixed point test with MATLAB; finally we designed the digital circuit’s structure, programmed with Verilog, and do the simulation on Modelsim platform.

--------------------------------------------------------------------------------------------------------------------
# 本科毕业论文

### 《一种深度学习网络的测试与专用电路设计》
#### 摘要
我们的研究基于一种新型的深度学习框架： 深度空时关系推断网络DeSTIN（Deep SpatioTemporal Inference Network）– 这种框架基于一种神经网络结构（Deep Belief Neural Network），通过实时的k-means聚类方法提取特征，逐步提取出高维输入信息内部的有效全局特征，并对其进行监督学习，从而对新的输入进行有效预测。这种神经网络的优点在于数据的实时更新，可以反映出数据的空时依赖关系。

我们首先研究了DeSTIN 算法在算法层次上面的具体实现方法，进行了参数调试；然后进行了相应的定点数测试；之后再利用集成电路设计的方法，设计出一种专用的数字电路进行这种神经网络结构的实现。我们通过Verilog HDL进行编程，设计出专用数字电路的结构，进行了相应的仿真工作，确认了我们的设计的合理性。

我们探讨了其在图像处理上的应用，尤其是对于视频中的动作识别（空时相关的模式）进行深入研究。



使用 [njuthesis文档类](https://github.com/zhangchuheng123/NJUThesis)生成南京大学本科生毕业论文的示例文档
作者：张楚珩，zhangchuheng123 (at) live (dot) com

