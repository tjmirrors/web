---
title: "NPM"
date: 2017-11-12T21:02:31+08:00
---

## 上游仓库

[https://registry.npm.taobao.org](https://registry.npm.taobao.org)

## 使用方法

使用`npm config`命令，设置配置文件`.npmrc`中`registry`

```
$ npm config set registry https://mirrors.tongji.edu.cn/nexus/repository/npm/
```

上面的命令会在用户目录的`.npmrc`文件中插入以下配置

```
registry=https://mirrors.tongji.edu.cn/nexus/repository/npm/
```

## 相关链接

- [https://help.sonatype.com/display/NXRM3/Node+Packaged+Modules+and+npm+Registries](https://help.sonatype.com/display/NXRM3/Node+Packaged+Modules+and+npm+Registries)
