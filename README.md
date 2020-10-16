# Hackintosh EFI for HP ProBook 440 G4

### - 镜像来自黑果小兵，版本是 `10.15.7`，在此基础上修改EFI。
### - 目前声卡，核显，HDMI（开机之后需要插拔一次HDMI线），触摸板，有线网卡都是可以用的。
### - 蓝牙我没有测试，因为我从来没用过。
### - 自带的 `RTL8723BE` 无线网卡暂时是无解的。
### - 重启之后 `BIOS` 会提示时间不对，但是 `RTC` 相关的各种补丁我没有尝试成功。
### - 目前勉强可用，以后有机会再更新。
---
## 配置如下
```
Model              HP ProBook 440 G4
Mainboard          Intel H270
CPU                Intel Core i5-7200U
Memory             24G DDR4 2133MHz (8G)
Graphics           Intel HD Graphics 620
Audio              Conexant CX20632
Ethernet           Realtek RTL8111/8168/8411
Wi-Fi              Realtek RTL8723BE
```
