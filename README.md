# Hackintosh-i510400-B460M-MORTAR-WIFI
## EFI 
因为我装的是双系统，所以EFI中有`windows`引导文件，使用前删除`Microsoft`文件夹

EFI都是在网上东拼西凑找来的，后期有时间考虑学习自己定制一个，毕竟现在的EFI还有很多地方不是很好。

> 参考EFI及资料
> 
> https://mp.weixin.qq.com/s/UNtxsMIaKISyH6uRNt0LzQ
> 
> https://github.com/cheneyxx/Hackintosh-10400-B460M-MORTAR
> 
> https://www.bilibili.com/video/BV1Lf4y1i7FV?from=search&seid=15517732188143082051
> 
> https://github.com/OpenIntelWireless/IntelBluetoothFirmware
> 
> https://github.com/OpenIntelWireless/itlwm

macOS version: 11.3.1

镜像使用了黑果小兵的11.3.1镜像

## 硬件配置
|组件|型号|
|------|------|
|主板|微星 B460M MORTAR WIFI|
|CPU|Intel i5 10400|
|内存|金士顿骇客神条RGB灯条 8GB * 2 2666MHz|
|显卡|Intel UHD Graphics 630（CPU自带核显） |
|SSD|铠侠 RC10 512GB * 2|
|电源|振华LEADEX G 550|
|机箱|爱国者 M2 白色|
|散热|乔思伯CR-1000 白色|
|显示器|AOC Q27U2D 27寸/2K|

## Bios设置
![](./images/pic1.png)
![](./images/pic2.png)
![开启核显加速](./images/pic3.png)
![](./images/pic4.png)
![](./images/pic5.png)


## 功能测试和待完成
- [x] 睡眠/唤醒
- [x] 核显硬件加速
- [x] 声卡输出
- [x] windows和mac时间不同步问题
  windows下管理员身份运行命令
  ```
  Reg add HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation /v RealTimeIsUniversal /t REG_DWORD /d 1
  ```

## 不稳定的功能
蓝牙和wifi都不是太稳定(使用的是主板自带的AX200)
- [x] 蓝牙
- [x] wifi
- [x] HIDPI开启后感觉效果不大，帧率反而有明显的下降，字体有一点模糊（可能是2k分辨率不太够？）

### 关于本机
![](./images/mac_info.png)
![效果图](./images/效果图.jpg)

