---
title: "CRAN"
date: 2017-12-16T20:00:00+08:00
---

> 本镜像站为CRAN官方安全镜像，通过ssh同步上游仓库，支持HTTPS安全传输。

## 上游仓库

rsync over ssh: `cran-rsync@cran.r-project.org:`

## 使用方法

- 在初次执行`install.packages()`时可以设置镜像，选择`China (Shanghai) [https]`镜像即可；
- 已经设置过镜像的话，也可以执行`chooseCRANmirror()`更换镜像。
