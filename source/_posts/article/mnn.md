---
title: MNN
date: 2021-06-07 12:27:48
tags: [MNN, Mobile AI, Alibaba]
excerpt: 阿里巴巴MNN深度学习推理框架编译使用指南，包括源码下载、Linux x86平台编译配置、模型部署示例等移动端AI推理技术。
---
本文主要介绍Alibaba MNN编译使用。

# 下载编译
## 下载
``` shell
git clone github.com/alibaba/MNN
```
## linux x86
```
./schema/generate.sh
mkdir build && cd build && cmake .. && make -j4
```
refer to ```https://www.yuque.com/mnn/en/build_linux```


# 模型部署示例
``` c
int main(){
  return main();
}
```