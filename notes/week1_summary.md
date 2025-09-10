{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "ec19bc28-befe-4f3c-8fe3-736f019e90b6",
   "metadata": {},
   "source": [
    "# Week 1 总结（Day1–Day7）\n",
    "\n",
    "## 我学了什么\n",
    "- [1] 熟悉 GitHub：创建仓库、提交 notebook\n",
    "- [1] PyTorch 基础：张量创建、自动求导\n",
    "- [ ] 线性代数在神经网络里的应用（点积、矩阵乘法）\n",
    "- [ ] Logistic Regression 在 MNIST 上的训练过程\n",
    "- [ ] 训练循环的关键步骤：\n",
    "  - `zero_grad()` → 清空梯度\n",
    "  - `forward()` → 前向传播\n",
    "  - `loss.backward()` → 反向传播，计算梯度\n",
    "  - `optimizer.step()` → 梯度下降，更新参数\n",
    "\n",
    "## 我遇到的困难\n",
    "- [ ] 理解 logits（未归一化分数） vs softmax 概率 的区别\n",
    "- [ ] 梯度到底代表什么？为什么“往负梯度方向走”会下降\n",
    "- [ ] 学习率（lr）的选择如何影响训练效果\n",
    "- [ ] GitHub 上传 notebook 的流程有时不太熟练\n",
    "\n",
    "## 下周目标（Week2）\n",
    "- [ ] 学会搭建一个 CNN baseline，并与 Logistic Regression 对比\n",
    "- [ ] 学习正则化方法：Dropout, Weight Decay\n",
    "- [ ] 尝试优化器对比：SGD vs Adam\n",
    "- [ ] 阅读《Deep Learning》Ch.5（机器学习基础）\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
