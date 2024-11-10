# 猫狗分类
这是一个基于pytorch实现的简单猫狗分类器，用到的backbone是卷积神经网络（CNN）中的Resnet
>你可以在 <[这里](https://zhuanlan.zhihu.com/p/360550845)> 找到所有关于这个项目的理论和实践知识
## 快速开始
## 1.安装GPU加速工具链
在开始一切工作前，请先检查你是否为电脑安装了GPU加速工具链，包括（nvidia 驱动，CUDA toolkit，cuDNN）
这一步是必要的，除非你能忍受超过半个小时的训练时间
## 2.环境依赖
请确保你已经安装了minconda,如果没有，请看这篇文档

请在你的IDE终端中进入你创建的conda环境（关于如何创建conda环境，请看这一篇），并且运行以下指令（不知道IDE的看上次的文档）
```
pip install -r requirements.txt
```
等待所有依赖都安装成功
## 3.开始训练
进入train.py,运行即可开始训练
## 4.做出预测
进入evaluate.py,运行即可使用模型做出预测结果




