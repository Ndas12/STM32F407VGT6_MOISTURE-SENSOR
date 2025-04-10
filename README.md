# 🌱 STM32F407VGT6 Soil Moisture Monitoring via ADC1

![image](https://github.com/user-attachments/assets/8cd1159b-c0ef-4aa6-be31-058799edd02e)

This project demonstrates how to interface a soil moisture sensor with the STM32F407VGT6 microcontroller using the ADC1 peripheral. The goal is to measure and display the moisture percentage in soil, making it ideal for precision agriculture, garden automation, or educational purposes.

# 📦 Features

Reads analog data from a soil moisture sensor connected to ADC1.

Converts raw ADC values to moisture percentage (0–100%).

Configurable ADC sampling settings for accurate readings.

Lightweight and efficient codebase for real-time applications.

# 🔌 Hardware Setup

**MCU:** STM32F407VGT6 (on STM32F4 Discovery or custom board)

**Sensor:** Analog soil moisture sensor (e.g., YL-69 or similar)

# Connections:

Sensor analog output → STM32 ADC1 channel pin (e.g., PA1)

Sensor VCC → 3.3V

Sensor GND → GND
