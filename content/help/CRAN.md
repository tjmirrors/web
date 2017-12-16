---
title: "CRAN"
date: 2017-12-16T20:00:00+08:00
---

> 本镜像站为CRAN官方安全镜像，通过ssh同步上游仓库，支持HTTPS安全传输。

## 上游仓库

rsync over ssh: `cran-rsync@cran.r-project.org:`

## 镜像地址

[https://mirrors.tongji.edu.cn/CRAN/](https://mirrors.tongji.edu.cn/CRAN/)

## 使用方法

- 在初次执行`install.packages`安装软件包时，可以进入镜像设置界面，选择`China (Shanghai) [https]`镜像即可；
- 已经设置过镜像的话，也可以执行`chooseCRANmirror()`进入镜像设置界面来更换镜像。
