
N1打包学习测试，请不要使用。

# 如何使用
1. fork项目
2. 在secrets中创建RELEASES_TOKEN，一般一次编译要2~4小时，所以要创建一个github发布用的token。
3. 点击Actions -> Workflows -> Run workflow -> Run workflow 
4. N1 Multiple Version 多版本编译
5. N1 Single Version 只编译一个版本
6. Update Checker, 上游更新则编译。MULTIPLE_BUILD: true **编译mini和plus多版本编译**  false，**只编译mini**

# 感谢
 * [mingxiaoyu](https://github.com/mingxiaoyu/N1Openwrt)
 * [P3TERX](https://github.com/P3TERX/Actions-OpenWrt)提供的脚本参考
