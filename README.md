![N1](https://github.com/mingxiaoyu/N1Openwrt/workflows/N1/badge.svg)

自用 Phicomm N1 Openwrt，默认旁路油

默认自定义防火墙: iptables -t nat -I POSTROUTING -o eth0 -j MASQUERADE

# 如何使用
1. fork项目
2. 在secrets中创建RELEASES_TOKEN，一般一次编译要2~4小时，所以要创建一个github发布用的token。
3. 点击Actions -> Workflows -> Run workflow -> Run workflow

## 用户名和密码
 * User: root
 * Password: password
 * Default IP: 192.168.32.2


## app list:
 * UU网游加速器
 * jd-dailybonus
 * ssr+
 * ServerChan
 * unblockmusic
 * aria2
 * ddns
 * samba4
 * KMS 
 * frp
 * docker
 * cifs(挂载 SMB/CIFS 网络共享文件夹)
 * vsftpd
 * usb_printer
 * ipsec-server
 * zerotier
 * flowoffload
 
------
 # 感激 
 [P3TERX](https://github.com/P3TERX/Actions-OpenWrt)提供的脚本参考
 
 ## 云编译的规格
https://docs.github.com/en/actions/reference/virtual-environments-for-github-hosted-runners#supported-runners-and-hardware-resources

