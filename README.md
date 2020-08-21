# HP-15-ax015tx-macOS11-OC6.0EFI
暗影精灵2 macOS 11 B5 完美EFI
| 硬件| 型号|   
| :----: | :---- |
| CPU | I5 6300HQ |    
|内存 | 8G*2 DDR4 |     
|显卡| Intel HD Graphics 530 + NVIDIA GeForce GTX 960Mi |     
|网卡| Realtek RTL8111H + BCM94352z |     
|声卡| Realtek ALC295  |   
## 系统支持
系统：macOS 11 B3
EFI:OC0.6.1  编译日期2020-08-04
### 正常功能：  
1. 核心显卡
2. FN按键
3. 电源管理
4. 睡眠
5. 声音
6. 蓝牙
7. 触摸板
8. 摄像头
9. 无线网卡
10. 隔空投送  

# 注意:同系列使用我的EFI请注意APCI下的补丁 文件里面的APCI 命名是否和你们的DSDT里面一样.
具体SSDT是否通用请移步 小兵的仓库查看 https://github.com/daliansky/OC-little  
## 例如:`SSDT-ALS0.aml` 仿冒环境光传感器补丁  

原始 `ACPI` 存在环境光传感器设备接口和不存在环境光传感器设备接口。首先在原始 `ACPI` 里面查找 `ACPI0008`，如果可以查到相关设备，一般是 `ALSD`，则说明存在环境光传感器设备接口，否则即为不存在环境光传感器设备接口。  

我的原始`ACPI`并没有存在`ACPI0008` 所以使用的是`SSDT-ALS0.aml`    

具体请进入 https://github.com/daliansky/OC-little/tree/master/02-%E4%BB%BF%E5%86%92%E8%AE%BE%E5%A4%87/02-4-%E4%BB%BF%E5%86%92%E7%8E%AF%E5%A2%83%E5%85%89%E4%BC%A0%E6%84%9F%E5%99%A8 查看     
