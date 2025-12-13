# STM32 Projects Collection

This repository contains a collection of basic to intermediate embedded systems projects developed using **STM32** microcontrollers with **STM32CubeIDE** and **HAL libraries**. Each project is standalone and demonstrates a specific peripheral or concept.

---

## Requirements

* STM32CubeIDE
* Compatible STM32 development board (commonly STM32F1 / STM32F4 series)
* USB programmer/debugger (ST-Link)

---

## Project List

### 1. adcPotentiometer

Reads analog values from a potentiometer using the ADC peripheral.

### 2. adcWaterSensor

Reads analog data from a water/moisture sensor using ADC.

### 3. button1

External push-button input example using GPIO.

### 4. interrupts

Examples of external or timer-based interrupt usage.

### 5. karasimsek

Knight Rider ("Kara Şimşek") LED animation using GPIO outputs.

### 6. ledyakma

Basic LED on/off control using GPIO.

### 7. logicAnalyzer

GPIO timing and signal behavior suitable for logic analyzer inspection.

### 8. mpu6050

I2C communication with MPU6050 accelerometer & gyroscope sensor.

### 9. pwmApplication

PWM signal generation example.

### 10. pwmDCMotor

DC motor speed control using PWM.

### 11. pwmLed

LED brightness control using PWM.

### 12. servoMotor1

Basic servo motor control using PWM.

### 13. servoMotor2

Advanced servo motor control scenarios.

### 14. timers

STM32 timer peripheral usage examples.

### 15. toggle

GPIO pin toggle example.

### 16. uart

UART serial communication (TX/RX) example.

---

## How to Use

1. Open **STM32CubeIDE**
2. Import a project via **File > Import > Existing Projects into Workspace**
3. Check pin assignments and clock configuration
4. Build and flash the project to your STM32 board

---

## Notes

* Projects are intended for educational purposes
* Pin mappings and clock settings may vary depending on the STM32 board
* Main application code can be found in `Core/Src/main.c`

---


