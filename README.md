# 📡 IR Sensor – Infrared Detection & Object Sensing
## 📌 Overview
Infrared (IR) sensors are widely used for object detection, proximity sensing, obstacle avoidance, and automation systems. These sensors operate using infrared radiation to detect the presence or movement of nearby objects.
This repository focuses on the working principle, internal architecture, ESP32 interfacing, signal behavior, and engineering applications of IR sensors.
## 🧠 Working Principle
IR sensors work based on the transmission and reception of infrared radiation.
The transmitter emits infrared light, while the receiver detects reflected infrared waves from nearby objects.
### 🔹 Detection Logic:
* Object detected → Reflected IR received
* No object → No reflected IR detected
## ⚙️ Internal Components
An IR sensor module generally consists of:
* IR LED transmitter
* Photodiode / phototransistor receiver
* Comparator circuit
* Sensitivity adjustment potentiometer
## 🔌 Signal Behavior
IR sensors usually provide digital output.
### 🔹 Output States:
* LOW → Object detected
* HIGH → No object detected
The output depends on reflected infrared intensity.
## 📡 ESP32 Interfacing
The IR sensor output pin can be connected directly to ESP32 GPIO pins.
### 🔹 Flow:
* IR emitted
* Reflection detected
* Signal sent to ESP32
* ESP32 processes input
* Automation action triggered
## 🌐 IoT Integration
ESP32 enables IR-based systems to become part of IoT networks.
### 🔹 Applications:
* Smart obstacle detection
* Automatic door systems
* Conveyor object counting
* Home automation systems
## 🧩 Design Considerations
### 🔹 Important Points:
* Avoid direct sunlight interference
* Adjust sensitivity properly
* Ensure proper alignment
* Maintain stable power supply
## ⚠️ Limitations
* Limited sensing distance
* Affected by ambient infrared noise
* Performance varies with object surface properties
