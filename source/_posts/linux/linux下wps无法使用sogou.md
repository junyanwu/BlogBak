---
title: 解决WPS下搜狗输入法不能输入中文
date: 2017-12-21 11:05:23
categories: Linux
tags:
- Linux
---

问题：WPS下搜狗输入法不能输入中文

原因：环境变量未正确设置

```bash
$ vi /usr/bin/wps
在第一行 #!/bin/bash 下添加：
export XMODIFIERS="@im=fcitx"
export QT_IM_MODULE="fcitx"
```

(2）ppt、excel部分

和word一样的方法添加环境变量，只是编辑的文件各不同：

```bash
$ vi /usr/bin/wpp
$ vi /usr/bin/et
```
