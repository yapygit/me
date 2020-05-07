# QtScrcpy 打手机游戏



QtScrcpy 是一款基于 Scrcpy 开源项目重构的用电脑控制 Android 手机的软件，支持多点触控、有图形界面、中文界面，
在 Windows 下可自定义按键映射，在电脑上进行手机游戏@Appinn

- QtScrcpy可以通过USB(或通过TCP/IP)连接Android设备，并进行显示和控制。不需要root权限，不需下载客户端。
- 单个应用程序最多支持16个安卓设备同时连接。
- 同时支持GNU/Linux，Windows和MacOS三大主流桌面平台

**用 QtScrcpy 打手机游戏，匹配时不被检查到，关键是免费**

 重点在于 QtScrcpy 在 Windows 下可自定义按键映射，用于玩游戏**可实现功能**

- 实时显示Android设备屏幕
- 实时键鼠控制Android设备
- 屏幕录制
- 截图为png
- 无线连接
- 最多支持16台设备连接（PC性能允许的情况下可以增加，需要自己编译）
- 全屏显示
- 窗口置顶
- 安装apk：拖拽apk到视频窗口即可安装
- 传输文件：拖拽文件到视频窗口即可发送文件到Android设备
- 后台录制：只录制，不显示界面
- 复制粘贴在计算机和设备之间双向同步剪贴板：
  - Ctrl + c将设备剪贴板复制到计算机剪贴板；
  - Ctrl + Shift + v将计算机剪贴板复制到设备剪贴板；
  - Ctrl +v 将计算机剪贴板作为一系列文本事件发送到设备（不支持非ASCII字符）。
- 群控

![img](D:\image\new\093100tqrydy29que8trun.png)



**下载地址**：
               官网https://gitee.com/Barryda/QtScrcpy/releases， 
            不想注册的 附件里有蓝凑云
**使用方法**：

有线连接

- 安卓手机（5.0+）端在开发者选项中打开 usb 调试
- 通过 usb 连接安卓手机到电脑
- 点击刷新设备，会看到有设备号更新出来
- 点击启动服务，即可食用
- 玩游戏的话，启动后刷新脚本
- 选择合适脚本，应用脚本即可

无线连接

- 安卓手机端在开发者选项中打开usb调试
- 通过usb连接安卓手机到电脑
- 点击刷新设备，会看到有设备号更新出来
- 点击获取设备IP
- 点击启动adbd
- 无线连接
- 再次点击刷新设备，发现多出了一个IP地址开头的设备，选择这个设备
- 启动服务

备注：启动adbd以后不用再连着usb线了，以后连接断开都不再需要，除非安卓adbd停了需要重新启动，部分手机不支持



![img](D:\image\new\093849dbg2cgycfhlttjfc.png)




 -----------------------------------补充部分-----------------------------------

- 自定义按键：官方教程》》[https://gitee.com/Barryda/QtScrcpy/blob/master/docs/%E6%8C%89%E9%94%AE%E6%98%A0%E5%B0%84%E8%AF%B4%E6%98%8E.md#](https://gitee.com/Barryda/QtScrcpy/blob/master/docs/按键映射说明.md#)
- 延迟：有线35~70ms  无线连会卡
- 自己写的改建教程： https://www.52pojie.cn/thread-1152899-1-1.html