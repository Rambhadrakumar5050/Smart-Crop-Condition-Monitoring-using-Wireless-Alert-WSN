# Smart Crop Condition Monitoring using Wireless Sensor Networks (WSN)

## 🌱 Project Overview

This project presents a Smart Crop Condition Monitoring System developed using concepts of Wireless Sensor Networks (WSN) and embedded systems for precision agriculture applications.

The system continuously monitors:

- Soil Moisture
- Temperature
- Humidity

using sensors connected to an Arduino Uno microcontroller. Real-time readings are displayed on a 16x2 LCD display, while alert mechanisms such as LEDs and buzzers notify users whenever environmental conditions cross predefined thresholds.

The project demonstrates how low-cost embedded hardware can help farmers improve irrigation efficiency, reduce water wastage, and monitor crop conditions automatically.

---

# 📌 Features

- 🌡 Real-time Temperature Monitoring
- 💧 Soil Moisture Detection
- ☁ Humidity Measurement
- 📟 LCD Display Output
- 🔔 Buzzer Alert System
- 💡 LED Warning Indicators
- 🌾 Dry Soil Detection
- 🔌 Arduino-based Embedded System
- 📡 WSN-based Architecture Design
- 🧪 Physical Hardware Prototype + Tinkercad Simulation

---

# 🛠 Hardware Components

| Component | Purpose |
|---|---|
| Arduino Uno | Main microcontroller |
| Soil Moisture Sensor | Measures soil water content |
| DHT11 Sensor | Temperature & humidity sensing |
| 16x2 LCD Display | Displays sensor readings |
| Potentiometer | LCD contrast adjustment |
| LED | Visual alert |
| Buzzer | Audio alert |
| Breadboard | Circuit assembly |
| Jumper Wires | Connections |
| USB Cable | Power and programming |

---

# 💻 Software & Tools Used

- Arduino IDE
- Tinkercad Circuit Simulator
- Embedded C / Arduino Programming
- LiquidCrystal Library
- DHT Sensor Library
- LaTeX (IEEE Research Paper)

---

# ⚙️ Working Principle

The system continuously collects environmental data using sensors:

1. Soil Moisture Sensor measures moisture level in soil.
2. DHT11 Sensor reads temperature and humidity.
3. Arduino processes sensor values.
4. Readings are displayed on the LCD screen.
5. If moisture becomes too low or temperature becomes too high:
   - LED turns ON
   - Buzzer activates
6. Future wireless expansion using nRF24L01 modules is planned.

---

# 🧠 System Architecture

```text
Sensors → Arduino Uno → LCD Display
                     → LED Alert
                     → Buzzer Alert
                     → Wireless Module (Future Scope)
```

---

# 📊 Experimental Results

The prototype was tested using dry soil samples under room conditions.

### Observations:
- Soil moisture readings consistently detected dry soil.
- LCD updated readings every 2 seconds.
- Buzzer and LED alerts triggered correctly.
- Temperature and humidity readings remained stable.
- No firmware crashes were observed during testing.

---

# 📷 Project Images

## Physical Prototype

```markdown
![Prototype](Images/photo_setup.jpg)
```

## Breadboard Circuit

```markdown
![Circuit](Images/photo_circuit.jpg)
```

## Tinkercad Simulation

```markdown
![Simulation](Images/photo_tinkercad.jpg)
```

---

# 🚀 Future Enhancements

- 📡 Wireless Communication using nRF24L01
- 💦 Automatic Irrigation System
- 📲 GSM SMS Alerts
- ☁ IoT Cloud Dashboard
- 🌧 Rain Detection Sensor
- 🔋 Solar Powered System
- 📈 Data Logging & Analytics
- 🤖 Machine Learning for Yield Prediction
- 🌍 Multi-node WSN Deployment

---

# 📂 Repository Structure

```text
Smart-Crop-Condition-Monitoring/
│
├── Arduino_Code/
│   └── smart_crop_monitoring.ino
│
├── Images/
│   ├── photo_setup.jpg
│   ├── photo_circuit.jpg
│   └── photo_tinkercad.jpg
│
├── Research_Paper/
│   └── IEEE_Paper.pdf
│
├── Simulation/
│   └── tinkercad_design.png
│
├── README.md
└── LICENSE
```

---

# ▶️ How to Run the Project

## Hardware Setup
- Connect all sensors to Arduino Uno as per circuit diagram.
- Upload Arduino code using Arduino IDE.
- Power the board through USB.

## Software Setup

1. Install Arduino IDE
2. Install:
   - DHT Library
   - LiquidCrystal Library
3. Open `.ino` file
4. Upload to Arduino Uno

---

# 📚 Research Domain

- Wireless Sensor Networks (WSN)
- Smart Agriculture
- Precision Farming
- Embedded Systems
- IoT-based Farming
- Environmental Monitoring

---

# 👨‍💻 Authors

### Ch. Rambhadra Kumar
Department of Computer Science and Engineering  
Indian Institute of Information Technology Vadodara

### Annepu Adarsh
Department of Computer Science and Engineering  
Indian Institute of Information Technology Vadodara

### Ch. Punyamurthy
Department of Computer Science and Engineering  
Indian Institute of Information Technology Vadodara

---

# 🙏 Acknowledgment

We sincerely thank the faculty of the Wireless Sensor Networks (CS314) course at IIIT Vadodara for their guidance and support throughout the development of this project.

---

# 📄 License

This project is developed for academic and educational purposes. Feel free to use and modify it with proper credits.

---

# ⭐ If you like this project

Give this repository a ⭐ on GitHub and support the project!
