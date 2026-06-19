# 🔥 Fire Detector Alarm Using Arduino Nano

## 📌 Project Description

The Fire Detector Alarm Using Arduino Nano is a safety-based embedded system project designed to detect fire hazards and provide immediate alerts. The system uses a flame sensor to detect infrared radiation emitted by flames. When fire is detected, a buzzer sounds and a red LED glows as a warning signal. During normal conditions, a green LED remains ON, indicating that the system is functioning properly.

This project demonstrates the practical implementation of Arduino-based fire detection systems and can be used in homes, offices, laboratories, industries, and other environments where fire safety is essential.

---

## 🎯 Objectives

* Detect the presence of fire using a flame sensor.
* Provide visual and audible alerts during fire hazards.
* Enhance safety through early fire detection.
* Demonstrate the use of Arduino Nano in real-time monitoring applications.

---

## 🛠️ Components Required

| Component                 | Quantity    |
| ------------------------- | ----------- |
| Arduino Nano              | 1           |
| Flame Sensor Module       | 1           |
| Buzzer                    | 1           |
| Red LED                   | 1           |
| Green LED                 | 1           |
| PCB/Breadboard            | 1           |
| Connecting Wires          | As Required |
| 9V Battery                | 1           |
| USB Cable                 | 1           |
| Computer with Arduino IDE | 1           |

---

## ⚙️ Working Principle

The flame sensor continuously monitors the surrounding area for infrared radiation produced by fire. When a flame is detected:

1. The flame sensor sends a signal to the Arduino Nano.
2. Arduino processes the signal.
3. The Red LED turns ON.
4. The buzzer starts beeping.
5. A fire alert message is displayed on the Serial Monitor.

When no flame is detected:

* Green LED remains ON.
* Red LED remains OFF.
* Buzzer remains OFF.

---

## 🔌 Circuit Connections

| Component           | Arduino Pin |
| ------------------- | ----------- |
| Flame Sensor Output | A0          |
| Red LED             | D2          |
| Green LED           | D3          |
| Buzzer              | D4          |
| VCC                 | 5V          |
| GND                 | GND         |

---

## 🚀 Installation and Setup

1. Install Arduino IDE on your computer.
2. Connect Arduino Nano using a USB cable.
3. Assemble the circuit according to the connection table.
4. Upload the Arduino code.
5. Power the system using a 9V battery.
6. Test the setup using a flame source such as a lighter.

---

## 💻 Features

* Real-time flame detection.
* Audible alarm using buzzer.
* Visual alert through LEDs.
* Compact and low-cost design.
* Easy to build and deploy.
* Low power consumption.

---

## 📊 Results

The Fire Detector Alarm system was successfully implemented and tested. When a flame was introduced near the sensor, the flame sensor detected the fire and sent a signal to the Arduino Nano. The system responded immediately by activating the buzzer and turning ON the red LED.

Under normal conditions, the green LED remained ON and no alarm was triggered. The project effectively demonstrated reliable fire detection and alert generation.

---

## 🌍 Applications

* Residential Buildings
* Commercial Offices
* Industrial Facilities
* Laboratories
* Server Rooms
* Warehouses
* Vehicles
* Educational Projects

---

## ✅ Advantages

* Affordable and easy to implement.
* Fast fire detection response.
* Portable and compact.
* Reliable operation.
* Suitable for beginners learning Arduino.

---

## ⚠️ Limitations

* Detects only visible flames.
* Limited sensing range.
* Sensitive to strong infrared sources.
* Does not measure fire intensity.

---

## 🔮 Future Scope

Future improvements may include:

* GSM module integration for SMS alerts.
* IoT-based remote monitoring using ESP8266.
* Automatic water sprinkler activation.
* Smoke and temperature sensor integration.
* Cloud-based monitoring and data logging.

---

## 📚 Technologies Used

* Arduino Nano
* Embedded C/C++
* Arduino IDE
* Flame Sensor Module
* Basic Electronics

---

## 👨‍💻 Authors

**Prashant Kumar (23CSU244)**
**Prateek Khatana (23CSU246)**

Department of Computer Science & Engineering

---

## 📜 License

This project is developed for educational and learning purposes. Feel free to use and modify it for academic and personal projects.

⭐ If you found this project useful, consider giving it a star on GitHub!
