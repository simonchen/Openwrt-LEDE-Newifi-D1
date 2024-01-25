基于Openwrt/LEDE编译的 Newifi D1 固件

# Feeds
Uses the local packages/helloword forked from (https://github.com/coolsnowwolf/packages) (https://github.com/fw876/helloworld.git)

# Fix issues

```
luci-app-ssr-plus (Fix the rule with gfw mode / restarting without killing kcptun)
luci-app-kcptun (Brackets with $server variable for support IPv6 address)
luci-app-udp2raw (Brackets with ${listen_addr} / ${server_addr} variables for support IPv6 address)
udp2raw (Makefile downgrades to stable version of 0.45.0)
kcptun (Makefile downgrades to stable version 20210922)
```

# What's New
```
系统
Diskman,文件传输

服务
SSR plus+, Adblock,全能推送,动态DDNS, QOS Nftables, 网络唤醒, KMS服务器, uPnP, OpenVPN, , NWAN3w分流助手

管控
上网时间控制, 访问控制, 网址过滤, 定时唤醒

网络存储
Samba网络共享,FTP服务器

网络
Socat, turbo ACC 网络加速, 多线多拨, NWAN3负载均衡

更多网络插件
SmartDNS | iPerf3 |

集成驱动
USB-RNDIS 驱动 | [Rtw88-usb 无线网卡驱动](https://github.com/ulli-kroll/rtw88-usb)
