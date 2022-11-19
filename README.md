# <div align="center">VAIO SVE14136CVB Hackintosh</div> 

## Intro

| | Version |
|-|---------|
| OpenCore | 0.8.4 |
| macOS | Big Sur 11.7 |

![Screenshot](ScreenShot.png)

## Laptop Specification

|                     | Specifications| Note |
| ---------------------------- | ---------------------- |------------------|
| ``Chipset``| Intel Panther Point |   |
| ``CPU``| Intel Core i5-3230M 2.60GHz |  |
| ``Memory``| 8GB DDR3-1600MHz |  |
| ``iGPU``| Intel HD Graphics 4000 | With full QE/CI (Graphics accleration) |
| ``Disk``| EK V100 128GB |  |
| ``Screen``| 14.0" 1366 x 768 |    |
| ``Ethernet``| RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | Use [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases). |
| ``WiFi and Bluetooth``| Qualcomn Atheros AR9485 |  | 
| ``Audio``| ALC269 | Add `alcid=44` to boot-arg or add layout-id to DeviceProperties. |
| ``Keyboard``| - |  |
| ``Touchpad``| Synapstic, PS/2 |  |
| ``Battery``| 60Wh 6-cell lithium ion | |
| ``Dimensions``| 25.4mm x 344mm x 243.6mm |     |
| ``Weight``| 2.4kg |     |

## Features

| ``Features``|``Working``| 
|-------------|-----------|
| ``Wifi``|✅|
| ``Bluetooth``|✅|
| ``Audio``|✅|
| ``Keyboard and Trackpad``|✅|
| ``Headphone Jack``|✅|
| ``Graphics``|✅|
| ``Battery``|✅|
| ``Power Management``|✅|
| ``Multigesture Trackpad``|✅|                                                                          
| ``Webcam``|✅|
| ``USB Port``|✅|
| ``Facetime and iMessage``|✅|
| ``Ethernet``|✅|
| ``Hotkeys``|✅|
| ``Sleep``|❌|
