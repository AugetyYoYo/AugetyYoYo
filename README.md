### 张志刚 ｜ 嵌入式开发

8051 / Cortex-M4 / ESP32-C3·S3 —— 从器件选型、电源树、原理图、多层 PCB 到固件，独立走完完整流程。

| 项目 | 概要 |
|---|---|
| **[便携式多参数环境监测仪](https://github.com/AugetyYoYo/YoYo-Environmental-Monitor)** | STC8H8K64U（8051）· 四层板 75×75 mm · 6 路传感器 + RS485 Modbus 主站 + GPS 授时 + TF 记录 · 固件 code 51 KB / 64 KB · 已开源 |
| **[USB-PD + CAN 双总线分析仪](https://github.com/AugetyYoYo/YoYo-USBPD-CAN-Analyzer)** | GD32F407VET6 + ESP32-C3 · 六层板 100×100 mm + 独立负载子板 · FUSB302B（TCPC）+ INA228 · DRC 0 违规 · 已打样 |

**技术栈**

`C` · `Keil C51` · `ARM GCC + CMake` · `ESP-IDF` · `I²C / SPI / UART / ADC / DMA` · `EXMC 8080` · `SDIO` · `Modbus RTU` · `CAN / CAN-FD` · `USB-PD 3.x` · `FreeRTOS`

📮 AugetyYoYo@gmail.com