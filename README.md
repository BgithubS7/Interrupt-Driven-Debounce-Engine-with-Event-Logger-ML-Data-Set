# Interrupt Debounce Engine & Event Logger (with ML Dataset)

## 📖 Overview
This project implements a **debounce engine** for push-button interrupts, paired with an **event logger** for structured dataset generation.  

A push button is used to simulate the noisy transitions typically seen with mechanical switches, transistors, or voltage regulators. The debounce logic filters out spurious edges, while the event logger records reliable press/release events along with timing information.  

The logged data is formatted into a dataset suitable for **machine learning workflows**, enabling training and validation of models on real-world hardware signals.

---

## ✨ Features
- **Interrupt-driven debounce engine**  
  - Handles mechanical switch bounce with configurable debounce times  
- **Event logging**  
  - Records press/release events with timestamps, durations, and raw signal states  
- **Noise filtering**  
  - Prevents false triggers caused by spurious transitions  
- **Dataset generation**  
  - Export logged events as CSV/JSON for downstream ML processing  
- **Hardware-friendly design**  
  - Low-latency, MCU-compatible implementation  

---

## 🛠️ Hardware Setup
- **Microcontroller**: Arduino / ESP32 / STM32 (specify your platform)  
- **Input device**: Push button (simulates a noisy regulator/transistor signal)  
- **Output**: Serial port logging (can be redirected to file for dataset building)  


