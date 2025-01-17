﻿# [PY32F0xx](https://www.soc.xin/PY32F002)

[![Build Status](https://github.com/SoCXin/PY32F002/workflows/templates/badge.svg)](https://github.com/SoCXin/PY32F002/actions/workflows/templates.yml)
[![Build Status](https://github.com/SoCXin/PY32F002/workflows/docs/badge.svg)](https://www.soc.xin/PY32F002)

* [PuyaSemi](https://www.puyasemi.com/): [Cortex-M0+](https://github.com/SoCXin/Cortex)
* [L1R1](https://github.com/SoCXin/Level): 24 MHz , [￥0.52 (SOP8)](https://item.szlcsc.com/6036161.html)

## [简介](https://github.com/SoCXin/PY32F002/wiki)

仓库资源可应用于PY32F0xx系列MCU，包括PY32F030、PY32F003和PY32F002A，主要以高性价比的PY32F002A为主。

[PY32F002A](https://www.puyasemi.com/cpzx3/info_267_aid_242_kid_235.html) 系列微控制器采用高性能的 32 位 ARM® Cortex®-M0+内核，宽电压工作范围的 MCU。嵌入高
达 20Kbytes flash 和 3Kbytes SRAM 存储器，最高工作频率 24MHz。包含多种不同封装类型多款产品。芯片集成多路 I2C、SPI、USART 等通讯外设，1 路 12bit ADC，多个定时器。

PY32F002A系列微控制器的工作温度范围为-40℃-85℃，工作电压范围 1.7V-5.5V。芯片提供 sleep 和 stop 低功耗工作模式，可以满足不同的低功耗应用。

### 关键参数

* 24 MHz [Cortex-M0+](https://www.soc.xin/Cortex-M0)
* 3KB SRAM + 20KB Flash
* USART + SPI + I2C
* 12-bit ADC (9ch)
* 封装规格：SOP8/ESSOP10/SOP16/QFN16/TSSOP20

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [工程模板](templates/)

提供跨平台编译工具[platform-puya](https://github.com/OS-Q/platform-puya)，[PY32F002A](https://www.soc.xin/PY32F002)非常适用于低成本控制器方案[Modbus RTU Slave](https://www.os-q.com/qio/templates/rtu)

## [选型建议](https://github.com/SoCXin/PY32F002)

普冉半导体[PuyaSemi](https://www.puyasemi.com/)是低功耗SPI NOR Flash存储器芯片和高可靠性IC EEPROM存储器芯片的供应商

* PY32F002A
  * PY32F002Ax5(20KB Flash/3KB RAM)
* PY32F003
  * PY32F003x4(16KB Flash/2KB RAM), PY32F003x6(32KB Flash/4KB RAM), PY32F003x8(64KB Flash/8KB RAM)
* PY32F030
  * PY32F030x4(16KB Flash/2KB RAM), PY32F030x6(32KB Flash/4KB RAM), PY32F030x7(48KB Flash/6KB RAM), PY32F030x8(64KB Flash/8KB RAM)

[PY32F002A](https://www.soc.xin/PY32F002)极低成本flash MCU，也是目前最便宜的Cortex-M0芯片，该系列包括：

* [PY32F002AL15S6TU (SOP8,￥0.52)](https://item.szlcsc.com/6036161.html)
* [PY32F002AA15M6TU (ESSOP10,￥0.57)](https://item.szlcsc.com/6036159.html)
* [PY32F002AW15U6TR (QFN16,￥0.72)](https://item.szlcsc.com/6035786.html)
* [PY32F002AF15P6TU (TSSOP20,￥0.75)](https://item.szlcsc.com/6036160.html)

作为对比[STM32G030 TSSOP20(￥2.56)](https://item.szlcsc.com/769428.html)，PY32F002A之上的MCU产品还包括PY32F003系列：

* [PY32F003L16S6TU (SOP-8,￥1.07)](https://item.szlcsc.com/5732433.html)
* [PY32F003L24D6TR (DFN-8,￥1.18)](https://item.szlcsc.com/5732434.html)
* [PY32F003W16S6TU (SOP-16,￥0.86)](https://item.szlcsc.com/5732435.html)

以及PY32F030系列：

* [PY32F030K28U6TR (QFN32,￥2.59)](https://item.szlcsc.com/3531932.html)
* [PY32F030K28T6 (LQFP32,￥2.62)](https://item.szlcsc.com/3531934.html)

目前，PY32F0xx的其他系列性价比不及PY32F002A(<￥1.0)，而TSSOP20以内封装超过￥2.0的选择范围很广，例如[CH32V003](https://github.com/SoCXin/CH32V003)

* 在￥3.0段当下首推[CH32V203 (LQFP-48,￥2.86)](https://github.com/SoCXin/CH32V203)
* 在￥5.0段当下超值[N32G430 (LQFP-48,￥4.5)](https://github.com/SoCXin/N32G430)，[RP2040 (QFN-56,￥4.3)](https://github.com/SoCXin/RP2040)

### 开源项目

* [py32f0-template](https://github.com/IOsetting/py32f0-template)

