# EMG-device-to-measure-potential-of-biceps-brachii
Project Overview

The goal of this project was to design and implement a low-cost EMG acquisition system capable of detecting muscle contraction and relaxation in real-time. The device includes both hardware signal conditioning and software-based data visualization and analysis.

System Design
Hardware Components

Electrodes: Surface EMG electrodes for biceps brachii signal acquisition

Signal Conditioning Circuit:

Differential amplifier to remove common-mode noise

Inverting amplifier for signal scaling

High-pass filter (removes motion artifacts)

Low-pass filter (reduces high-frequency noise)

Full-wave rectifier for envelope extraction

Microcontroller: Arduino (e.g., Uno/Nano) for analog-to-digital conversion and data transmission

Power Supply: Dual ±5V or ±9V regulated power source

Software Components

Arduino IDE: For data acquisition and threshold-based detection of muscle contraction

LabVIEW: For real-time signal visualization and analysis

Python: For offline data processing, visualization, and feature extraction (optional)
