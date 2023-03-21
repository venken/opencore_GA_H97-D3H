# opencore_GA_H97-D3H
OpenCore-0.9.0-DEBUG版本

U盘制作方法完全按照官方操作
https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos
EFI文件测试成功的镜像镜像如下

Catalina (10.15)
python3 macrecovery.py -b Mac-00BE6ED71E35EB86 -m 00000000000000000 download

机器环境配置如下：
主板：技嘉GA_H97-D3H 【技嘉YYDS】
内存：金士顿骇客神条8G-1600*4
显卡：影驰GT740骁将
硬盘：英睿达(Crucial)美光 500GB

EFI介绍：
进入菜单选择需要按空格 出现mac恢复安装菜单栏
取消隐藏安装菜单需要调整plist文件： Misc 》 Hideauxiliary 》false

![微信图片_20230321214317](https://user-images.githubusercontent.com/12839049/226625606-4251762c-0458-4cd4-80ca-7fdc58e71b3e.jpg)
