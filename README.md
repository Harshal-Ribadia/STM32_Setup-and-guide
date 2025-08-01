🛠️ STM32 Firmware Development Portfolio
This repository is a curated collection of embedded firmware projects developed using STM32 microcontrollers. It covers fundamental to intermediate topics in embedded systems development—designed to demonstrate practical skills in GPIO, UART, timers, ADC, PWM, DMA, and more using the STM32 HAL and STM32CubeIDE.

This project was inspired by online learning resources, including the excellent STM32-Tutorial by @mnemocron, and further customized, restructured, and documented for personal learning and professional portfolio purposes.

🔍 What's Inside
Each project folder represents a standalone embedded example:

Folder	Description
01_led_blink_init/	Basic GPIO output for LED blinking
02_uart_tx_rx_debug_console/	UART communication with a PC serial monitor
03_pwm_rgb_led_control/	PWM signals for RGB LED fading
04_adc_temperature_sensor_dma/	ADC sampling via DMA for sensor input

📚 Manuals & References
Each example is paired with:

Setup instructions (.ioc files for STM32CubeMX)

C source and header files (Core/, Drivers/)

Explanatory comments within code

Manuals and notes to aid learning (see /docs/)

⚙️ Tools Used
MCU Family: STM32F401RE (Nucleo Board)

IDE: STM32CubeIDE

HAL Library: STM32Cube HAL Drivers

Debugger: ST-Link v2

Languages: C, STM32Cube auto-gen headers

Host OS: Windows / Linux

📌 Goals
Reinforce embedded systems concepts using STM32

Build a firmware development workflow using STM32CubeIDE and HAL

Demonstrate hands-on skills across key MCU subsystems

Establish a public portfolio for career opportunities in firmware/embedded roles

🧭 Acknowledgments
This project builds on the excellent work by mnemocron, as well as various STM32 learning videos and reference manuals available online. All examples have been customized, expanded, and annotated to match my learning journey and development style.
