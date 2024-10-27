# 基于GEC6818开发板（s5p6818）移植64位linux系统-linux内核部分

[原版官方linux内核项目 READE文件](./kernel_README)

基于 https://github.com/friendlyarm/linux.git 工程，nanopi2-v4.4.y 分支，eb65719 提交进行开发

提交说明：dtsi: nanopi2/3: increase drive strength of i2c0


## 项目介绍：

[基于GEC6818开发板（s5p6818）移植64位linux系统_linux gec6818 3.4.39-gec #3 smp preempt tue jun 4 -CSDN博客](https://blog.csdn.net/B_X_Z/article/details/136825225#comments_32116831)

[基于GEC6818开发板（s5p6818）移植64位linux系统-烧录篇（一）-CSDN博客](https://blog.csdn.net/B_X_Z/article/details/141439554)



## 编译命令

```
make ARCH=arm64 gec6818_linux_defconfig
make ARCH=arm64
```

编译成功结束后，

linux/arch/arm64/boot目录下获得内核Image文件

linux/arch/arm64/boot/dts/nexell目录下获得s5p6818-gec6818.dtb设备树文件


## 微信讨论、交流群-针对gec6818开发板移植交流

<img src="Documentation/微信扫码加群.png" alt="微信扫码加群" style="zoom: 50%;" />
