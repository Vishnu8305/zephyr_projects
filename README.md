# Zephyr Projects – ESP32S3 & STM32

This repository contains my experiments and projects using **Zephyr RTOS** with  
- **Seeed Studio XIAO ESP32S3**, and  
- **STM32 custom boards**  

The projects include standalone examples for each board as well as collaborative setups where ESP32S3 and STM32 communicate under Zephyr.

---

## 📌 Features
- ✅ ESP32S3 Bluetooth (BLE) with **Nordic UART Service (NUS)**
- ✅ GPIO control (LED, sensors, etc.) on ESP32S3
- ✅ STM32 board bring-up with Zephyr
- ✅ Communication workflows between ESP32S3 and STM32
- ✅ Menuconfig-based configuration examples
- ✅ Ready-to-build Zephyr projects
- ✅ SPI Ready sample codes
- ✅ UART Sample codes
- ✅ Menuconfig custom activation codes  

## Codes for the building and flashing to the seed studio esp32s3 microcontroler 
- west build -b xiao_esp32s3/esp32s3/procpu -t menuconfig
- west build -p always -b xiao_esp32s3/esp32s3/procpu
# auto-detects the port
- west flash

# if the port is busy or not auto-detected:
- west flash --esp-device /dev/ttyUSB0       # Linux
- west flash --esp-device COM5               # Windows


---

## 📂 Repository Structure
