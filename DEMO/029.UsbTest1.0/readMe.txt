libusb1.0版本做出了重大修改
在windows下，首先需要用zadig软件安装驱动，当然也可以导出驱动
安装libusb-win32的话，只能支持usb2.0
安装libusbx或者winusb的话，可以支持3.0
本demo在设备测试通过
芯片使用FX3
VID 0x04B4
PID 0x00F1
配置只有一个
接口只有一个
设置只有一个
端点有两个，0x01和0x81