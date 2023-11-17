## [ROM] [GAUGUIN] [A13] [非官方] LineageOS 20 for Redmi Note 9 Pro 5G / Mi 10T Lite / Mi 10i

**提示** : 由 [kawaaii](https://github.com/kawaaii) 维护的 [LineageOS 20 官方版本](https://download.lineageos.org/devices/gauguin/builds) 已开放下载！不再建议使用此处提供的非官方版本，建议您使用官方版本！

[English](README.md) | 简体中文


### 免责声明

> 因使用本刷机包造成的设备损坏和数据丢失由使用者承担。
>
> 刷机有风险，操作需谨慎。
>
> 刷机前务必备份数据！

### 这是什么？

为 Redmi Note 9 Pro 5G / Mi 10T Lite / Mi 10i （代号 `gauguin`）适配的 LineageOS 20 （基于 Android 13）。

> LineageOS 是基于安卓移动平台的，为多种设备提供的自由和开源操作系统。

### 哪些功能可以正常使用？
* WiFi
* 通话、短信和上网 (RIL)
* 移动数据
* 蓝牙
* 指纹识别
* GPS
* 相机
* 闪光灯（手电筒）
* 红外遥控
* 声音
* 振动
* NFC
* SELinux 强制执行
* 文件加密
* FM 收音机*


> FM 收音机: 不使用 LineageOS 官方的 FM 收音机源码，因为官方的源码似乎有 Bug ，而使用[这一套源码](https://gitlab.com/lc0a/android_vendor_qcom_opensource_fm-commonsys)（基于 [ArrowOS 12.1](https://github.com/ArrowOS/android_vendor_qcom_opensource_fm-commonsys/tree/arrow-12.1)）。

### 已知问题
* **不要**把系统语言设置为**伪语言** \[ English ( **Pseudo Accents** )，`en-XA` \]，否则可能造成系统**崩溃**并且**无法启动**！

* 如果您在使用中遇到了 Bug ，欢迎告知作者！

### 下载

在 [Releases](https://github.com/lc0a/android_device_xiaomi_gauguin/releases) 中下载。

### 源码

* Repo 的 [附加清单](local_gauguin.xml)
* [Device tree](https://github.com/lc0a/android_device_xiaomi_gauguin/tree/lineage-20)
* 内核源码【 [原版](https://gitlab.com/lc0a/android_kernel_xiaomi_gauguin/tree/lineage-20-lc-stable) | [~~带KernelSU~~](https://gitlab.com/lc0a/android_kernel_xiaomi_gauguin/-/tree/lineage-20-lc-ksu) （从 [20230901](https://github.com/lc0a/android_device_xiaomi_gauguin/releases/tag/20230901) 起不再提供）】

* [专有文件](https://gitlab.com/lc0a/proprietary_gauguin)

### 致谢

* 原设备维护者 @KaguraRinko
