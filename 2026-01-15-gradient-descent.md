---
title: "梯度下降笔记"
date: 2026-01-15
categories: [Math, Optimization]
math: true
---

## 1. 引言

本文记录梯度下降算法的基本原理。

## 2. 定义

**定义 2.1（凸函数）**  
函数 $f$ 是凸的，如果对任意 $x,y$ 和 $\lambda \in [0,1]$：

$$
f(\lambda x + (1-\lambda)y) \le \lambda f(x) + (1-\lambda)f(y)
$$

## 3. 定理

**定理 3.1**  
若 $f$ 可微且凸，则：

$$
f(y) \ge f(x) + \nabla f(x)^\top (y-x)
$$

**证明：** 略
