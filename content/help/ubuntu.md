---
title: "Ubuntu"
date: 2017-11-08T20:00:00+08:00
---

## 收录版本
* precise
* trusty
* vivid
* wily
* xenial
* yakkety
* zesty

## 使用方法

修改配置文件`/etc/apt/sources.list`,将系统自带的该文件做个备份，将该文件替换为下面内容

示例：

### Ubuntu 16.04 xenial

```
# 默认注释了源码镜像以提高 apt update 速度，如有需要可自行取消注释
deb https://mirrors.tongji.edu.cn/ubuntu/ xenial main restricted universe multiverse
# deb-src https://mirrors.tongji.edu.cn/ubuntu/ xenial main restricted universe multiverse
deb https://mirrors.tongji.edu.cn/ubuntu/ xenial-updates main restricted universe multiverse
# deb-src https://mirrors.tongji.edu.cn/ubuntu/ xenial-updates main restricted universe multiverse
deb https://mirrors.tongji.edu.cn/ubuntu/ xenial-backports main restricted universe multiverse
# deb-src https://mirrors.tongji.edu.cn/ubuntu/ xenial-backports main restricted universe multiverse
deb https://mirrors.tongji.edu.cn/ubuntu/ xenial-security main restricted universe multiverse
# deb-src https://mirrors.tongji.edu.cn/ubuntu/ xenial-security main restricted universe multiverse

# 预发布软件源，不建议启用
# deb https://mirrors.tongji.edu.cn/ubuntu/ xenial-proposed main restricted universe multiverse
# deb-src https://mirrors.tongji.edu.cn/ubuntu/ xenial-proposed main restricted universe multiverse
```

### precise:
```
deb https://mirrors.tongji.edu.cn/ubuntu/ precise main restricted universe multiverse
deb-src https://mirrors.tongji.edu.cn/ubuntu/ precise main restricted universe multiverse

deb https://mirrors.tongji.edu.cn/ubuntu/ precise-security main restricted universe multiverse
deb-src https://mirrors.tongji.edu.cn/ubuntu/ precise-security main restricted universe multiverse

deb https://mirrors.tongji.edu.cn/ubuntu/ precise-updates main restricted universe multiverse
deb-src https://mirrors.tongji.edu.cn/ubuntu/ precise-updates main restricted universe multiverse

deb https://mirrors.tongji.edu.cn/ubuntu/ precise-backports main restricted universe multiverse
deb-src https://mirrors.tongji.edu.cn/ubuntu/ precise-backports main restricted universe multiverse

## Not recommended
# deb https://mirrors.tongji.edu.cn/ubuntu/ precise-proposed main restricted universe multiverse
# deb-src https://mirrors.tongji.edu.cn/ubuntu/ precise-proposed main restricted universe multiverse
```

### trusty:
```
deb https://mirrors.tongji.edu.cn/ubuntu/ trusty main restricted universe multiverse
deb-src https://mirrors.tongji.edu.cn/ubuntu/ trusty main restricted universe multiverse

deb https://mirrors.tongji.edu.cn/ubuntu/ trusty-security main restricted universe multiverse
deb-src https://mirrors.tongji.edu.cn/ubuntu/ trusty-security main restricted universe multiverse

deb https://mirrors.tongji.edu.cn/ubuntu/ trusty-updates main restricted universe multiverse
deb-src https://mirrors.tongji.edu.cn/ubuntu/ trusty-updates main restricted universe multiverse

deb https://mirrors.tongji.edu.cn/ubuntu/ trusty-backports main restricted universe multiverse
deb-src https://mirrors.tongji.edu.cn/ubuntu/ trusty-backports main restricted universe multiverse

## Not recommended
# deb https://mirrors.tongji.edu.cn/ubuntu/ trusty-proposed main restricted universe multiverse
# deb-src https://mirrors.tongji.edu.cn/ubuntu/ trusty-proposed main restricted universe multiverse
```


