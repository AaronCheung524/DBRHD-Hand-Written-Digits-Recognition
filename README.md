# DBRHD数据集手写数字识别

华中某985高级人工智能课程大作业

要求分别采用以下算法实现手写数字识别模型，数据集为DBRHD数据集，并采用python进行实现，数据显示可以采用matplotlib库：
1. KNN算法，可以采用sklearn库，也可以自己实现knn算法
2. 全连接的神经网络模型，采用sklearn库中的神经网络函数
3. 全连接的神经网络模型，只能采用Numpy库，不能采用任何其他的神经网络函数库
4. CNN（卷积）神经网络模型，可以采用sklearn库中的神经网络函数，或者其他的神经网络函数库 (但是sklearn好像没有CNN......)

## 关于数据集
对于DBRHD数据集，大部分参考资料说的是[Pen-Based Recognition of Handwritten Digits](https://archive.ics.uci.edu/dataset/81/pen+based+recognition+of+handwritten+digits)
但是用的是[Optical Recognition of Handwritten Digits](https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits)
这个不知道是什么原因，这里本人使用的是[Pen-Based Recognition of Handwritten Digits](https://archive.ics.uci.edu/dataset/81/pen+based+recognition+of+handwritten+digits), 因为长得更像DBRHD的缩写。

## NumPy实现MLP
该部分的代码基本来自[Numpy 手撸MLP](https://zhuanlan.zhihu.com/p/501743440), 点个赞同👍

## CNN部分
其实用TensorFlow+Keras会简单一些但是TensorFlow版本兼容实在是太幽默了

## 如何使用
运行以下上面的.ipynb文件, 等到它跑完就可以了, 方便得很, 哥
主要的环境版本为 Python 3.8, PyTorch 1.10, NumPy 1.23.2
环境上面应该问题不大


