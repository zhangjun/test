---
title: cudnn
date: 2022-04-06 03:14:08
tags:
excerpt: cuDNN优化设置指南，包括确定性算法配置、非确定性算法选择等性能优化策略，帮助提升深度学习模型在NVIDIA GPU上的运行效率。
---

# cudnn 优化设置

## cudnn deterministic
设置为true，cudnn使用非确定性算法，能够自动寻找最适合当前配置的高效算法，来达到优化运行效率的问题。