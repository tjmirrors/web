---
title: "Maven Central"
date: 2017-11-12T20:31:49+08:00
---

## 上游仓库

[https://repo.maven.apache.org/maven2/](https://repo.maven.apache.org/maven2/)

## 使用方法

在用户目录下的`.m2`文件夹中创建`settings.xml`配置文件。具体配置文件路径如下：

- Windows：`%HOMEPATH%\.m2\settings.xml`
- Linux或macOS：`$HOME/.m2/settings.xml`

在`settings.xml`中增加`mirror`配置，示例配置如下：

```
<settings>
  <mirrors>
    <mirror>
      <id>Tongji</id>
      <name>Tongji Maven Central Cache</name>
      <url>https://mirrors.tongji.edu.cn/nexus/repository/maven-central/</url>
      <mirrorOf>central</mirrorOf>
    </mirror>
  </mirrors>
</settings>
```

## 相关链接

- [https://maven.apache.org/guides/mini/guide-mirror-settings.html](https://maven.apache.org/guides/mini/guide-mirror-settings.html)
- [https://help.sonatype.com/display/NXRM3/Maven+Repositories](https://help.sonatype.com/display/NXRM3/Maven+Repositories)
