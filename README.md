Project Overview

This module is built around the SPIN FV1 DSP audio processor, tailored for audio effect processing across guitar pedals, Eurorack modular systems, and synthesizer projects.

Hardware Features

· Onboard 24LC32 EEPROM supporting up to 8 effect presets—a socket is recommended for easy replacement or future upgrades
· Integrated power regulation accepting +5V to +12V DC input, delivering stable 3.3V output
· L/R dual-channel inputs and outputs (stereo)
· P0, P1, P2: Three parameter control inputs (analog/potentiometer)
· S0, S1, S2: Address selection inputs for EEPROM preset switching
· S3: Reserved pin, recommended left unconnected

EEPROM Programming

· A CH341 programmer is recommended for burning code to the 24LC32 EEPROM
· An IC socket footprint is provided on the board—soldering a socket instead of the EEPROM directly is recommended, allowing for easy hot-swapping of EEPROM chips

Open-Source & Usage

· Hardware: Open-sourced under CERN-OHL-P-2.0, allowing modification and commercial use. Derivatives must credit "Based on EAR Modular."
· Firmware: Fully custom-developed, hosted separately on GitHub under MIT license. Users can burn their own effect programs.
· PCB: Three backplate pattern options available. Customer code position is pre-marked on the PCB for JLC fabrication.

🔗 PCB Repository: 

HEX file: This is an effect file for the re-effect pedal, provided in hex format and ready to be flashed directly. It’s compatible with any effect processor based on the Spin FV-1 DSP chip. The file includes 5 reverb effects and 3 delay effects, and the code was entirely written by Ear Modular.


项目概述

本模块基于 SPIN FV1 DSP 音频处理器构建，专为音频效果处理场景设计，可灵活应用于吉他效果器、Eurorack 模块化系统及各类合成器项目。

硬件特性

· 板载 24LC32 EEPROM，最多支持 8 组效果代码存储，建议搭配芯片座使用，方便后续更换或升级 EEPROM
· 集成电源转换电路，支持 +5V 至 +12V 宽电压输入，提供稳定的 3.3V 输出
· L/R 双声道输入与输出（立体声）
· P0、P1、P2：三组参数控制输入（模拟/电位器）
· S0、S1、S2：寻址输入，用于切换 EEPROM 中的效果预设
· S3：预留引脚，建议悬空

EEPROM 烧录说明

· 推荐使用 CH341 编程器 配合相应软件对 24LC32 进行代码烧录
· 板上预留了芯片座位置，建议直接焊接芯片座而非 EEPROM 本体，便于后续拔插更换

开源与使用说明

· 硬件：采用 CERN-OHL-P-2.0 协议开源，允许修改与商业使用，二创时请注明“Based on EAR Modular”
· 固件：完全自主开发，于 GitHub 独立发布，采用 MIT 协议，用户可自行烧录自定义效果
· PCB：提供三种背板图案供选择，已标注客编（Customer Code）添加位置，使用嘉立创（JLC）制板时可按标注指定位置添加

🔗 PCB地址：

HEX文件：这是用于re-effect效果器的效果文件，hex格式可以直接烧录。该文件可用于任何spin-fv1 DSP芯片为基础的效果器。包含5个reverb效果和3个delay效果。完全由ear modular编写。
