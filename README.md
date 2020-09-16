# Network-Reinstall-System-Modify

1. If you are from an English community, please click here.  
https://www.cxthhhhh.com/network-reinstall-system-modify  

2. 如果你来自于中文社区，请点击这里。  
https://www.cxthhhhh.com/network-reinstall-system-modify  
简介
一键网络重装系统 - 魔改版，它可以通过Internet重新安装Linux和Windows以及常见的操作系统。例如：Linux（CentOS，Debian，Ubuntu、etc..），Windows（2019、2016、2012R2、2008R2、7、2003、etc..），以及其他系统（不断支持更多中）。

当我们需要重装VPS/云平台/独立服务器操作系统时，通常可以通过服务商模板和ISO挂载的方式重新安装。从今天开始，你将拥有了一个全新的方式，通过网络一键式重新安装纯净操作系统，无需CD-ROM,无需VNC/IPIM/KVM。无论是Linux，还是Windows，都可以通过网络一键式完成安装，通过简单的一到两行命令开启全新而美妙的体验。

魔改版本及开源地址
最新版本：3.1.0（2020/09/15）

官方发布：https://www.cxthhhhh.com/network-reinstall-system-modify

Github：Network-Reinstall-System-Modify

魔改版本：CXTHHHHH (via) 原始版本：MoeClub(Vicer)

支持安装的系统
Alpine Linux、Anarchy Linux、Arch Linux、Backbox、BlackArch Linux、Bluestar Linux、Bodhi Linux、CentOS、CoreOS、Debian、Deepin、Devuan、Elementary OS、Fedora、Feren OS、Flatcar Linux、FreeBSD、FreeDOS、Gentoo、IPFire、Kali Linux、KDE Neon、Kodachi、Linux Lite、Q4OS、Microsoft Windows、Mageia、Manjaro、Mint、MirOS、Nitrux、NixOS、OpenBSD、OpenSUSE、Oracle Linux、Parrot Security、Peppermint、Proxmox-VE、Pop OS、Red Hat Enterprise Linux、Regolith、RancherOS、Scientific Linux、Slackware、SparkyLinux、Tails、Tiny Core Linux、Ubuntu、Velt、Voyager、Zen Installer、Zorin OS、ALT Linux Rescue、Boot Repair CD、Breakin、CAINE、Clonezilla、DBAN、GParted、Grml、Memtest、Rescatux、Super Grub2 Disk、System Rescue CD、Ultimate Boot CD
如何使用
1、下载脚本（通过root用户执行）
wget --no-check-certificate -qO ~/Network-Reinstall-System-Modify.sh 'https://www.cxthhhhh.com/CXT-Library/Network-Reinstall-System-Modify/Network-Reinstall-System-Modify.sh' && chmod a+x ~/Network-Reinstall-System-Modify.sh
2、安装系统（任选其一）
【图形化UI界面选择】（推荐）
bash ~/Network-Reinstall-System-Modify.sh -UI_Options
【合并执行】一键启动图形化UI界面，选择安装系统（包含下载+执行）：

wget --no-check-certificate -qO ~/Network-Reinstall-System-Modify.sh 'https://www.cxthhhhh.com/CXT-Library/Network-Reinstall-System-Modify/Network-Reinstall-System-Modify.sh' && chmod a+x ~/Network-Reinstall-System-Modify.sh && bash ~/Network-Reinstall-System-Modify.sh -UI_Options
【安装 裸机系统部署平台】（推荐）
bash ~/Network-Reinstall-System-Modify.sh -CXT_Bare-metal_System_Deployment_Platform
【安装 Linux】（推荐）
bash ~/Network-Reinstall-System-Modify.sh -CentOS_8
bash ~/Network-Reinstall-System-Modify.sh -Debian_10
bash ~/Network-Reinstall-System-Modify.sh -Ubuntu_20.04
【安装 Windows】（推荐）
bash ~/Network-Reinstall-System-Modify.sh -Windows_Server_2019
【安装 指定自定义 DD镜像】（推荐）
bash ~/Network-Reinstall-System-Modify.sh  -DD "%URL%"
【安装 更多系统 说明】
此页面为【一键网络重装系统 - 魔改版】发布页，仅列出了常用Linux和Windows的最新稳定版系统安装命令（截至2020年9月）。
要安装其他版本，请通过【图形化UI界面选择】/【裸机系统部署平台】/【手动输入版本】/【查看更多选项】等方式安装。

对于普通用户，直接一键脚本安装最方便，甚至可以直接使用（图形化UI界面选择）选项，一键安装常用系统。
对于高端用户，建议直接选择通过（裸机系统部署平台）安装任意系统。可定制化性高，但门槛相对高很多，便捷性较低。

本项目仅建议您安装最新的稳定版系统。新版系统具有官方长期的技术支持，而旧版已经失去官方支持，亦或者即将失去维护。
使用旧版操作系统，您的电脑和服务器将面临比新版操作系统更多的安全隐患，甚至造成巨大的损失。

恭喜，你已经完成了系统重装
常规说明
1、当您执行完上面的2行命令，你的服务器将开始网络重装纯净系统。在完成安装前，您将无法进行连接管理。因硬件配置和网络环境不同，安装全程需要15-60分钟，请耐心等待。安装完成即可通过IP:22(Linux SSH)/IP:3389(Windows RDP)进行连接。

2、为了保证更高的兼容性。推荐重装纯净系统前，您当前的系统版本为：CentOS 7 / Debian 9 / Ubuntu 18.04 。（在您的服务商未提供以上操作系统时，您可以考虑使用其他系统）

默认账户
通常，使用自带镜像，或者您的镜像作者未明确说明系统的用户名和密码的情况下。

对于Microsoft Windows。
默认的用户名是：Administrator
默认的密码是：cxthhhhh.com

对于Linux（CentOS / Debian / Ubuntu），裸机系统部署平台等。
默认的用户名是：root
默认的密码是：cxthhhhh.com

安全提示
【提示】系统重装完成后，请您务必立刻修改系统的默认密码【cxthhhhh.com】，并做好系统更新和安全补丁工作，否则您的服务器可能面临安全隐患。（由于本站默认密码为公开网址，因此可能已经被密码字典收录）

## Common Problem
Here and the tutorials in my blog will cover the answers to most questions.

1. Q：The default password for the system installation?  
A：The default password for all system installations is [cxthhhhh.com]. To prevent brute force cracking, you must change the default password immediately after installation!

2. Q：How to connect and control my new system？  
A：Due to different hardware configuration and network environment, the installation takes 15 to 60 minutes, please be patient. Once the installation is complete, you can connect via IP: 22 (Linux SSH) / IP: 3389 (Windows RDP).

3. Q：How to manually install any system using [Bare-metal_System_Deployment_Platform]?  
A：It's hard to describe the process in one sentence, so visit my blog and follow the tutorial.

4. Q：Why isn't the content of the project stored on Github not all?  
A：As we all know, Github can only upload files smaller than 100MB. However, as of January 1, 2019, all files in the entire Network-Reinstall-System-Modify project totaled more than 50GB. So I can only upload script content and smaller files, including various image files and the auxiliary platform I built will not be able to upload. But you can visit [Open Disk CDN](https://odc.cxthhhhh.com/) to learn more.

5. Q：How to communicate? Feedback question?[Support language English (Recommended), Chinese (中文).]  
A：You can join my Telegram channel and discussion groups for instant communication and feedback. You can also submit an Issues, but this is not immediate, but it is easy to track.  
[Telegram Channel：My Share](https://t.me/me_share)  
[Telegram Chat Group：Technical Blog | 技術博客](https://t.me/Technical_Blog)


## End Notes
[Network-Reinstall-System-Modify](https://www.cxthhhhh.com/)

Version：V3.1.0  
Date：2020/09/15

[CXT - Enjoy Life | 生活、技术、交友、分享 - 自天佑之，吉无不利](https://www.cxthhhhh.com/)  
https://www.cxthhhhh.com/
