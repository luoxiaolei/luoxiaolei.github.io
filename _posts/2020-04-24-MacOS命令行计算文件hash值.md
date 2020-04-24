---
layout: post
title: MacOS命令行计算文件hash值
categories: [Terminal]
excerpt: 
---

### MD5
```
openssl dgst -md5 123.bin
or
openssl md5 123.bin
or
md5 123.bin
or
md5 -s "text"
```

### SHA1
```
openssl dgst -sha1 123.bin
or
openssl sha1 123.bin
```

### HmacMD5
```
openssl md5 -hmac "replace_hmac_key_string_here" 123.bin

```

### sha256
```
openssl sha256 filename
```

### 参考链接
[MacOS 命令行计算文件的 MD5/HmacMD5/SHA1/SHA256](https://blog.csdn.net/toopoo/article/details/99657602)