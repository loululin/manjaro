[TOC]

sudo pacman-mirrors --fasttrack 

# manjaro常用软件
1. 编辑工具 sublime  [sublime中文支持可以参考我的csdn博客](https://blog.csdn.net/dixialieren/article/details/83624260) && typora
2. 浏览器 chrome
3. ssh远程客户端工具 secureCRT(remmina界面字体颜色显示有缺陷）  https://download.csdn.net/download/dixialieren/12408607
4. db客户端工具 dbeaver[7.1 企业版 破解   https://zhile.io/2019/05/08/dbeaver-license-crack.html]
5. 包管理工具 pamac-manager   开启Aur配置--------进程管理 系统卫士（系统监视器）
6. 包删除安装工具  pamac-manager（安装和升级）|||   octopi（卸载）
7. 终端工具 oh my zsh
8. 思维导图 xmind zen
9. email client foxmail------aur  使用pamac-manager install
10. ovpn client openvpn(sudo openvpn --config LOULVLIN.ovpn)
11. 空间清理 bleachbit
12. 防病毒 clamav
13. java dev idea webstorm
14. 截图 安装deepin 设置 快捷键  全局快捷键  KDE Daemon 设置 alt +a (sudo pacman -S flameshot-git #截图工具 flameshot比较好用）
15. 显示桌面  设置 快捷键  全局快捷键 Plasma  显示桌面 Meta+D
16. 打开文件资源管理 Dolphin 设置 快捷键 Meta+E
17.  web下载工具 uget / thunderspeed
18.  git client  gitkraken
19.  端口查看工具 net-tools / lsof
20. 远程桌面客户端　KRDC  rdp  远程登陆windows
21. sudo pacman -S screenfetch # 显示Linux环境工具
22. 进程管理 系统卫士
23. windowns远程登陆manjaro RealVNC manjaro上安装RealVNC的server，windowns上安装RealVNC的viewer 具体使用参考有道云
24. txt文本编辑工具 Notepadqq
25. crontab install--sudo pacman -S cronie && systemctl enable cronie.service
26. redis client ---AnotherRedisDesktopManager
27. mongo client ----robo 3t
28. wechat ----wine-wecht && wine-for-wechat
# yakuake设置
1.安装oh my zsh (主题 ZSH_THEME="powerlevel9k/powerlevel9k"
)-------NEW powerlevel10k   参考：https://github.com/loululin/powerlevel10k
2.在yakuake界面终端右键  选择 编辑当前方案  - 外观  配色方案和背景 Maia
字体 Noto Mono   字体大小 14.0

# other
1.manjaro下打开pdm（powerdesigner）文件,可以参考http://www.dmanywhere.cn/   自己构建一个工具，方便快捷;     
2.tim 无法发送接收图片解决，直接关闭ipv6即可,具体操作如下：
```
方法是在开机的时候传递一个必要的内核参数。
用文本编辑器打开 /etc/default/grub 并给GRUB_CMDLINE_LINUX变量添加“ipv6.disable=1”。
	
sudo vim /etc/default/grub

找到这一行 GRUB_CMDLINE_LINUX=“xxxxx ipv6.disable=1”
上面的“xxxxx”代表任何已有的内核参数,在它后面添加“ipv6.disable=1”。
sudo update-grub
最后重启电脑
```
3.符号连接
```
#dbeaver
sudo ln -s /home/loulvlin/soft/dbeaver/dbeaver /usr/bin/dbeaver
#typora
sudo ln -s /home/loulvlin/Downloads/Typora-linux-x64/Typora /usr/bin/typora
#secureCRT
sudo ln -s /opt/securecrt/scrt-8.3.4/SecureCRT /usr/bin/secureCRT
#vpnstart
sudo ln -s /home/loulvlin/vpnstart.sh /user/bin/vpnstart

```

