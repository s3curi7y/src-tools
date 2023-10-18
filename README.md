## 项目介绍

**src-tools** 收集与开发一些应急响应相关的工具，工具保证无毒无污染。

项目持续更新！


## dnsquerylist

一款Linux系统下的DNS请求查看工具。

使用方法：
```
chmod +x dnsquerylist
./dnsquerylist -device eth0	//指定网卡
```
输出结果：
```
源IP地址：10.xxx.xxx.143，目标IP地址：114.114.114.114，源端口：37047，目标端口：53，域名：www.baidu.com
源IP地址：10.xxx.xxx.143，目标IP地址：114.114.114.114，源端口：43566，目标端口：53，域名：xxx.xxx.xxx.180.xx-xxx.xxx
源IP地址：10.xxx.xxx.143，目标IP地址：114.114.114.114，源端口：51558，目标端口：53，域名：xxx.xxx.xxx.10.xx-xxx.xxx
```
