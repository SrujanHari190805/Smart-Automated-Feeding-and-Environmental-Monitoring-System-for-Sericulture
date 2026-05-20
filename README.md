# 🐛 Smart Automated Feeding & Environmental Monitoring System for Sericulture

> **Patent Application In Progress**

An automated sericulture management system that eliminates manual intervention in silkworm feeding cycles through multi-parameter environmental sensing, image-assisted monitoring, and microcontroller-based closed-loop control.

---

## 📌 Problem Statement

Traditional sericulture (silk farming) relies entirely on manual feeding and environmental monitoring — a labor-intensive, error-prone process. Silkworms are highly sensitive to environmental conditions; even small deviations in temperature, humidity, or CO₂ levels can significantly reduce cocoon yield and silk quality.

---

## 💡 Solution

An intelligent, automated system that monitors the sericulture environment in real time, uses image-assisted monitoring to assess feeding status, and autonomously regulates feeding schedules and environmental conditions — maintaining consistent, optimal habitat quality for silkworms without human intervention.

---

## 🏗️ System Architecture

```
[Environmental Sensors]
   ├── Temperature Sensor
   ├── Humidity Sensor
   └── CO₂ Sensor
         │
[Image Capture Module]
   └── Camera (leaf coverage / feeding status)
         │
   [ESP32 Microcontroller]
         │
   ├── Real-time sensor data processing
   ├── Image-assisted feeding status evaluation
   ├── Automated feeding mechanism control
   └── Environmental regulation (fan, heater, humidifier)
         │
   [Actuators]
   ├── Automated Feeding Mechanism (novel design)
   ├── Ventilation / Fan Control
   └── Humidity Regulation
```

---

## ⚙️ Hardware Stack

| Component | Purpose |
|---|---|
| ESP32 | Main microcontroller |
| DHT22 / SHT31 | Temperature & humidity sensing |
| MH-Z19 CO₂ Sensor | Carbon dioxide monitoring |
| Camera Module (OV2640) | Image-assisted leaf coverage monitoring |
| Servo / Stepper Motor | Automated feeding mechanism actuation |
| Relay Module | Fan, heater, humidifier control |

---

## 💻 Firmware Overview

- **Language:** Embedded C (ESP32)
- Real-time multi-sensor data acquisition
- Threshold-based environmental regulation loop
- Image capture and basic processing for feeding status detection
- Automated feeding trigger based on time + visual cues
- Logging and alert system

---

## 🌱 Environmental Control Loop

```
Sense (Temp / Humidity / CO₂)
        ↓
Compare against optimal thresholds
        ↓
Actuate (Fan / Heater / Humidifier)
        ↓
Re-sense → Closed feedback loop
```

---

## 🍃 Automated Feeding Mechanism

A novel mechanised feeding design (patent pending) that:
- Dispenses fresh mulberry leaves on a programmed schedule
- Adjusts quantity based on silkworm growth stage
- Uses image-based feedback to verify leaf coverage
- Eliminates the need for manual feeding intervention

> ⚠️ **Note:** Specific mechanical design details are withheld pending patent filing.

---

## 📊 Key Outcomes

- Eliminated manual intervention in feeding cycles
- Maintained consistent habitat quality across rearing cycles
- Novel automated feeding mechanism validated through testing
- Patent application filed for the feeding mechanism design

---

## 🚧 Status

- [x] System designed and prototyped
- [x] Environmental monitoring validated
- [x] Automated feeding mechanism tested
- [x] Patent application in progress (2024–Present)
- [ ] Field deployment at sericulture farm (upcoming)

---

## 👤 Author

**Sri Srujan Hari T**
B.E – Electronics & Communication Engineering, BMSIT&M
[LinkedIn](https://www.linkedin.com/in/srujan-hari-undefined-1a7364399) | thammineedisrujanhari@gmail.com
