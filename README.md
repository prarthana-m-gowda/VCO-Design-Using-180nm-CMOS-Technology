# VCO-Design-Using-180nm-CMOS-Technology

This repository presents a mini-project on designing a **Voltage-Controlled Oscillator (VCO)** using **TSMC 180nm CMOS technology**, simulated in **LTSpice**. The project demonstrates frequency tuning using an inverter-based ring oscillator architecture, optimized for low power and stability.

## 🎯 Project Objectives

- Design a **VCO** using 180nm CMOS models in LTSpice.
- Ensure **low power operation**, **frequency tunability**, and **circuit stability**.
- Simulate and analyze output waveform, frequency behavior, and voltage control.


## 🛠️ Tools & Technology

- **LTSpice XVII**
- **TSMC 180nm CMOS Models**  
- Waveform plots and transistor-level simulation


## 🧩 Circuit Overview

- Architecture: **5-stage ring oscillator**
- Frequency controlled by **input voltage (Vin)**
- Basic unit: CMOS inverter using **PMOS & NMOS**
- Output observed at the final stage of the ring
- Control voltage varied from **0.8V to 2V**


## 🖼️ Simulation Snapshots

### 📐 Circuit Schematic  
![VCO Schematic](vco_schematic.png)

### 📉 Output Waveform  
![Output Waveform](vco_waveform.png)

### 📊 Frequency Observation Table  
![Observation Table](vco_frequency_analysis.png)


## ✅ Key Observations

- As **Vin increases**, output **frequency increases linearly**
- Waveform maintains **stable amplitude** across different control voltages
- Output frequency range observed: **~800 MHz to ~1.6 GHz**


## 📺 Reference

Circuit inspiration and initial simulation approach referred from:  
[CMOS VCO Design in LTSpice using 180nm Technology – YouTube](https://youtu.be/HrBU2t1_TSk?si=Hdy9YUQL7FQHOa7O)  
*Simulated, analyzed, and documented independently for academic learning.*


## 📌 Conclusion

This project validates the implementation of a **voltage-controlled oscillator** using inverter-based ring architecture in **180nm CMOS**.  
It demonstrates:
- Efficient frequency tuning  
- Simple, scalable design  
- Suitability for integration in PLLs, clocks, and RF circuits


## 👩‍💻 Author

**Prarthana M**  
B.Tech – Electronics & Communication Engineering  
Sri Krishna Institute of Technology, Bengaluru  
📧 [prarthana.gowda.m@gmail.com](mailto:prarthana.gowda.m@gmail.com)


## 📁 Recommended Folder Structure

