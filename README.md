# EMG Device to Measure Potential of Biceps Brachii

## Project Overview
The objective of this project was to design and implement an EMG system capable of detecting muscle contraction and relaxation in real time. The system includes hardware and software-based data visualization and analysis. 

Three key phases:
1. **EMG Signal Acquisition**
2. **Arduino Interfacing**
3. **LabView Signal Analysis**
---
## System Design

### Hardware Components
- **Electrodes:** Surface EMG electrodes for biceps brachii signal acquisition  
- **Signal Conditioning Circuit:**
  - Differential amplifier to remove common-mode noise  
  - Inverting amplifier for signal scaling  
  - High-pass filter (removes motion artifacts)  
  - Low-pass filter (reduces high-frequency noise)  
  - Full-wave rectifier for envelope extraction  
- **Microcontroller:** Arduino for analog-to-digital conversion and data transmission  
- **Power Supply:** Dual ±5V or ±9V regulated power source  

---

### Software Components
- **Arduino IDE:** For data acquisition and threshold-based detection of muscle contraction  
- **LabVIEW:** For real-time signal visualization and analysis
