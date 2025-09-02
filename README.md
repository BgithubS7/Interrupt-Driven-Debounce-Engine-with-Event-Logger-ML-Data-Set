# 🚦 Interrupt Debounce Engine & Event Logger (with ML Dataset)

## 📖 Overview
Mechanical switches and regulators often generate **bouncy, noisy transitions** when toggled.  
This project implements an **interrupt-driven debounce engine** with an integrated **event logger** that:

- Cleans up noisy edges in real time  
- Logs press/release events with precise timestamps and durations  
- Formats data into **ML-ready datasets (CSV/JSON)**  

It demonstrates **end-to-end system design**: from hardware signals ➝ embedded firmware ➝ structured dataset ➝ ML pipeline.

---

## ✨ Features
- ⚡ **Interrupt-driven debounce logic** (configurable delay)  
- 📝 **Event logging engine** (timestamp, duration, state)  
- 🔊 **Noise filtering** (filters spurious edges)  
- 📊 **Dataset generation** (export as CSV/JSON)  
- 💻 **Portable firmware** (Arduino, ESP32, STM32 compatible)  

---

## 🛠️ Hardware Setup
- **MCU**: Arduino Uno (beginner friendly), ESP32 (Wi-Fi logging), STM32 (advanced)  
- **Input**: Push button (simulates noisy transitions)  
- **Output**: Serial logging to PC  

### CIRCUIT
<img width="315" height="237" alt="Image" src="https://github.com/user-attachments/assets/327a3db4-5070-4436-8c1e-bb4f34f46942" />
