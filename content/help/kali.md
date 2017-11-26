---
title: "Kali Linux"
date: 2017-11-26T14:13:48+08:00
---

## 上游仓库

[rsync://ftp.nluug.nl/kali/](rsync://ftp.nluug.nl/kali/)

## 使用方法

编辑`/etc/apt/sources.list`文件，添加以下配置：

```
deb https://mirrors.tongji.edu.cn/kali kali-rolling main non-free contrib
deb-src https://mirrors.tongji.edu.cn/kali kali-rolling main non-free contrib
```

更新软件库索引

```
$ sudo apt-get update
```
