---
layout: post
title: Mac install nginx
categories: [Install]
excerpt: 
---

# 安装
```
brew install nginx
```

# 常用命令
启动
```
./nginx
```

退出
```
nginx -s quit
```

测试
```
nginx -t
```

查看nginx是否运行
```
pidof nginx
ps -A | grep nginx
```

# 访问路径
```
http://localhost:8080/
```

# 常用路径

默认安装路径
```
/usr/local/etc/nginx
```

默认页面路径
```
/usr/local/var/www
```