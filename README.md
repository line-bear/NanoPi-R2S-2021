# 中文简体 | [English](https://github.com/DHDAXCW/NanoPi-R2S-2021/blob/main/EngLish.md)
# 项目正在重置中~
# NanoPi-R2S-2021 每天自动更新插件和内核版本。
## 👉使用本固件前，请严格遵守国家互联网使用相关法律规定,不要违反国家法律规定！👈
## ``` 由于源码无法从硬盘拿出来，只好重新做了。，目前重构进度只有70%用在本镜像闭源上，后期尽量处理，这一个月已更新了下面这几点东西 ```
## 强烈推荐三星TF卡\海康TF卡。哪怕是很难刷上的固件，只有三星刷上可以开机。
### 注：不要用恢复备份。。不保证某个插件是否正常运行。。。建议重新设置贼好！！！
这一个月我没电脑都在讨乞（求电脑中~）。。。 
### 默认编译 

- 用户名：root 密码：password 管理IP：192.168.2.1
- x86_64固件下载 谷歌网盘 https://drive.google.com/file/d/11Qit2AAupTXkUnG66LHK550UADmTkb-R/view
### - beta：高大全
### - stable：稳定精简
### - WANLAN：互换 高大全
- 电报群：https://t.me/DHDAXCW
# 赏个鸡腿吧
 ![捐赠](data/2.jpg?raw=true "Title")
### 如果你觉得此项目对你有帮助，可以捐助我们，以鼓励项目能持续发展，更加完善
# 插件展示
 ![插件展示](data/20.jpg?raw=true "Title")
## 提示
 - 我的固件加了动态超频，不管热不热这是取决后台运行程序在跑什么。
 - 感觉很热  就加风扇，推荐 风扇6cm×6cm，薄1cm，usb也行 或者端子线zh1.5
 - 更新模块有很严重的问题 目前开发者无法修复
### 更新日志 6.19（如果没有就等明天呗）
- 新增ARMv8 硬件AEM解密补丁，提高翻墙速度
- 修复动态dns缺失部分域名
- 新增docker插件，讲此插件改为独立菜单，不再是服务里菜单
- 更新代理协议
- 内核从5.10退回5.4（因boot无法写入成功）
- 将性能改为平衡模式，高性能容易死机
- 修复bug
