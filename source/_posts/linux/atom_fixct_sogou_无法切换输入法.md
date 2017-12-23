---
title: atmo_fixct_sogou_无法切换输入法
date: 2017-12-21 11:05:23
categories: Linux
tags:
- Linux
---

https://github.com/atom/atom/issues/5447

@yuyichao I found that the environment variables were wrong. I edited ~/.xprofile as below and it worked.

export GTK_IM_MODULE=fcitx
thanks a lot @yuyichao @xfq @yuyichao @wengxt @defunkt

后记：

我尝试了很多网上的方法，对我来说都不行。后来自己发现了一个方法，就是在atom多打开一个文档。当你无法切换输入法的时候，切换到另一个文档，再切回来，就好了。
