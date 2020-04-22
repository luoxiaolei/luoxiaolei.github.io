---
layout: post
title: 2020-04-22-网站接入GoogleAnalytics步骤
categories: [Experience]
excerpt: 
---

1. [注册Google账号](https://accounts.google.com/signup/v2/webcreateaccount?continue=https%3A%2F%2Faccounts.google.com%2F&gmb=exp&biz=false&flowName=GlifWebSignIn&flowEntry=SignUp)
2. 访问[GoogleAnalytics](https://analytics.google.com/analytics/web/?authuser=0)首页，用谷歌账号登录
3. 打开GoogleAnalytics首页，点击左下角[管理]
4. 创建GoogleAnalytics账号，点击[创建账号]
5. 添加媒体资源（你要监控的网站链接），点击[创建媒体资源]
6. 点击[跟踪信息]-[跟踪代码]查看全局代码
7. 复制全局代码，并将其粘贴到您要跟踪的每个网页的 <HEAD> 标记中。如果网页上已经有全局网站代码，则只需将以下代码段中的 config 行添加到现有的全局网站代码。