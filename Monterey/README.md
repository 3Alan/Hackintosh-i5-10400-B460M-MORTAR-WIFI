## 基本信息

macOS version: 12.1 Monterey

引导方式：OC引导（0.7.6）

## EFI下载地址
[下载](https://github.com/3Alan/Hackintosh-i5-10400-B460M-MORTAR-WIFI/releases/tag/v2.0.0)

## 升级过程记录

### 操作
- 升级最新的 `opencore` (借助了工具 [QtOpenCoreConfig](https://github.com/ic005k/QtOpenCoreConfig))
- 更换 `AirportItlwm` 为 `Monterey` 版本
- 添加 `BlueToolFixup.kext`
- 升级最新的 `IntelBluetoothFirmware.kext` 并（禁用/删除） `IntelBluetoothInjector.kext`

### 遇到的坑
做完了上面的操作后，蓝牙死活没有用，几乎网上所有方案都试过了，最后在远景论坛找到了解决方案。
[查看](http://bbs.pcbeta.com/forum.php?mod=redirect&goto=findpost&ptid=1915971&pid=51985501)
> 关机后断电，断电后长按开机键5秒，接电源，开机。

