# CAWController控制器

### 简介

该控制器集成了STM32F407VET6芯片和CC2640R2F可编程蓝牙芯片，可用于开发一些无线通讯的产品，适合学习STM32和CC2640蓝牙的同学。

这款开发板将STM32芯片的USART1和CC2640的UART0引脚用排针引出。支持USB串口下载程序（CC2640需要启用bootloader后门）。

STM32支持SWD下载调试，CC2640支持cJTAG调试。

蓝牙连接测试，穿墙在10米距离左右能够正常连接（使用的BLE Scanner软件）。

### 如何制造

将Gerber打包成zip格式的压缩包，然后上传给嘉立创即可。在bom目录下有物料表，焊接的时候可以打开里边的html文件对照着焊接。

### 图片展示

![](https://github.com/GUAIK-ORG/CAWController/blob/master/imgs/PCB.png?raw=true)

![](https://github.com/GUAIK-ORG/CAWController/blob/master/imgs/3D_F.png?raw=true)

![](https://github.com/GUAIK-ORG/CAWController/blob/master/imgs/3D_B.png?raw=true)

![](https://github.com/GUAIK-ORG/CAWController/blob/master/imgs/SHELL.png?raw=true)

![](https://github.com/GUAIK-ORG/CAWController/blob/master/imgs/F.jpg?raw=true)

![](https://github.com/GUAIK-ORG/CAWController/blob/master/imgs/B.jpg?raw=true)

![](https://github.com/GUAIK-ORG/CAWController/blob/master/imgs/Scanner.jpg?raw=true)
