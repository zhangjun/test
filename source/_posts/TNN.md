---
title: TNN
date: 2021-03-06 07:17:58
tags: [TNN, Mobile AI, Tencent]
excerpt: 介绍腾讯TNN深度学习推理框架的编译和使用方法。包括从GitHub下载源码、使用CMake在Linux x86平台编译配置，以及提供基础的模型部署示例代码。
---
本文主要介绍Tencent TNN编译使用。

# 下载编译
## 下载
``` shell
git clone github.com/Tencent/TNN
```
其他需要cmake、opencv，单独安装
## linux x86
```
mkdir build && cd build
cmake .. -DTNN_X86_ENABLE=ON
```


# 模型部署示例
``` c
int main(){
  return main();
}
```