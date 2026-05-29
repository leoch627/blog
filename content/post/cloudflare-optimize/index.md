---
title: cloudflare优选教程
description: 绷不住了自己看了好几个教程没看懂 自己写一个备用
slug: cloudflare-optimize
date: 2026-04-27
image:
license:
comments: false
categories:
  - 建站
tags:
---

需要准备的：
1.一个cloudflare账号 需要绑卡开saas
2.两个域名 a.com b.com

最终呈现：a.com

首先，到b.com SSL/TLS设置 Custom Hostnames 设置一个fallback origin 弄到你真正的源上面

接下来，在b.com的Custom Hostnames加上你的a.com，并且到a.com添加一堆记录
