

# 课题记录
## 24-0518开题
[开题报告](开题报告.pdf)
主要参考：[《Interpretable image-based deep learning for price trend prediction in ETF markets》](<Zhang 等 - 2023 - Interpretable image-based deep learning for price .pdf>)，

上述文章又参考了[(Re‐)Imag(in)ing Price Trends](<Jiang 等 - 2023 - (Re‐)Imag(in)ing Price Trends.pdf>)

整体思路：

1.将股票数据利用波峰波谷、布林带等技术方法拆分成不同长度的数据，然后绘制成图像

2.用图像分类算法进行涨跌预测

问题：

胡杰老师：图像中没有具体的数值数据，那为什么不用图神经网络的方法
## 24-0521

1.能不能加入资金流向等数据

2.变长数据选择可以增加上下限，如5-30天

3.主要看模型效果，北大张瑞勋教授的模型准确率大概在56%

## 24-0619
单个代码：提高准确率很难，市场应该是联动的反应，要么画图，把部分股票的所有图拿进来
而LSTM等时间序列方法，大概只能选一只，

先把相关的模型、算法看一下，花两周时间把文献中的方法整理一下，不一定是图像预测分类，近两年做预测的各种方法，如扩散模型、transformer、attention-LSTM、强化学习，看一下效果，预测准确率、策略收益率等


# 课题进展

## K线数据拆分

## 图像分类预测

先按定长时间图像进行预测？

学习一下图像分类的算法实践

## (Re‐)Imag(in)ing Price Trends代码参考
找到了复现文章《(Re‐)Imag(in)ing Price Trends》的Github
https://github.com/RichardS0268/CNN-for-Trading

https://github.com/lich99/Stock_CNN?tab=readme-ov-file

