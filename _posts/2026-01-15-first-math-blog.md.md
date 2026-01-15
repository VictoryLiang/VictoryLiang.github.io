---
title: "我的第一篇数学博客"
date: 2026-01-15
categories: [Math, Notes]
tags: [Gradient Descent, Linear Algebra]
math: true
---

## 引言

这是我写的第一篇博客，记录一些数学笔记和公式测试。

行内公式示例：$E = mc^2$

块公式示例：

$$
\int_0^1 x^2 \, dx = \frac{1}{3}
$$

---

## 1. 梯度下降算法

**定义：** 梯度下降是一种优化算法，用于最小化函数 $f(x)$。

迭代公式：
$$
x_{k+1} = x_k - \alpha \nabla f(x_k)
$$

其中：
- $x_k$：第 k 次迭代的变量  
- $\alpha$：学习率（step size）  
- $\nabla f(x_k)$：函数梯度

---

## 2. 定理示例

**定理 2.1**（凸函数性质）  

如果 $f(x)$ 是凸函数，则对任意 $x, y$ 和 $\lambda \in [0,1]$：
$$
f(\lambda x + (1-\lambda) y) \le \lambda f(x) + (1-\lambda) f(y)
$$

**证明（略）**  

---

## 3. 总结

- 这是第一篇测试博客  
- 支持数学公式和 Markdown 排版  
- 下一篇可以写更复杂的算法和定理

