## 支持 BigSur

## 简介

- Lenovo ThinkPad E470c Hackintosh EFI ，基于OC包含基础驱动，修改三码后开箱即用。
- 适用版本：macOS BigSur(其他版本未测试)

### EFI自测试硬件配置

Lenovo ThinkPad E470c

- Intel i5-6200U
- 16GB RAM ( 8+8 )
- GLOWWAY 512G
- BCM94352Z
- 1080 IPS屏
 
### SMBIOS MacBookPro13,1
- 支持 BigSur 双向隔空

### 硬件使用状态

* [x] 集成显卡 HD520 2G显存
* [x] 有线网正常
* [x] 无线网（自带的无线网卡无法驱动，需换网卡）
* [x] 蓝牙 （同上）
* [x] 电池状态正常
* [x] 声音正常
* [x] 触控板（多点触摸手势全开）
* [x] F1、F2、F3、F5、F6、PrtSc（PrtSc支持需要设置键盘快捷键 默认为CTRL+COMMAND+3 改为 F13），注意：睡眠之后除PrtSc外其他F(x)键功能失效
* [x] 小红点正常
* [x] 休眠/唤醒/关机/重启 （电源LED、合盖/开盖全部状态正常）
* [x] USB全部端口
* [x] HDMI（显示正常，无声音，可切换为内置）
* [x] 3.5MM耳机孔（播放正常，麦克风不可用，可切换为内置）
* [x] hidpi (未测试，理论上可用）
* [ ] SD 卡读取（未支持）

## 使用方法

- 复制EFI到EFI分区（推荐使用Hackintool） 编辑EFI/OC/config.plist 修改SystemSerialNumber、SystemUUID、MLB三码


## 已知问题
- BIGSUR下除了睡眠按键问题（如果外接支持macos的键盘使用，则可避免），几乎完美
- SD 卡读取不支持

## 致谢

- daliansky https://blog.daliansky.net/
- JeoJay127 https://github.com/JeoJay127/RapidEFI-Tool
- rsdev69 https://github.com/rsdev69/ThinkPad-E560-Hackintosh
- Hackintosh Fans
