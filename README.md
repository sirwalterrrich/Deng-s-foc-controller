# Dengge open source FOC dual-channel brushless motor controller

​ Dengge open source FOC controller is an open source by Dengge, based on [GPL-3.0](https://github.com/ToanTech/Deng-s-foc-controller/blob/master/LICENSE) open source protocol and ESP32 The main control low-cost brushless motor dual-channel FOC drive control board. The total power of the two channels is 240W, and the maximum power of the single channel is 120W. It supports the FOC position, speed and torque open and closed loop control of most gimbal motors. The encoder supports common IIC, ABI, and PWM formats. **Join the online current detection module to realize the real and complete FOC control**. In general, Dengge open source FOC controller is an easy-to -use and cheap dual-channel brushless FOC driver, click to view [effect video](https://www.bilibili.com/video/BV1Hz4y127FL/).

​ The current development of Toan's open-source brushless FOC is deeply supported by the open-source team of Toan, and [Toan's open-source brushless quadruped robot] (https://github.com/ToanTech/py-apple-bldc- quadruped-robot), see DIY videos and effects: [Station B](https://www.bilibili.com/video/BV1kV411i76z/), there will be brushless balance cars, inverted pendulums, etc. Stay tuned as the running example rolls out.

* **Currently, the main control board has been listed on Taobao. It is a finished product that has been welded and debugged. It includes ESP32 when sold**; if you need it, you can click [Taobao link (you can find it in all treasures after entering the store)] ://shop564514875.taobao.com/)

* Open source work is not easy, I hope everyone will click more Stars and more videos with one-click triple link! ! !

![image1](pic/PAFOC_front_v3.jpg)

## 1 Software features (support SimpleFOC library 2.2.1--the latest library)

  As the first team in China to introduce SimpleFOC, we have been working hard to improve the SimpleFOC hardware and make it localized, so that everyone can play with the brushless FOC algorithm at a low price. SimpleFOC is an open source library with powerful support, which can realize open and closed loop torque, speed, and position control of brushless motors. The specific features are as follows:

- **Arduino Based**: Runs on ESP32 Arduino

- **Open Source**: All code and configuration documents can be found at: [SimpleFOC Documentation Page](https://docs.simplefoc.com/)

- **Lightweight**: Compared with drivers such as Odrive, the lighter software structure can help you complete algorithm learning and configuration at high speed

- **Abundant control modes**: open/closed loop speed, position; and open loop torque-based control; two FOC kernel algorithms

- **Graphical configuration software**: The latest DengFOC supports the use of **SimpleFOC Studio** for motor parameter configuration, as shown in the figure below. For configuration methods, please refer to the document PDF

  ![image1](pic/SimpleFOC_Studio.gif)

## 2 Hardware Features

| Description | Parameters |
| ---------------- | -------------------------------- ------------------------------- |
| Dimensions | 56*39 mm |
| Input Voltage Type | Direct Current DC |
| Input voltage | 12-24V |
| Maximum Power | Single 120W Dual 240W |
| Number of supported motors | 2 |
| Main control | The bottom surface is equipped with ESP32 development board lolin32 lite |
| Encoder support | IIC mode, ABI mode, PWM mode encoder (AS5600, AS5047, AS5048, etc.), SPI mode, HALL encoder |
| Expansion interface| Serial port (you can control the FOC board through the serial port) |
| Current Sense Reference Voltage | 3.3V |
| Current detection maximum current | 3.3A |

## 3 Community

This FOC board community is a Q group, welcome to join: **Open source FOC brushless driver exchange group light brother open source group number 778255240 (1 group) 735755513 (2 group)**

Any usage questions and DIY questions will be directly discussed and answered here

## 4 Project file description

* Dengs FOC V3.0 DIY materials: BOM, schematic diagram, PCB, Gerber
* Dengs FOC V3.0 test routine: 21 open-loop, closed-loop and application test videos of Dengs open-source FOC
*Dengge open source FOC use document PDF: **Detailed configuration method and usage tutorial**

## 5 DengFOC supporting application practice project

Interesting brushless motor practice projects made with DengFOC:

[1 Momentum wheel inverted pendulum project, applied to DengFOC after low cost and miniaturization](https://github.com/ToanTech/Inverted_Pendulum_DengFOC)

[2 Self-balancing DengFOC Lailuo triangle](https://github.com/ToanTech/Lailuo_DengFOC)

[3 Self-balancing DengFOC brushless balance car](https://github.com/ToanTech/Balance_Bot_DengFOC)

[4 Brushless quadruped robot dog with parallel legs based on DengFOC](https://github.com/ToanTech/py-apple-bldc-quadruped-robot)