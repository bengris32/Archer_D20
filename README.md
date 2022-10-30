# Archer D20 Research
This repo aims to provide information about the TP-Link Archer D20 Modem Router.
The stock firmware runs a version of OpenWRT with kernel version 2.6

## Getting UART
The UART pins on the board are not clearly labeled. Use this image as reference.

![Archer D20 UART](img/uart.jpg)

Use the following table to connect to a UART adapter

| Router | UART Adapter |
| ------ | ------------ |
| TX     | RX           |
| RX     | TX           |
| GND    | GND          |
| VCC    | DONT CONNECT |

## Useful References
[Stock Firmware](https://static.tp-link.com/res/down/soft/Archer_D20_V1_150728.zip)  
[GPL Code](https://static.tp-link.com/resources/gpl/ArcherD20v1_GPL.tar.gz)
