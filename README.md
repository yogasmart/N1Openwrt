![N1](https://github.com/mingxiaoyu/N1Openwrt/workflows/N1/badge.svg)

[N1Openwrt](https://github.com/mingxiaoyu/N1Openwrt)和[N1imagebuilder](https://github.com/mingxiaoyu/N1imagebuilder)是关联项目。
N1Openwrt仅仅编译为OpenWrt，不能直接为N1所用。必须通过N1imagebuilder打包成img

# mini版和plus（高大全）的处理方式，学习的了要求不高，请请请在感谢列表里加上我的名字。

自用 Phicomm N1 Openwrt，默认旁路油
默认自定义防火墙: iptables -t nat -I POSTROUTING -o eth0 -j MASQUERADE

每三天自动编译一次。

# 如何使用
1. fork项目
2. 在secrets中创建RELEASES_TOKEN，一般一次编译要2~4小时，所以要创建一个github发布用的token。
3. 点击Actions -> Workflows -> Run workflow -> Run workflow
4. 编译多版本，可以直接用。
5. 如果只编译单个，可以复制single.yml到.github/workflows 然后简单修改。

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
 * zerotier
 * flowoffload
 * WIFI
 
 ![applist](https://github.com/mingxiaoyu/N1Openwrt/blob/master/imgs/mini.jpg?raw=true)
------
 # 感激 
 [P3TERX](https://github.com/P3TERX/Actions-OpenWrt)提供的脚本参考
 
 ## 云编译的规格
https://docs.github.com/en/actions/reference/virtual-environments-for-github-hosted-runners#supported-runners-and-hardware-resources

