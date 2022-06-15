# nanoUART-wl User Manual
* [Introduction](#introduction) 
* [How to Use](#how-to-use)
    * [Wire Connection](#wire-connection)
    * [Establish wireless connection](#establish-wireless-connection)
	* [Serial Software](#serial-software)
* [FAQ](#faq)
	
# introduction
nanoUART-wl is a wireless serial port tool made by MuseLab. It is plug and play, full duplex communication, and can support up to 460800 baudrate. For some debugging scenarios, such as the target is always in a moving state or at a high place, it can effectively improve the development efficiency
<div align=center>
<img src="https://github.com/wuxx/nanoUART-wl/blob/master/doc/nanoUART-wl-top.jpg" width = "500" alt="" align=center />
<img src="https://github.com/wuxx/nanoUART-wl/blob/master/doc/nanoUART-wl-bottom.jpg" width = "500" alt="" align=center />
</div>



# How to Use
nanoUART-wl is divided into the transmitter and the receiver. The transmitter is plug into the PC, and the receiver is connected to the target board. When the transmitter is plugged into the PC, a virtual serial device will appear in the device manager.
![usb_cdc_device](https://github.com/wuxx/nanoUART-wl/blob/master/doc/usb_cdc_device.png)  
and a virtual disk callled nanoUART-wl appear.
![disk](https://github.com/wuxx/nanoUART-wl/blob/master/doc/disk.png)
## Wire Connection
Generally, only three wires, GND, TX and RX need to be connected. Note that both sending and receiving are aimed at the board itself. For example, the pin marked TX on the receiver indicates that the receiver sends and needs to be connected to the serial port of the target board for reception.

## Establish wireless connection
After the transmitter and receiver are powered on, the blue light will start flashing. When the blue light changes from flashing to constant, it indicates that the wireless connection is established. At this time, the wireless serial port can be used
## Serial Software
It is recommended to use sscom or putty to open the  serial port. the use method is the same as wired serial port, and will not be repeated here.
![sscom](https://github.com/wuxx/nanoUART-wl/blob/master/doc/sscom.png)

# FAQ
