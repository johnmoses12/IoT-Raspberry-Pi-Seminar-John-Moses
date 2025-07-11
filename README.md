# 🚀 IoT Using Raspberry Pi – Technical Seminar

This repository contains the technical seminar report and presentation by **E. John Moses (22W95A0405)**, a final-year B.Tech student at Malla Reddy Institute of Engineering and Technology, Hyderabad.

---

## 🎓 Seminar Title:
**Internet of Things (IoT) using Raspberry Pi**

---

## 📚 Table of Contents

| Section | Link |
|--------|------|
| 📘 Seminar Report | [JOHN_SEMINAR.pdf](./JOHN%20SEMINAR.pdf) |
| 📊 Seminar Presentation | [SEMINAR_2.pdf](./SEMINAR%2B2.pdf) |
| 🖼️ Circuit Diagram | See below 👇 |

---

## 🧠 Overview

This seminar explores the role of **Raspberry Pi** in developing IoT systems, focusing on automation using Python and sensors. It covers IoT architecture, GPIO control, MQTT communication, and presents a practical **smart home automation** example that uses a web interface to control a lightbulb remotely.

---

## 🧰 Technologies & Components

- **Hardware**
  - Raspberry Pi 3
  - PIR Motion Sensor
  - DHT11 Temperature/Humidity Sensor
  - Relay Module
  - Light Bulb
- **Programming Language**
  - Python
- **Libraries**
  - `RPi.GPIO`, `Flask`, `paho-mqtt`, `requests`
- **Communication Protocols**
  - MQTT, HTTP
- **Cloud Platforms**
  - AWS IoT, ThingSpeak, Node-RED

---

## 🧪 Example Project: Smart Light Control System

A basic home automation project to remotely control a lightbulb using Raspberry Pi GPIO pins and a Python-Flask web server.

---

### 🖼️ Circuit Diagram

![Smart Home Circuit](./IOT%20circuit.png)

- **DHT11 Sensor**: Measures temperature & humidity.
- **PIR Sensor**: Detects motion.
- **Relay Module**: Switches the light ON/OFF.
- **Web Interface**: Controls the relay using Python + Flask hosted on Raspberry Pi.

---

### 💻 Python Control Script Overview

The `smart_home_control.py` file includes:
- Sensor input reading
- GPIO pin management
- Web UI served through Flask
- Light ON/OFF commands sent through browser interface

#### 🔧 How to Run (on Raspberry Pi):
```bash
sudo python3 smart_home_control.py
