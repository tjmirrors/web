---
title: "Maven Central"
date: 2017-11-12T20:31:49+08:00
---

## 上游仓库

[https://repo.maven.apache.org/maven2/](https://repo.maven.apache.org/maven2/)

## 使用方法

修改配置文件`${user.home}/.m2/settings.xml`，增加`mirror`配置

```
<settings>
  ...
  <mirrors>
    <mirror>
      <id>Tongji</id>
      <name>Tongji Maven Central Cache</name>
      <url>https://mirrors.tongji.edu.cn/nexus/repository/maven-central/</url>
      <mirrorOf>central</mirrorOf>
    </mirror>
  </mirrors>
  ...
</settings>
```

## 相关链接

- [https://maven.apache.org/guides/mini/guide-mirror-settings.html](https://maven.apache.org/guides/mini/guide-mirror-settings.html)
- [https://help.sonatype.com/display/NXRM3/Maven+Repositories](https://help.sonatype.com/display/NXRM3/Maven+Repositories)
