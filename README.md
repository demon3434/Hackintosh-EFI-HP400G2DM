# Hackintosh-EFI-HP400G2DM
## 惠普ProDesk 400 G2，黑苹果EFI

### 软件版本
| 软件 | 版本 |
| --- | :--: |
| 系统 | macOS Big Sur 11.6.5 (20G527) |
| 引导 | OpenCore v0.8.0 |

### 自选硬件
|   硬件    |   型号  |
| -------- | :----: |
| 主机 | 惠普 ProDesk 400 G2 DM |
| CPU | Intel Core i5 6600T |
| 内存 | 英睿达 DDR4 2666 4G*2 |
| 硬盘 | 紫光 S100 480GB |
| 显卡 | Intel UHD Graphics 530 |
| 显示器 | DIY便携屏，4K 60Hz |
| 无线网卡 | 联想拆机卡（ngff，1个缺口），博通BCM94352Z |

### 完成度
+ 核显正常驱动，2048MB显存
+ 声卡正常驱动
+ Wi-Fi、蓝牙正常驱动。Big Sur 11.6.5 (20G527) 下可以双向隔空投送
+ DP接口能亮屏，VGA接口未测试
+ 睡眠可唤醒
+ USB定制，所有USB接口（含Type-C）正常
+ Sata硬盘装Win10，OC可引导Win10
+ 引导界面图形化，开机有“duang”声音

### 缺陷
+ 初始安装，使用黑果小兵的镜像 macOS Big Sur 11.5.2 (20G95)，安装完毕未升版本，直接连接蓝牙音响，声音会有断断续续的卡顿现象，升级到11.6.5 (20G527)，蓝牙声音正常
+ 隔空投送，Monterey下只能接收，不能发送

### 备注
1. PlatformInform 模拟机型，选择 iMac17,1
2. 隔空投送问题未解决，建议不要升级Monterey

### 效果图
![关于本机.png](https://github.com/demon3434/Hackintosh-EFI-HP400G2DM/blob/main/OpenCore%20v0.8.0%20%26%20macOS%20Big%20Sur%2011.6.5%20(20G527)%20%26%20BCM94352Z/1.%E5%85%B3%E4%BA%8E%E6%9C%AC%E6%9C%BA.png "关于本机")
![蓝牙.png](https://github.com/demon3434/Hackintosh-EFI-HP400G2DM/blob/main/OpenCore%20v0.7.9%20%26%20%20macOS%20Big%20Sur%2011.6.5%20(20G527)%20%26%20BCM94352Z/2.%E8%93%9D%E7%89%99.png "蓝牙")
![Hackintool系统信息.png](https://github.com/demon3434/Hackintosh-EFI-HP400G2DM/blob/main/OpenCore%20v0.7.9%20%26%20%20macOS%20Big%20Sur%2011.6.5%20(20G527)%20%26%20BCM94352Z/3.Hackintool%E7%B3%BB%E7%BB%9F%E4%BF%A1%E6%81%AF.png "Hackintool系统信息")
