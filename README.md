#!/bin/bash
#tools to change your mac
#after download and unzip it ,using " bash install " to install
#after install you need to reboot of input "souce ~/.bashrc" to make it work
#this tool will remember you original mac and changed mac
#using "backmac" to change your mac back
#every time you reboot your mac is reseted,so you need to use "setmac"
#Warning: two or more computer in same mac under SAME NET will occor some error
#一些对付校网限制的小工具
#主要是我设备太多但校网只运行最多4台设备注册校网
#所以写了些脚本来解决这个问题
#使用方法：
#下载，然后bash install 安装脚本
#setmac:修改mac地址为已注册的设备以实现突破设备数量限制,但同不能同时使用2个mac相同的设备
#backmac:将你的mac改为原来的样子
#警告：相同mac地址连接同一网络会导致一些问题，部分学校网络管理员甚至会因此封mac...

#未来特性
#三个文件合为一个，自动安装，自动识别mac...
#可添加至开机自动修改（我还不会写开机脚本=。=）
#
