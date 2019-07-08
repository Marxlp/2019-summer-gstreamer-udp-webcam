# gstreamer udp camera transfer command lines 
清华计算机学院2019年，大三小学期机器人实践课，无人机与地面站之间图像传输实现
这里基于 Gstreamer 库提供的工具实现图像基于UDP的传输

## Installation
参考[https://gstreamer.freedesktop.org/documentation/installing/index.html?gi-language=c](https://gstreamer.freedesktop.org/documentation/installing/index.html?gi-language=c)

## Commmand Lines
1 首先连接到 AirZen 的Access Point, 密码：testzed000

2 然后通过 ssh 连接到 companion computer ， 密码 nvidia

> $ ssh -p 5222 nvidia@192.168.2.1

3 进入 script 文件夹

> $ cd script
> $ ./transfer_camera_data.sh

4 在本地电脑运行

Windows 

> accept_data.bat 

Linux

> ./accept_data.sh

## Some Instructions
see [docs](./docs)
