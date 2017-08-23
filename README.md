之前介绍过用kcptun来给搬瓦工等openvz架构的vps加速，不过搭建的过程稍微复杂。最近得知koolshare论坛clang大佬已经放出一键脚本，从SS到KCPTUN一键装好，真是贴心。以下内容就转载过来了:
脚本Github地址：https://github.com/clangcn/onekey-install-shell/tree/master/kcptun_for_ss_ssr
首先还是感谢，感谢 秋水逸冰 ，因为代码中很多都是借鉴了秋水大大的脚本，在此非常感谢大佬的付出。
下面开始简单的教程：
已测试过的平台：
CentOS 6 32/64bit
CentOS 7 32/64bit
Debian 6 32/64bit
Debian 7 32/64bit
Debian 8 32/64bit
Ubuntu 14 32/64bit
一、安装命令，这个命令都是在你的服务器上运行的
安装时间较长，网络不稳定的建议使用screen或者tmux进行安装，这两个东东请自行百度使用方法吧：
wget --no-check-certificate https://raw.githubusercontent.com/clangcn/onekey-install-shell/master/kcptun_for_ss_ssr/kcptun_for_ss_ssr-install.sh -O ./kcptun_for_ss_ssr-install.sh
chmod 700 ./kcptun_for_ss_ssr-install.sh
./kcptun_for_ss_ssr-install.sh install
二、安装步骤
1、运行脚本时会自动检测脚本是否有更新，如有更新会自动更新，然后需要再次运行脚本继续。
KCPTUN for SS/SSR 一键脚本

2、如果脚本是最新的，那么就会然你选择安装的内容：
KCPTUN for SS/SSR 一键脚本

KCPTUN for SS/SSR 一键脚本

KCPTUN for SS/SSR 一键脚本

KCPTUN for SS/SSR 一键脚本

三、卸载命令
./kcptun_for_ss_ssr-install.sh uninstall
复制代码
四、更新命令
./kcptun_for_ss_ssr-install.sh update
复制代码
原帖地址：http://koolshare.cn/thread-66315-1-1.html
