# nanoUART-wl 用户手册
* [产品介绍](#产品介绍) 
* [使用说明](#使用说明)
    * [建立无线连接](#建立无线连接)
	* [打开串口工具](#打开串口工具)
* [FAQ](#faq)
	
# 产品介绍
nanoUART-wl是实验室推出的无线串口工具，即插即用，无需驱动，双向通信，最高可支持460800波特率输出，对于某些调试场景如目标始终处于移动状态或者位于高处等，可有效提高开发效率  
![screenshot](https://github.com/wuxx/nanoUART-wl/blob/master/doc/nanoUART-wl.jpg)

# 使用说明
无线串口分为发射机和接收机，将发射机插入PC中，接收机则和目标板连接。 
当发射机插入PC后，设备管理器中会出现虚拟串口设备。  
![usb_cdc_device](https://github.com/wuxx/nanoUART-wl/blob/master/doc/usb_cdc_device.png)  
同时PC中会出现一个名为nanoUART-wl的虚拟U盘，U盘内为产品相关的资料链接，虚拟U盘亦可用于无线串口本身的固件升级。  
![disk](https://github.com/wuxx/nanoUART-wl/blob/master/doc/disk.png)
## 接线说明
一般只需连接三根线，GND，TX，RX，注意发送和接收均是针对板子自身而言，例如接收机上标记为TX的引脚，说明是接收机发送，需要接目标板的串口接收。  

## 建立无线连接
发射机和接收机上电之后，均会开始蓝灯闪烁，当蓝灯由闪烁变为常亮后，说明无线连接建立，此时可开始使用无线串口  
## 打开串口工具
推荐使用sscom或者putty连接串口使用，此时使用方法和有线串口一致，在此不再赘述。  
![sscom](https://github.com/wuxx/nanoUART-wl/blob/master/doc/sscom.png)
# FAQ
