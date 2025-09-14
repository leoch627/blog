---
title: Hugo+Stack主题在本机的部署
description: Welcome to Hugo Theme Stack
slug: hugo-deployment
date: 2024-12-20T16:26:17+08:00
image: hugo-deployment.jpg
categories:
  - 技术
tags:
  - Hugo
---


前言：
最近看到了一堆年终总结，看到了一个十分漂亮的Hugo+Stack主题配置。加上最近感觉十分没有任何一点技术上的涨进，且感受到了我们班同学的技术水平后，决定开始写一些博客来提高平均的一个技术水平。


[Hugo](https://github.com/gohugoio/hugo "Hugo")是一个方便，快捷，好管理的基于markdown的静态博客系统。blah,blah,blah 
Anyway, 我最终还是使用了这个博客系统。

## 安装（Windows Only）

折腾了半天hugo 各种版本的release后，我还是选择了最简单的安装方式：通过chocolatey 

1.安装chocolatey

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

2.通过chocolatey 安装 hugo-extended

```
choco install hugo-extended
```

3.安装[Git for Windows](https://git-scm.com/downloads)


## 部署

1.初始化环境
新建一个空文件夹，cmd cd至文件夹内

2.使用Git Bash 克隆主题+Hugo环境到文件夹内
```bash
git clone https://github.com/CaiJimmy/hugo-theme-stack-starter .
```

3.使用Hugo搭建本地服务器
```
hugo server -D
```

4.打开浏览器看看效果
[https://localhost:1313](https://localhost:1313)


