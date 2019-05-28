# STM32F407VGT6_CORE
Core board of STM32F407VGT6 with a CH340 TTL2USB chip, support I2C/SPI/USART and ADC/DAC interface.

## Interface  
- SPI * 2
- I2C * 2
- ADC * 8
- DAC * 2
- USART * 1
- USB * 1
- LED * 2
- KEY * 2

## Resources  
This repository contains a sample project for STM32F407VGT6 core board， a LED is blinking every 2 seconds, and a message "STM32F407VGT6" is printing to the console through CH340G chip.  
The PCB file is also attached.

## Required_softwares  
1. You may need to download STM32CUBE to open the .ioc file, which contains the basic setups for the board. This step is optional as a KEIL project has been provided.  
2. KEIL MDK 5.23.  This software is a IDE for embedded devices development, other IDEs such as IAR should be OK, but you may need to build the project by your self.  
    > NOTE: only version 5.23 is tested, previous version may encounter some problems.  