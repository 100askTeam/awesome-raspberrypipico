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
    - [视频](#视频)

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

- [Official Pico Announcement](https://www.raspberrypi.org/blog/raspberry-pi-silicon-pico-now-on-sale/) - The official Raspberry Pi Pico annoucement.
- [MicroPython Book](https://www.raspberrypi.org/blog/new-book-get-started-with-micropython-on-raspberry-pi-pico/) - New book available to help get you started with MicroPython on Raspberry Pi Pico.
- [NeoPixel Dithering](https://www.raspberrypi.org/blog/neopixel-dithering-with-pico/) - HackSpace magazine look at NeoPixels with the Raspberry Pi Pico.
- [Closer Look at RP2040](https://www.cnx-software.com/2021/01/27/a-closer-look-at-raspberry-pi-rp2040-programmable-ios-pio/) - A closer look at Raspberry Pi RP2040 programmable I/Os (PIOs).

### 书籍
- [MicroPython Pico](https://hackspace.raspberrypi.org/books/micropython-pico) - 'Get Started With MicroPython on Raspberry Pi Pico'.


### 社区

### 项目

- [Pico Tetris](https://github.com/rbirkby/picotetris) - 'Tetris on a Raspberry Pi Pico mounted on a Pimoroni Pico Explorer.'
- [Pico Display Colour Change](https://github.com/shane-powell/pico-display-colour-change) - 'A Pico app using Pimoroni's display pack.'
- [Pico Lib for NeoPixels](https://github.com/benevpi/pico_python_ws2812b) - A Raspberry Pi Pico library for using NeoPixels (WS2812b LEDs).
- [TensorFlow Lite Micro](https://github.com/raspberrypi/pico-tflmicro) - An official port of the TensorFlow Lite Micro library for the Pico.
- [Rust Support Crate](https://github.com/devsnek/pio-rs) - Rust support crate for Pico's PIO architecture.
- [morse4pico](https://github.com/slouchd/morse4pico) - Very simple Morse code script in MicroPython for the Raspberry Pi Pico.
- [picoLCD](https://github.com/zadi15/picoLCD) - 'picoLCD is a collection of functions to make interfacing with HD44780 based LCD screens easier on the Raspberry Pi Pico.'
- [Balloon Tracking](http://www.daveakerman.com/?p=2737) - Dave Akerman creates a Raspberry Pi Pico weather balloon tracking device. Code is available at https://github.com/daveake/pico-tracker
- [Pico Snake](https://github.com/Tohaker/pico-snake) - Snake for the Raspberry Pi Pico, running on the Pimoroni Pico Explorer.
- [Annoying Book Mark](https://github.com/rhipps/Annoying-Book-Mark) - A bookmark that counts the amount of time that has passed since you last opened your book.

### 教程

- [Control an LED](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico) - Official Raspberry Pi documentation for setting up the Pico. Then controlling an LED with MicroPython.

### 视频

- [Raspberry Pi Pico Launch](https://www.youtube.com/watch?v=o-tRJPCv0GA) - Raspberry Pi Foundation's Pico launch video.
- [BBC Micro Emulation](https://www.youtube.com/watch?v=WaPJmCgseQw) - 'Full-speed high-fidelity BBC Micro emulation on a (slightly) overclocked Raspberry Pi Pico'
- [Geerling Pico Review](https://www.youtube.com/watch?v=dUCgYXF01Do) - YouTuber Jeff Geerling reviews Raspberry Pi Pico.
- [Hackster Pico Unboxing](https://www.youtube.com/watch?v=qHT9UR8MTrE) - Hackster.io partake in a recorded Raspberry Pi Pico unboxing.
- [ETA PRIME Pico First Look](https://www.youtube.com/watch?v=IIBtAQQOZ90) - YouTuber ETA PRIME reviews Raspberry Pi Pico. 
