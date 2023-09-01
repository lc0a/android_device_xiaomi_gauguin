## [ROM] [GAUGUIN] [A13] [UNOFFICIAL] LineageOS 20 for Mi 10T Lite / Mi 10i / Redmi Note 9 Pro 5G

English | [简体中文](README_CN.md)

```
* Your warranty is now void.
*
* I am not responsible for bricked devices, dead SD cards,
* thermonuclear war, or you getting fired because the alarm app failed. Please
* do some research if you have any concerns about features included in this ROM
* before flashing it! YOU are choosing to make these modifications, and if
* you point the finger at me for messing up your device, I will laugh at you.
```

### What is this?

LineageOS 20 for Mi 10T Lite / Mi 10i / Redmi Note 9 Pro 5G (codename `gauguin`).

> LineageOS is a free and open-source operating system for various devices, based on the Android mobile platform.

### What's working?
* WiFi
* RIL
* Mobile data
* Bluetooth
* Fingerprint
* GPS
* Camera
* Flashlight
* IR
* Sound and audio
* Vibration
* NFC (Excluding Indian devices)
* SELinux Enforcing
* Filesystem encryption
* FM Radio*


> FM Radio: Not using LineageOS's official FM App source because it doesn't work on this device, using [this](https://gitlab.com/lc0a/android_vendor_qcom_opensource_fm-commonsys) (based on [ArrowOS 12.1](https://github.com/ArrowOS/android_vendor_qcom_opensource_fm-commonsys/tree/arrow-12.1)) instead.

### Known issues
* **DO NOT** set the system language to `en-XA` a.k.a. English ( **Pseudo Accents** ), otherwise the system may **CRASH** and stuck in a **BOOT LOOP** !

* You tell me!

### Download

Download from [Releases](https://github.com/lc0a/android_device_xiaomi_gauguin/releases) page.

### Source code

* [Additional manifest](local_gauguin.xml) for repo
* [Device tree](https://github.com/lc0a/android_device_xiaomi_gauguin/tree/lineage-20)
* Kernel source ( [Vanilla](https://gitlab.com/lc0a/android_kernel_xiaomi_gauguin/tree/lineage-20-lc-stable) | [~~With KernelSU~~](https://gitlab.com/lc0a/android_kernel_xiaomi_gauguin/-/tree/lineage-20-lc-ksu) (deprecated since [20230901](https://github.com/lc0a/android_device_xiaomi_gauguin/releases/tag/20230901)) )
* [Proprietary files](https://gitlab.com/lc0a/proprietary_gauguin)

### Credits

* Original device maintainer @KaguraRinko
