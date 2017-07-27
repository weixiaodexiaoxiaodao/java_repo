# maven-repo

> 纷享科技公开maven-repo  有两个分支 snapshot 和 release  
>
> QQ交流群：661749608

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
            <artifactId>common-utils</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>
```



`一些常用的工具`

- httputils 
