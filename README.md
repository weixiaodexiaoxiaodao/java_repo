# maven-repo

> 小刀java公开maven-repo  有两个分支 snapshot 和 release
>

## 引用方法

在pom.xml中添加

```xml
    <repositories>
        <repository>
            <id>ideaShare-maven-snapshot-repository</id>
            <name>ideaShare-maven-snapshot-repository</name>
            <url>https://raw.github.com/ideaShareTech/maven-repo/snapshot/</url>
        </repository>
        <repository>
            <id>ideaShare-maven-release-repository</id>
            <name>ideaShare-maven-release-repository</name>
            <url>https://raw.github.com/ideaShareTech/maven-repo/release/</url>
        </repository>
    </repositories>
```



## 现有的包

### common-utils

```xml
        <dependency>
            <groupId>tech.ideashare</groupId>
            <artifactId>utils-base</artifactId>
            <version>0.0.1-RELEASE</version>
        </dependency>
```

`一些常用的工具`

- httputils
