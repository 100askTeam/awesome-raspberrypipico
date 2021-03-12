# Raspberry Pi Pico 资源列表

Raspberry Pi [Pico](https://www.raspberrypi.org/documentation/pico/getting-started/) 是 具有灵活数字接口的低成本，高性能微控制器板。

## 目录
- [文档](#文档)
- [软件/工具](#软件与工具)
- [资源](#资源)
    - [博客](#博客)
    - [书籍](#书籍)
    - [社区](#社区)
    - [项目](#项目)
    - [教程](#教程)

## 文档

- [Getting Started](https://datasheets.raspberrypi.org/pico/getting-started-with-pico.pdf) - 官方Pico入门指南。
- [Pico SDK C/C++](https://datasheets.raspberrypi.org/pico/raspberry-pi-pico-c-sdk.pdf) - Pico SDK C / C ++-官方Pico C/C++ SDK文档。
- [Pico SDK MicroPython](https://datasheets.raspberrypi.org/pico/raspberry-pi-pico-python-sdk.pdf) - Pico SDK MicroPython-官方MicroPython SDK文档。
- [Pico Doxygen](https://raspberrypi.github.io/pico-sdk-doxygen/index.html) - Pico Doxygen-官方的"Raspberry Pi Pico的API级别Doxygen文档"。
- [Pinout Diagram](https://datasheets.raspberrypi.org/pico/Pico-R3-A4-Pinout.pdf) - 树莓派pico官方引脚图。
- [Fritzing Diagram](https://datasheets.raspberrypi.org/pico/Pico-R3-Fritzing.fzpz) - Fritzing图表-官方的Pico Fritzing图表。
- [Design Files](https://datasheets.raspberrypi.org/pico/RPi-Pico-R3-PUBLIC-20200119.zip) - 设计文件-官方的Pico硬件设计文件。
- [Pico Datasheet](https://datasheets.raspberrypi.org/pico/pico-datasheet.pdf) - Pico数据手册-官方Pico数据手册。
- [RP2040 Datasheet](https://datasheets.raspberrypi.org/rp2040/rp2040-datasheet.pdf) - RP2040芯片数据-官方RP2040芯片数据手册。
- [Hardware Design](https://datasheets.raspberrypi.org/rp2040/hardware-design-with-rp2040.pdf) - 硬件设计-RP2040的官方硬件设计参考手册。

## 软件与工具

- [Pico 示例](https://github.com/raspberrypi/pico-examples) - Raspberry Pi Pico SDK示例。
- [Pico MicroPython示例](https://github.com/raspberrypi/pico-micropython-examples) - Raspberry Pi Pico MicroPython示例。
- [Pico SDK Repo](https://github.com/raspberrypi/pico-sdk) - 官方Raspberry Pi Pico SDK存储库。
- [Pico C++ Setup Script](https://github.com/raspberrypi/pico-setup/blob/master/pico_setup.sh) - 一个BASH脚本，用于在您的设备上设置Pico C ++工具链。
- [Picotool](https://github.com/raspberrypi/picotool) - Picotool是一种用于检查RP2040二进制文件并在处于BOOTSEL模式时与RP2040设备进行交互的工具。
- [Picoprobe](https://github.com/raspberrypi/picoprobe) - 可以使用一个Raspberry Pi Pico调试另一个Pico。 这可以通过picoprobe实现，该应用程序允许Pico充当USB→SWD和UART转换器。 
- [Resetting Pico Flash Memory](https://github.com/raspberrypi/pico-examples/blob/master/flash/nuke/nuke.c) - 强制将Raspberry pi pico闪存空间清除为空。
- [Thonny IDE](https://github.com/raspberrypi/thonny-pico) - Thonny IDE对Pico的支持。
- [Pico-Stub](https://github.com/cpwood/Pico-Stub) - 从Visual Studio Code中对树莓派pico的python代码插入和自动补全。
- [Pimoroni Pico](https://github.com/pimoroni/pimoroni-pico) - Pimoroni Pico库和示例包含micropython 和C/C++支持。

## 资源

### 博客

- [Official Pico Announcement](https://www.raspberrypi.org/blog/raspberry-pi-silicon-pico-now-on-sale/) - Raspberry Pi Pico首次发布。
- [MicroPython Book](https://www.raspberrypi.org/blog/new-book-get-started-with-micropython-on-raspberry-pi-pico/) - 新书可帮助您入门Raspberry Pi Pico上的MicroPython。
- [NeoPixel Dithering](https://www.raspberrypi.org/blog/neopixel-dithering-with-pico/) - HackSpace杂志用Raspberry Pi Pico看NeoPixels。
- [Closer Look at RP2040](https://www.cnx-software.com/2021/01/27/a-closer-look-at-raspberry-pi-rp2040-programmable-ios-pio/) - 详细学习Raspberry Pi RP2040可编程I/O（PIO）。

### 书籍
- [MicroPython Pico](https://hackspace.raspberrypi.org/books/micropython-pico) - 开始使用micropython学习raspberrypi pico开发板。

### 社区

### 项目

- [Pico Tetris](https://github.com/rbirkby/picotetris) - 安装在Pimoroni Pico Explorer上的Raspberry Pi Pico上的俄罗斯方块。  
- [Pico Display Colour Change](https://github.com/shane-powell/pico-display-colour-change) - 使用Pimoroni的展示包的Pico应用。
- [Pico Lib for NeoPixels](https://github.com/benevpi/pico_python_ws2812b) - 一个使用NeoPixels（WS2812b LED)的Raspberry Pi Pico库。
- [TensorFlow Lite Micro](https://github.com/raspberrypi/pico-tflmicro) - 用于Pico的TensorFlow Lite Micro库。
- [Rust Support Crate](https://github.com/devsnek/pio-rs) - 为Raspberry Pi的PIO架构提供支持。
- [morse4pico](https://github.com/slouchd/morse4pico) - 用于Raspberry Pi Pico的MicroPython中非常简单的摩尔斯电码脚本。
- [picoLCD](https://github.com/zadi15/picoLCD) - picoLCD是使Raspberry Pi Pico上的基于HD44780的LCD屏幕更方便接口功能的集合。
- [Balloon Tracking](http://www.daveakerman.com/?p=2737) Raspberry Pi Pico天气气球跟踪设备。代码在 https://github.com/daveake/pico-tracker
- [Pico Snake](https://github.com/Tohaker/pico-snake) - 在Pimoroni Pico Explorer中运行的Raspberry Pi Pico蛇。
- [Annoying Book Mark](https://github.com/rhipps/Annoying-Book-Mark) - 一个用于计算自您上次打开书以来经过的时间书签。

### 教程

- [Control an LED](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico) - 树莓派官方提供的设置文档，使用micro python语言控制led灯。
