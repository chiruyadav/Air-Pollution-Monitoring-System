# 🌍 Air Pollution Monitoring System

An **IoT-based Air Pollution Monitoring System** developed using **ESP32 and multiple gas sensors** to monitor environmental air quality in real time.
The system measures different gas concentrations and temperature, displays the data on an LCD screen, and sends it to **IoT cloud platforms** for remote monitoring.

---

## 🚀 Features

* 📡 Real-time air quality monitoring
* 🌡 Temperature measurement using LM35 sensor
* 📟 LCD display for local monitoring
* 📱 Mobile monitoring using **Blynk IoT**
* ☁ Cloud data storage using **ThingSpeak**
* 🚨 Alert system using **buzzer and LEDs**
* 📊 AQI calculation for pollution analysis

---

## 🛠 Hardware Components

* ESP32 Development Board
* ADS1115 16-bit ADC Module
* MQ135 Air Quality Sensor
* MQ6 LPG Gas Sensor
* MQ7 Carbon Monoxide Sensor
* LM35 Temperature Sensor
* 16×2 LCD Display with I2C Module
* Buzzer
* LED Indicators
* Power Supply

---

## 💻 Software Used

* Arduino IDE
* Blynk IoT Platform
* ThingSpeak Cloud Platform
* Embedded C Programming

---

## ⚙ System Architecture

The sensors detect different air pollutants present in the environment.
The **ADS1115 ADC module** converts analog sensor signals into digital values that are processed by the **ESP32 microcontroller**.

The ESP32 performs the following tasks:

1. Reads sensor values
2. Calculates pollution levels
3. Displays data on LCD screen
4. Sends data to IoT platforms for remote monitoring

---

## 📊 IoT Dashboard

* **Blynk Mobile App** – Real-time monitoring
* **ThingSpeak** – Data logging and visualization

*(Upload dashboard screenshots in the images folder and show them here)*

---

## 🌐 Applications

* Smart City Air Monitoring
* Industrial Pollution Monitoring
* Indoor Air Quality Monitoring
* Environmental Research

---

## 📚 Future Improvements

* Integration with **AI-based pollution prediction**
* Web dashboard for real-time visualization
* SMS alert system for dangerous pollution levels

---

## 👨‍💻 Author

**Prashanth C**
Electronics and Communication Engineering
Bangalore Institute of Technology

GitHub: https://github.com/chiruyadav
