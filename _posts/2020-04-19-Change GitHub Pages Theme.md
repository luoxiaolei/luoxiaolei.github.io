---
layout: post
title: 修改GitHub Pages主题
categories: [Experience]
excerpt: 
---

# 选择主题
1. 从[jekyllthemes](https://jekyllthemes.io/github-pages-themes)中选择喜欢的主题
2. 免费的主题通常都是GitHub的开源项目，访问GitHub项目主页

# 以主题为模板创建自己的Repository
1. 通过点击[Use this template]创建自己的Repository
2. 以[yourgithubname].github.io命名新建的Repository

# 修改通用配置(_config.yml)
1. 修改根目录（==根目录不正确的话会导致样式或图片加载失败==）
```
baseurl: "/"
```
2. 修改博客名称
```
name: yourblogname
```
3. 修改博客描述
```
description: yourblogdesc
```

# 常用目录介绍
1. 页面模板目录
```
_pages包含如下文件
about.md        自我介绍页
categories.md   分类标签页
search.md       搜索页
```
2. 发布的博客目录
```
_posts
yyyy-MM-dd-title.md 博客文件名称样式
```

# 访问博客
```
https://yourgithubname.github.io
```

# Demo
1. 我选择的主题
    - [Reverie](https://jekyllthemes.io/theme/reverie)
2. 我配置完成后的主题
    - [我的博客](https://luoxiaolei.github.io)

# 参考链接
- [jekyllthemes](https://jekyllthemes.io/github-pages-themes)
- [Reverie](https://jekyllthemes.io/theme/reverie)
- [我的博客](https://luoxiaolei.github.io)