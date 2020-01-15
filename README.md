# magicbook-hackintosh-opencore-i7-8550u
hackintosh for magicbook(i7-8550u) by opencore 0.5.4

# Honor-Magicbook
华为荣耀 Magicbook i7-8550u 14寸 黑苹果
## Configuration

| 描述   | 详情                                                  |
| ------------------- | ------------------------------------------- |
| 电脑型号      | 华为荣耀 Magicbook      |
| 处理器           | 英特尔酷睿i7-8550u处理器     |
| 内存              | 8 GB 2133 MHz LPDDR3              |
| 硬盘           | Crucial_CT250MX200SSD4 SATA    |
| 显卡 | Intel UHD Graphics 620 2048 MB                     |
| 声卡         | Realtek ALC256           |
| 摄像头 | hm1091_techfront |
| 无线网卡       | dw1820a                        |
| 触摸板 | ELAN2203 |


## 正常工作的设备

- 显卡
- 亮度控制快捷键 
- 无线网卡
    - 需要拆机更换无线网卡
- 蓝牙
- 隔空传送
- hdmi接口
- 触摸板
    - 手势完美
- 摄像头
- 声卡 Realtek ALC256 声卡ID为57
    - 开机如果连接耳机，会有破音；外放偶尔会出现破音，进行一次睡眠唤醒后就能正常
- 显示器
- 睡眠正常（一晚掉电不到1%）
  

## 不能正常工作的设备

- 指纹识别
- 独显 MX150
- typc接口无法接入显示器，会导致panic

## 其他
如果是初次安装，请在bios中关闭无线和蓝牙；
关于如何解锁cfg，请自行爬帖

## 参考
hjmmc/Honor-Magicbook(https://github.com/hjmmc/Honor-Magicbook)
