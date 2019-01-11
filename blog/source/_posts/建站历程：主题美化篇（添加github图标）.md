---
title: 建站历程：主题美化篇（添加github图标）
date: 2019-01-11 20:45:47
tags:
- Hexo
- Next
categories:
- 建站历程
---

在网站右上角添加github图标一共有两种不同的样式，见下图：

![avatar](https://github.com/SwayYe/Img/raw/master/blog/fork%20me%20on%20github.png)

# 挑选自己喜欢的图标

你可以从[这里](http://tholman.com/github-corners/#)挑选图片样式的图标或者从[这里](https://blog.github.com/2008-12-19-github-ribbons/)挑选文字样式的图标。挑选完之后，复制对应的代码。

# 添加到_layout.swig

打开文件`themes/next/layout/_layout.swig`，找到`<div class="headband"></div>`那一行，把之前复制的代码黏贴进去，同时把`href="https://your-url"`中的网址改成自己的github网址，部署后即可看到效果。