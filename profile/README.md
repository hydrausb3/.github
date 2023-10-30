HydraUSB3 main repository
========

Welcome to HydraUSB3 project main repository

![HydraUSB3 V1 board](HydraUSB3_V1_board.jpg)

Official detailed specification about HydraUSB3 v1 devkit is available online: https://hydrabus.com/hydrausb3-v1-0-specifications

You can Buy HydraUSB3 online: http://hydrabus.com/buy-online

Wiki for HydraUSB3 test firmware / examples: https://github.com/hydrausb3/hydrausb3_fw/wiki

Join Official HydraUSB3 Discord Server: https://discord.gg/6DCVURV5c2

For HydraDancer dedicated organisation: https://github.com/HydraDancer

### HydraUSB3 repositories

#### Hardware
- https://github.com/hydrausb3/hydrausb3_hw
  - [hydrausb3_hw](https://github.com/hydrausb3/hydrausb3_hw) repository contains details about HydraUSB3 V1 devkit

#### RISC-V open source toolchain
- https://github.com/hydrausb3/riscv-none-elf-gcc-xpack
  - Open source RISC-V toolchain for WCH CH56x (thanks to David Carne / davidcarne on GitHub) 
    - Based on xPack GNU RISC-V Embedded GCC v12.2.0-1 with support of WCH RISCV CH56x... "WCH-Interrupt-fast"
  - See Pre-built toolchain for Linux/Windows on https://github.com/hydrausb3/riscv-none-elf-gcc-xpack/releases/tag/12.2.0-1

#### Firmware
- https://github.com/hydrausb3/hydrausb3_fw 
  - [hydrausb3_fw](https://github.com/hydrausb3/hydrausb3_fw) repository contains open source test firmware / examples for HydraUSB3 v1 devkit using WCH CH569 MCU
- https://github.com/hydrausb3/wch-ch56x-bsp
  - [wch-ch56x-bsp](https://github.com/hydrausb3/wch-ch56x-bsp) repository contains open source code for WCH CH565/CH569 BSP with libraries(mainly drivers) mainly used for HydraUSB3 v1 Hardware.

#### Host tools
- https://github.com/hydrausb3/wch-ch56x-isp
  - [wch-ch56x-isp](https://github.com/hydrausb3/wch-ch56x-isp) is a open source small utility(Windows/Linux) to program WCH CH56x micro-controllers over USB (using WCH56x ISP bootloader).
- https://github.com/hydrausb3/hydrausb3_host
  - [hydrausb3_host](https://github.com/hydrausb3/hydrausb3_host) repository contains open source host tools (for Linux & Windows)
  - The aim is to use host tools with [hydrausb3_fw](https://github.com/hydrausb3/hydrausb3_fw) USB Examples (mainly related to USB2 or USB3 examples)

#### Reverse engineering materials related to HydraUSB3 v1 (WCH CH569)
- https://github.com/hydrausb3/wch-ch569-serdes
  - [wch-ch569-serdes](https://github.com/hydrausb3/wch-ch569-serdes) repository contains details about WCH CH569 SerDes to interface it with FPGA... 

