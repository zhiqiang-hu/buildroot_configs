# Lotlab Boards Buildroot config

Lotlab的板子配置

## 用法

```
cd $PATH_TO_BUILDROOT
make BR2_EXTERNAL=$PATH_TO_THIS_FOLDER menuconfig

make lotlab_fam_defconfig # 载入某个指定硬件的defconfig
```

## 扩展脚本

```
#!/bin/sh

make linux-update-defconfig
make uboot-update-defconfig
make busybox-update-config
make update-defconfig
```
