---
title: Modern Cpp
date: 2022-01-09 07:03:59
tags: [C++, Modern C++, Programming]
excerpt: Modern C++ programming techniques summary, including C++11/14/17/20 new features, type traits, template metaprogramming, smart pointers, move semantics, and other advanced programming techniques and best practices.
---

# cpp11

## type traits
* std::integral_constant

    wrap a static constant of specified type. Defined in <type_traits>
    ```
    template<class T, T v>
    struct integral_constant;
    ``` 
