---
title: Acme.sh使用cloudflare api和letsencrypt申请通配符证书
description: 老是忘，记一下
slug: acme-sh-cloudflare-api
date: 2025-03-19
image: 
categories:
  - 技术
tags: 
weight: 1
---
1.安装acme.sh
```
curl get.acme.sh | bash
source ~/.bashrc
acme.sh --set-default-ca --server letsencrypt
```

2.申请cloudflare api并导入
```
export CF_Token=""
```

3.申请证书
```
acme.sh --issue --dns dns_cf -d *.leochang.eu.org -d leochang.eu.org
```

