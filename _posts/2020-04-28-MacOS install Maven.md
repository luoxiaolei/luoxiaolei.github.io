---
layout: post
title: MacOS install Maven
categories: [Install]
excerpt: 
---

# 步骤
1. 下载安装包
```
http://mirror.bit.edu.cn/apache/maven/maven-3/3.6.1/binaries/apache-maven-3.6.1-bin.tar.gz
```

2. 解压
```
tar xzvf apache-maven-3.6.1-bin.tar.gz
```

3. 检查JAVA环境变量
```
echo $JAVA_HOME
/Library/Java/JavaVirtualMachines/jdk1.8.0_45.jdk/Contents/Home
```

4. 将bin目录加入PATH
```
export PATH=/opt/apache-maven-3.6.1/bin:$PATH
```

# 常用命令
```
debug模式执行install
mvn install -X 
```


# 参考链接
- [Installing Apache Maven](https://maven.apache.org/install.html)
- [Mac OS X下安装和配置Maven](https://www.cnblogs.com/vitasyuan/p/7395601.html)