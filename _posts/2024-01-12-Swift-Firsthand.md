---
title: Happy New Year!
author: Wan
date: 2023-12-31 17:31:00 +0800
categories: [Coding, Swift]
tags: [UI For Apple]
---

# Swift 从这里开始

重新从头复习一下Swift，自己也不知道为什么想再学一遍，就当是提升代码能力了，总之，从这里开始吧。

课程资源来源于Youtube->[Stanford CS193P.](https://www.youtube.com/@StanfordCS193p)。

## lecture 1 and 2 main points

~~~swift
struct ContentView: View {
    # ContentView 是结构名，冒号后的View是类型。
    var body: some View { 
        # “some View”代表返回的是一种TupleView，ViewBuilder。
        # 这里的Var定义的是结构，不是函数，所以不需要return。也可以用Var定义parameters，用let定义不变常量。
        Text("Hello, world!")
            .padding()      # 填充
    }
}
~~~

在这里，**Some View**中的部分主要有以下几个内容
1. Creating Instances of Structs.
2. Named Parameters.
3. Parameter Defualts.
