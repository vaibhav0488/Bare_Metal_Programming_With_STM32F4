# Bare_Metal_Programming_With_STM32
This repository contains a collection of bare-metal embedded firmware projects developed for STM32 microcontrollers using STM32CubeIDE. The projects were implemented while completing the course Embedded Systems Bare-Metal Programming Ground Up™ (STM32).

The goal of this repository is to demonstrate how embedded firmware can be developed directly at the hardware register level without relying on external libraries or hardware abstraction layers (HAL). Instead of using pre-built drivers, each peripheral driver and firmware component is developed from scratch using bare-metal embedded C and direct memory-mapped register manipulation.

These projects focus on building a deep understanding of ARM Cortex-M microcontroller architecture, CMSIS standards, and low-level peripheral programming. The implementations follow a professional embedded development workflow that involves reading the microcontroller datasheet and reference manual to identify peripheral addresses, create registers, and write firmware drivers manually.

Key Concepts Demonstrated

ARM Cortex-M microcontroller architecture
1.  Memory-mapped register programming
2.  Peripheral address definition and register creation
3.  CMSIS (Cortex Microcontroller Software Interface Standard) fundamentals
4.  GPIO driver development
5.  UART communication driver
6.  SPI and I2C peripheral drivers
7.  ADC (Analog-to-Digital Converter) driver implementation
8.  Timer and SysTick configuration
9.  Interrupt handling using NVIC
10. DMA driver development
11. Debugging embedded firmware using STM32 development tools

These projects help build a strong foundation in embedded firmware development, enabling developers to understand how microcontroller peripherals operate internally and how drivers are implemented in real embedded systems. The repository can serve as a learning resource for students, embedded developers, and anyone interested in low-level microcontroller programming using STM32 devices.
