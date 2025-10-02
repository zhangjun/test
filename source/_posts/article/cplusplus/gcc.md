---
title: gcc
date: 2021-04-14 03:51:57
tags:
excerpt: GCC编译器优化技术详解，包括RVO（返回值优化）、NRVO（命名返回值优化）等编译优化策略，以及相关C++代码示例和性能优化技巧。
---

# content

## RVO(Return Value Optimization) 
## NRVO(Named Return Value Optimization)

## code snipts
```
#include <algorithm>
#include <cctype>

std::string lower(const std::string &data) {
  std::string result = data;
  std::transform(result.begin(), result.end(), result.begin(),
    [](unsigned char c){ return std::tolower(c); });
  return result;
}
```