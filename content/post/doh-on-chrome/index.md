---
title: chrome打开doh
description: 不用代理打开神秘同人小网站
slug: doh-on-chrome
date: 2026-05-26
image:
license:
comments: false
categories:
  - 技术
  - 生活小妙招
tags:
---
原理：
在使用DoH的情况下 你能拿到不被污染的dns查询结果 如果对面网站使用了ech的话 你发送TLS请求中的ClientHello字段将被加密 导致防火墙看不到你访问的真实地址 这样就无法阻断你的访问请求
但是如果对面的ip被阻断了的话 那这种方法也无能为力 只适用于一小部分网站

如何配置：
Chrome浏览器：
chrome://settings/security
下拉找到使用安全dns
添加dns供应商 填入doh地址即可

Edge浏览器：
edge://settings/privacy/security
下拉找到使用安全dns 调整为custom并且填入地址

Firefox浏览器：
about:preferences#privacy
下拉很多找到dns over https
选择Increased Protection
提供商下拉找到custom 填入地址即可


