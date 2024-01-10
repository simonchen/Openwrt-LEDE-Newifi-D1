基于Openwrt/LEDE编译的 Newifi D1 固件

# Fix

/usr/bin/ssr-rules

找到 "ipset_r() > gfw)" 添加:
$IPT -A SS_SPEC_WAN_AC -j SS_SPEC_WAN_FW
意思是不在gfwlist 、chinalist的都用SS redir
