# Arduino & ESP32 Projects Collection

A comprehensive collection of over 40 Arduino and ESP32 projects, ranging from basic LED blinking to complex robotics and sensor integrations. This repository serves as a learning resource and a portfolio of embedded systems applications.

## 🚀 Project Categories

### 🤖 Robotics & Automation
* **Automatic Car Parking & Toll Gate**: Managed system for vehicle entry and parking.
* **Bluetooth Controlled Car**: Smartphone-controlled vehicle using Arduino and HC-05.
* **IR Remote Controlled Car**: Vehicle navigation using standard IR remotes.
* **Smart Dustbin**: Motion-triggered automated trash can.
* **Fingerprint Attendance System**: Biometric attendance logging with RTC support.
* **Line Follower/Forward Robot**: Autonomous navigation using IR sensors.

### 🌡️ Sensors & Measurement
* **Environment Monitoring**: BMP280 for temperature, pressure, and altitude.
* **Health Tech**: Blood Oxygen and Heart Rate measurement with MAX30100.
* **Gas Detection**: Gas leakage monitoring using MQ-2 and MQ-5 sensors (Arduino/ESP32).
* **Motion Tracking**: 6-axis accelerometer and gravity sensing with BMI160.
* **Digital Compass**: Heading and magnetic field detection using HMC5883L.
* **Water Level Management**: IoT-based water level monitoring for ESP32 and ESP8266.
* **Security**: PIR motion detection with audible buzzer alarms.

### 📺 Displays & Graphics
* **OLED & TFT Graphics**: Advanced graphics benchmarks and demos using U8g2 and Adafruit libraries.
* **LCD Interfaces**: I2C-based 16x2 and 20x4 character displays.
* **Legacy Displays**: Interfacing with Nokia 5110 (PCD8544) monochrome screens.
* **Matrix Displays**: LED dot matrix control and animations.

### ⚙️ Basic Components & IO
* **Input Handling**: Matrix keypads, pushbuttons, and IR receivers.
* **Actuators**: Precision control of Servo and DC Gear motors.
* **Visuals & Audio**: Traffic light simulations, multiple LED patterns, and a mini buzzer piano.
* **Timekeeping**: Real-time clock (RTC) implementations for scheduled tasks.

## 🛠️ Hardware Stack
* **Microcontrollers**: Arduino Uno, ESP32 DevKit, NodeMCU (ESP8266).
* **Communication**: I2C, SPI, UART, Bluetooth, Infrared.
* **Key Components**: SSD1306 OLED, HC-SR04 Ultrasonic, MAX30100, BMP280, L298N Motor Driver, DS1302 RTC.

## 💻 Getting Started

### Prerequisites
1. Install [Arduino IDE](https://www.arduino.cc/en/software).
2. Install necessary board cores (ESP32 by Espressif, ESP8266 by ESP8266 Community).
3. Install required libraries via the Arduino Library Manager:
   * `Adafruit_BMP280`
   * `U8g2`
   * `LiquidCrystal_I2C`
   * `Adafruit_Fingerprint`
   * `MAX30100_PulseOximeter`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/[username]/[repo-name].git
   ```
2. Navigate to the specific project folder.
3. Open the `.ino` sketch in Arduino IDE.
4. Select your board and COM port.
5. Compile and **Upload**.

## 📝 License
This project is for educational purposes. Feel free to use and adapt the code for your own projects.
