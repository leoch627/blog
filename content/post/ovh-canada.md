---
title: OVH加拿大独服测评
description: 8t hdd 64g 内存
slug: ovh-canada
date: 2025-11-24T16:26:17+08:00
---

```
测评频道: https://t.me/+UHVoo2U4VyA5NTQ1                    
VPS融合怪版本：2025.11.09
Shell项目地址：https://github.com/spiritLHLS/ecs
Go项目地址 [推荐]：https://github.com/oneclickvirt/ecs
---------------------基础信息查询--感谢所有开源项目----------------------
 CPU 型号          : Intel(R) Xeon(R) CPU E5-1630 v4 @ 3.70GHz
 CPU 核心数        : 1 物理核心, 4 总核心, 8 总线程数
 CPU 频率          : 2600.233 MHz
 CPU 缓存          : L1: 128.00 KB / L2: 1.00 MB / L3: 10.00 MB
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ✔ Enabled
 内存              : 2.72 GiB / 62.69 GiB
 Swap              : 1.65 GiB / 2.00 GiB
 硬盘空间          : 205.11 GiB / 7.21 TiB
 启动盘路径        : /dev/md3
 系统在线时间      : 6 days, 5 hour 49 min
 负载              : 0.83, 0.41, 0.55
 系统              : Debian GNU/Linux 13 (trixie) (x86_64)
 架构              : x86_64 (64 Bit)
 内核              : 6.12.48+deb13-amd64
 TCP加速方式       : cubic
 虚拟化架构        : Dedicated
 IPV4 ASN          : AS16276 OVH SAS
 IPV4 位置         : Montréal / Quebec / CA
 IPV6 ASN          : AS16276 OVH SAS
 IPV6 位置         : Canada
 IPV6 子网掩码     : 128
------------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分: 		1261 Scores
 8 线程测试(多核)得分: 		7761 Scores
--------------------内存测试--感谢lemonbench开源----------------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:		26173.39 MB/s
 单线程写测试:		20263.69 MB/s
--------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作		写速度					读速度
 100MB-4K Block		69.3 MB/s (16.91 IOPS, 1.51s)		104 MB/s (25304 IOPS, 1.01s)
 1GB-1M Block		597 MB/s (569 IOPS, 1.76s)		407 MB/s (388 IOPS, 2.58s)
----------------------磁盘fio读写测试--感谢yabs开源-----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 3.47 MB/s      (868) | 50.47 MB/s     (788)
Write      | 3.50 MB/s      (876) | 50.78 MB/s     (793)
Total      | 6.97 MB/s     (1.7k) | 101.26 MB/s   (1.5k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 149.02 MB/s    (291) | 163.47 MB/s    (159)
Write      | 156.94 MB/s    (306) | 174.36 MB/s    (170)
Total      | 305.97 MB/s    (597) | 337.84 MB/s    (329)
正在并发测试中，大概2~3分钟无输出，请耐心等待。。。
---------------流媒体解锁--感谢oneclickvirt/UnlockTests测试----------------
测试时间:  2025-11-24 14:43:34
IPV4:
============[ 跨国平台 ]============
Apple                     YES (Region: CAN) [Native]
BingSearch                YES (Region: CA)
Claude                    YES [Native]
Dazn                      Banned
Disney+                   NO (forbidden-location)
Gemini                    YES (Region: CA) [Native]
GoogleSearch              YES
Google Play Store         YES (Region: CA) [Native]
IQiYi                     YES (Region: CA) [Native]
Instagram Licensed Audio  YES [Native]
KOCOWA                    YES [Native]
MetaAI                    NO (GeoBlocked)
Netflix                   NO
Netflix CDN               NO (Main Service Unavailable) (Region: US)
OneTrust                  YES (Region: CA QUEBEC) [Via DNS]
ChatGPT                   YES (Region: CA) [Native]
Paramount+                YES [Native]
Amazon Prime Video        YES (Region: CA) [Native]
Reddit                    NO
SonyLiv                   YES (Region: CA) [Native]
Sora                      YES (Region: CA)
Spotify Registration      YES (Region: CA) [Native]
Steam Store               YES (Community Available) (Region: CA)
TVBAnywhere+              YES (Region: CA) [Native]
TikTok                    YES (Region: CA) [Native]
Viu.com                   YES [Native]
Wikipedia Editability     YES
YouTube Region            YES (Region: CA) [Native]
YouTube CDN               IAD
IPV6:
============[ 跨国平台 ]============
Apple                     YES (Region: CAN) [Native]
BingSearch                YES (Region: CA)
Claude                    YES [Native]
Dazn                      N/A (No IPv6 Support)
Disney+                   NO (forbidden-location)
Gemini                    YES (Region: CA) [Native]
GoogleSearch              YES
Google Play Store         YES (Region: CA) [Native]
IQiYi                     N/A (No IPv6 Support)
Instagram Licensed Audio  YES [Native]
KOCOWA                    N/A (No IPv6 Support)
MetaAI                    NO (GeoBlocked)
Netflix                   NO
Netflix CDN               NO (Main Service Unavailable) (Region: US)
OneTrust                  YES (Region: CA QUEBEC) [Via DNS]
ChatGPT                   Unknown
Paramount+                YES [Native]
Amazon Prime Video        N/A (No IPv6 Support)
Reddit                    Failed (Network Connection Failed)
SonyLiv                   YES (Region: CA) [Native]
Sora                      YES (Region: CA)
Spotify Registration      YES (Region: CA) [Native]
Steam Store               Failed (Network Connection Failed)
TVBAnywhere+              N/A (No IPv6 Support)
TikTok                    N/A (No IPv6 Support)
Viu.com                   N/A (No IPv6 Support)
Wikipedia Editability     YES
YouTube Region            YES (Region: CA) [Native]
YouTube CDN               IAD
---------------------TikTok解锁--感谢lmc999的源脚本---------------------
 Tiktok Region:		【CA】
-------------IP质量检测--基于oneclickvirt/securityCheck使用--------------
数据仅作参考，不代表100%准确，如果和实际情况不一致请手动查询多个数据库比对
以下为各数据库编号，输出结果后将自带数据库来源对应的编号
ipinfo数据库  [0] | scamalytics数据库 [1] | virustotal数据库   [2] | abuseipdb数据库   [3] | ip2location数据库    [4]
ip-api数据库  [5] | ipwhois数据库     [6] | ipregistry数据库   [7] | ipdata数据库      [8] | db-ip数据库          [9]
ipapiis数据库 [A] | ipapicom数据库    [B] | bigdatacloud数据库 [C] | dkly数据库        [D] | ipqualityscore数据库 [E]
ipintel数据库 [F] | ipfighter数据库   [G] | fraudlogix数据库   [H] | cloudflare数据库  [I] |
IPV4:
安全得分:
信任得分(越高越好): 25 [8] 
VPN得分(越低越好): 26 [8] 
代理得分(越低越好): 100 [8]
社区投票-无害: 0 [2] 
社区投票-恶意: 0 [2] 
威胁得分(越低越好): 100 [8] 
欺诈得分(越低越好): 65 [E] 
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0044 (Low) [A] 
公司滥用得分(越低越好): 0 (Very Low) [A] 
威胁级别: low [9]
流量占比: 真人(越高越好)17% [I] 机器人(越低越好)82% [I]
黑名单记录统计:(有多少黑名单网站有记录):
无害记录数: 0 [2]  恶意记录数: 0 [2]  可疑记录数: 0 [2]  无记录数: 95 [2] 
安全信息:
使用类型: hosting [0 3 7 9 A C] business [8]
公司类型: hosting [0 7 A] 
浏览器类型: 主流53% 其他46% [I] 
设备类型: 桌面80% 移动19% 其他0% [I] 
操作系统类型: 主流92% 其他7% [I] 
是否云提供商: Yes [7] 
是否数据中心: Yes [0 5 A C G] No [6 8]
是否移动设备: Yes [E] No [5 A C G]
是否代理: Yes [E G] No [0 4 5 6 7 8 9 A C]
是否VPN: Yes [E G] No [0 6 7 A C]
是否Tor: No [0 3 6 7 8 A C E] 
是否Tor出口: No [7] 
是否网络爬虫: No [9 A E] 
是否匿名: No [6 7 8] 
是否攻击者: No [7 8] 
是否滥用者: No [7 8 A C E] 
是否威胁: No [7 8 C] 
是否中继: No [0 7 8 C] 
是否Bogon: No [7 8 A C] 
是否机器人: No [E] 
DNS-黑名单: 314(Total_Check) 0(Clean) 0(Blacklisted) 0(Other) 
IPV6:
安全得分:
滥用得分(越低越好): 0 [3] 
ASN滥用得分(越低越好): 0.0044 (Low) [A]
公司滥用得分(越低越好): 0 (Very Low) [A] 
流量占比: 真人(越高越好)17% [I] 机器人(越低越好)82% [I]
安全信息:
使用类型: hosting [3 A] 
公司类型: hosting [A] 
浏览器类型: 主流53% 其他46% [I] 
设备类型: 桌面80% 移动19% 其他0% [I] 
操作系统类型: 主流92% 其他7% [I] 
是否数据中心: Yes [A G] 
是否移动设备: No [A G] 
是否代理: No [A] Yes [G]
是否VPN: No [A] Yes [G]
是否Tor: No [3 A] 
是否网络爬虫: No [A] 
是否滥用者: No [A] 
是否Bogon: No [A] 
DNS-黑名单: 314(Total_Check) 0(Clean) 0(Blacklisted) 314(Other) 
Google搜索可行性：NO
------------邮件端口检测--基于oneclickvirt/portchecker开源------------
Platform  SMTP  SMTPS POP3  POP3S IMAP  IMAPS
LocalPort ✘     ✔     ✔     ✔     ✔     ✔    
QQ        ✔     ✔     ✔     ✘     ✔     ✘    
163       ✔     ✔     ✔     ✘     ✔     ✘    
Sohu      ✔     ✔     ✘     ✘     ✔     ✘    
Yandex    ✔     ✔     ✔     ✘     ✔     ✘    
Gmail     ✔     ✔     ✘     ✘     ✘     ✘    
Outlook   ✔     ✘     ✔     ✘     ✔     ✘    
Office365 ✔     ✘     ✔     ✘     ✔     ✘    
Yahoo     ✔     ✔     ✘     ✘     ✘     ✘    
MailCOM   ✔     ✔     ✔     ✘     ✔     ✘    
MailRU    ✔     ✔     ✘     ✘     ✔     ✘    
AOL       ✔     ✔     ✘     ✘     ✘     ✘    
GMX       ✔     ✔     ✔     ✘     ✔     ✘    
Sina      ✔     ✘     ✔     ✘     ✔     ✘    
Apple     ✘     ✔     ✘     ✘     ✘     ✘    
FastMail  ✘     ✔     ✘     ✘     ✘     ✘    
ProtonMail✘     ✘     ✘     ✘     ✘     ✘    
MXRoute   ✔     ✘     ✔     ✘     ✔     ✘    
Namecrane ✔     ✔     ✔     ✘     ✔     ✘    
XYAMail   ✘     ✘     ✘     ✘     ✘     ✘    
ZohoMail  ✘     ✔     ✘     ✘     ✘     ✘    
Inbox_eu  ✔     ✔     ✔     ✘     ✘     ✘    
Free_fr   ✘     ✔     ✔     ✘     ✔     ✘    
-------------上游及三网回程--基于oneclickvirt/backtrace开源--------------
国家: CA 城市: Montréal 服务商: AS16276 OVH SAS
北京电信v4 219.141.140.10           电信163    [普通线路] 
北京联通v4 202.106.195.68  检测不到回程路由节点的IPV4地址
北京移动v4 221.179.155.161          移动CMI    [普通线路] 
上海电信v4 202.96.209.133           电信163    [普通线路] 
上海联通v4 210.22.97.1              联通4837   [普通线路] 
上海移动v4 211.136.112.200          移动CMI    [普通线路] 
广州电信v4 58.60.188.222            电信163    [普通线路] 
广州联通v4 210.21.196.6    检测不到回程路由节点的IPV4地址
广州移动v4 120.196.165.24           移动CMI    [普通线路] 
成都电信v4 61.139.2.69              电信163    [普通线路] 
成都联通v4 119.6.6.6       检测不到回程路由节点的IPV4地址
成都移动v4 211.137.96.205           移动CMI    [普通线路] 移动CMIN2  [精品线路] 
北京电信v6 2400:89c0:1053:3::69     检测不到回程路由节点的IPV6地址
北京联通v6 2400:89c0:1013:3::54     检测不到回程路由节点的IPV6地址
北京移动v6 2409:8c00:8421:1303::55  检测不到回程路由节点的IPV6地址
上海电信v6 240e:e1:aa00:4000::24    检测不到回程路由节点的IPV6地址
上海联通v6 2408:80f1:21:5003::a     移动CMI    [普通线路] 
上海移动v6 2409:8c1e:75b0:3003::26  检测不到回程路由节点的IPV6地址
广州电信v6 240e:97c:2f:3000::44     电信163    [普通线路] 
广州联通v6 2408:8756:f50:1001::c    移动CMI    [普通线路] 
广州移动v6 2409:8c54:871:1001::12   检测不到回程路由节点的IPV6地址
准确线路自行查看详细路由，本测试结果仅作参考
同一目标地址多个线路时，检测可能已越过汇聚层，除第一个线路外，后续信息可能无效
----------------------回程路由--基于nexttrace开源-----------------------
依次测试电信/联通/移动经过的地区及线路，核心程序来自nexttrace，请知悉!
广州电信 58.60.188.222
1.22 ms 	AS16276 [OVH-ARIN] 加拿大 魁北克省 博阿努瓦 ovhcloud.com
0.66 ms 	* RFC1918
0.18 ms 	* RFC1918
1.20 ms 	* RFC1918
10.61 ms 	AS16276 [OVH-ARIN] 美国 纽约 纽约 ovhcloud.com
11.25 ms 	AS16276 [OVH-ARIN] 美国 纽约 纽约 ovhcloud.com
84.45 ms 	AS16276 [OVH-ARIN] 英国 英格兰 伦敦 ovhcloud.com
89.81 ms 	AS16276 [OVH] 英国 英格兰 伦敦 ovhcloud.com
93.12 ms 	AS16276 德国 黑森 美因河畔法兰克福 ovhcloud.com
102.11 ms 	* RFC1918
285.30 ms 	AS4134 [CHINANET-BB] 中国 香港 chinatelecom.com.cn
404.36 ms 	AS4134 [CHINANET-BB] 中国 广东 广州 chinatelecom.com.cn 电信
广州联通 210.21.196.6
0.65 ms 	AS16276 [OVH-ARIN] 加拿大 魁北克省 博阿努瓦 ovhcloud.com
0.81 ms 	* RFC1918
10.92 ms 	* RFC1918
21.43 ms 	* RFC1918
54.53 ms 	AS16276 [HO-2] 加拿大 魁北克 蒙特利尔 ovhcloud.com
22.78 ms 	* RFC1918
1.62 ms 	AS1299 [ARELION-NET] 加拿大 魁北克 蒙特利尔 arelion.com
5.02 ms 	AS1299 [ARELION-NET] 加拿大 魁北克 蒙特利尔 arelion.com
8.46 ms 	AS1299 [ARELION-NET] 美国 纽约 纽约 arelion.com
21.82 ms 	AS1299 [ARELION-NET] 瑞典 斯德哥尔摩省 斯德哥尔摩 arelion.com
85.64 ms 	AS1299 [ARELION-NET] 美国 佐治亚 亚历山大 arelion.com
127.53 ms 	AS1299 [ARELION-NET] 美国 佐治亚州 亚特兰大 arelion.com
127.60 ms 	AS1299 [ARELION-NET] 美国 德克萨斯 达拉斯 arelion.com
134.14 ms 	AS1299 [ARELION-NET] 美国 加利福尼亚 洛杉矶 arelion.com
73.76 ms 	AS1299 [ARELION-NET] 美国 加利福尼亚 洛杉矶 arelion.com
227.41 ms 	AS1299 美国 加利福尼亚 洛杉矶 arelion.com
227.81 ms 	AS4837 [CU169-BACKBONE] 中国 北京 chinaunicom.cn 联通
297.39 ms 	AS4837 [CU169-BACKBONE] 中国 北京 chinaunicom.cn 联通
319.56 ms 	AS17623 [APNIC-AP] 中国 广东 深圳 chinaunicom.cn 联通
285.10 ms 	AS17623 中国 广东 深圳 宝安区 chinaunicom.cn 联通
广州移动 120.196.165.24
0.75 ms 	AS16276 [OVH-ARIN] 加拿大 魁北克省 博阿努瓦 ovhcloud.com
0.56 ms 	* RFC1918
0.20 ms 	* RFC1918
77.62 ms 	* RFC1918
17.08 ms 	AS16276 [OVH-ARIN] 美国 伊利诺伊 芝加哥 ovhcloud.com
65.99 ms 	AS16276 [OVH-ARIN] 美国 加利福尼亚 圣何塞 ovhcloud.com
64.68 ms 	* RFC1918
63.87 ms 	AS58453 [CMI-INT] 美国 加利福尼亚 圣何塞 cmi.chinamobile.com 移动
223.07 ms 	AS58453 [CMI-INT] 中国 广东 广州 cmi.chinamobile.com 移动
222.85 ms 	AS9808 [CMNET] 中国 广东 广州 X-I chinamobileltd.com 移动
222.59 ms 	AS9808 [CMNET] 中国 广东 广州 I-C chinamobileltd.com 移动
259.21 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
267.46 ms 	AS9808 [CMNET] 中国 广东 广州 chinamobileltd.com 移动
260.66 ms 	AS56040 [APNIC-AP] 中国 广东 深圳 gd.10086.cn 移动
---------------------自动更新测速节点列表--本脚本原创----------------------
位置		 上传速度	 下载速度	 延迟
Speedtest.net	 457.67Mbps	 919.65Mbps	 7.82ms	
洛杉矶		 418.24Mbps	 568.90Mbps	 76.09ms	
法兰克福	 453.15Mbps	 798.08Mbps	 95.09ms	
联通上海5G	 0.36Mbps	 0.01Mbps	 577.66ms	
电信Suzhou5G	 231.81Mbps	 414.59Mbps	 260.46ms	
电信浙江	 0.80Mbps	 284.76Mbps	 284.66ms	
移动Suzhou	 0.61Mbps	 0.48Mbps	 1.67ms	
------------------------------------------------------------------------
 总共花费      : 5 分 8 秒
 时间          : Mon Nov 24 14:45:43 UTC 2025
------------------------------------------------------------------------
```