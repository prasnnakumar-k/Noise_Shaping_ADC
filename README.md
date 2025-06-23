# Noise_Shaping_ADC
# Filter-Based Noise Shaping SAR ADC

This repository contains the design, implementation, and simulation results of a **Filter-Based Noise Shaping Successive Approximation Register (SAR) Analog-to-Digital Converter (ADC)** for low-power, high-resolution applications. The project was developed as part of the undergraduate dissertation at **PSG Institute of Technology and Applied Research** under the **Electronics and Communication Engineering** department.

## 🧠 Project Overview

Conventional SAR ADCs face challenges such as:
- Quantization noise
- Comparator noise
- Capacitive mismatch errors

To overcome these issues, this project proposes a **Noise Shaping SAR ADC (NS SAR ADC)** that integrates a **fully differential OTA-based loop filter**. The filter spectrally shapes the quantization noise, pushing it to higher frequencies, thereby improving in-band SNR and resolution.

## 🧩 Features

- **8-bit resolution** with effective noise shaping
- **Low power consumption**
- **Robust against PVT (Process-Voltage-Temperature) variations**
- Modular architecture with bootstrapped sampling, capacitive DAC, OTA-based integrator, and dynamic comparator
- Implemented using **Cadence Virtuoso** in **90nm CMOS technology**

## ⚙️ Architecture Components

1. **Bootstrap Sampling Switch**
2. **Capacitive DAC (CDAC)**
3. **Dynamic Comparator**
4. **Fully Differential OTA-based Loop Filter**
5. **SAR Logic**
6. **Noise Shaping Feedback Loop**

## 🔧 Tools Used

- **Cadence Virtuoso** (Schematic, Layout, Post-layout Simulation)
- **Analog Design Environment (ADE)**
- **GPDK 90nm Technology Node**

## 📈 Results

- Achieved high linearity and resolution
- Verified via post-layout simulations
- Demonstrated improved SNDR and ENOB compared to conventional SAR ADCs
- Area: ~0.000376 mm²
- Power: ~0.62 mW

## 📚 Report and Documentation

The full report includes:
- Introduction to SAR and NS-SAR ADCs
- Literature survey
- Detailed methodology and circuit implementation
- Simulation results and performance comparison with state-of-the-art
- Conclusion and future scope

Refer to `Final_Report.pdf` for the complete dissertation.

## 👨‍💻 Authors

- **Prasanna Kumar K**
- Deepak K
- Deepesh M
- Kishore C

