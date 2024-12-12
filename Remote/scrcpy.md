## scrcpy

（Windows）

```
scoop install adb
scoop install scrcpy
```

找到下载的scrcpy文件夹，把该文件夹加入系统环境变量

使手机和电脑连接同一个wifi

通过usb数据线将手机和电脑相连

手机打开开发者模式，启用“USB调试”、“USB调试（安全设置）”和”无线调试“（华为无”无线调试“）

```
adb tcpip 5555
```

去掉数据线

查找手机IP

```
adb connect <ip>
```

显示already connected to <ip>

```
scrcpy --keyboard=uhid
```

电脑输入法保持为英文！--keyboard=uhid可以输入中文

其他版本或有问题请查阅官方文档

[Genymobile/scrcpy：显示和控制您的 Android 设备 --- Genymobile/scrcpy: Display and control your Android device](https://github.com/Genymobile/scrcpy)

## zerotier

不需要在同一个wifi，实现内网穿透

[强大的内网穿透工具ZeroTier，随时随地远程访问家中NAS和其它设备！没有公网IP也不怕](https://www.bilibili.com/video/BV1hK4y1L7ND/?spm_id_from=333.337.search-card.all.click&vd_source=f7cadf462a105b99d7d00efa1a09735e)

