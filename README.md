# ⚡ HLK Rebooters Series

> High-reliability AC-DC power supply modules (90–265 VAC to 5 VDC) with integrated 10-hour cyclic reboot, low-side power switching with soft-start, and event-driven control logic.

> [!NOTE]
> **Available Form-Factor Modifications**:
> * **Power Ratings**: 2 W, 3 W, 5 W, 10 W, 15 W, 20 W, 30 W, 40 W, 50 W, 60 W
> * **Output Voltages**: 3.3 V, 5 V, 9 V, 12 V, 15 V, 24 V

---

## 📋 Active Models & Modules

<div align="center">

[![HLK-5M05](https://img.shields.io/badge/HLK--5M05%20(5V%2F1A)-38%20%C3%97%2023%20%C3%97%2018%20mm-555555?labelColor=6f42c1&style=for-the-badge&logo=circuitverse&logoColor=white)](./HLK-5M05/)
[![HLK-3M05B](https://img.shields.io/badge/HLK--3M05B%20(5V%2F0.6A)-34.8%20%C3%97%2020.5%20%C3%97%2015%20mm-555555?labelColor=6f42c1&style=for-the-badge&logo=circuitverse&logoColor=white)](./HLK-3M05B/)

</div>

---

### 📂 Directory Structure

| Module Model | AC Input | DC Output | Dimensions | Features & Description | Folder |
| :--- | :---: | :---: | :---: | :--- | :---: |
| **HLK-5M05** | `90–265 VAC` | `5.0 V / 1.0 A` | `38 × 23 × 18 mm` | 5W AC-DC Rebooter, Low-Side Switch with Soft-Start, Dedicated 220V Filter Board | [Open Folder →](./HLK-5M05/) |
| **HLK-3M05B** | `90–265 VAC` | `5.0 V / 0.6 A` | `34.8 × 20.5 × 15 mm` | 3W Compact AC-DC Rebooter, Low-Side Switch with Soft-Start, Dedicated 220V Filter Board | [Open Folder →](./HLK-3M05B/) |

---

### 🛡️ Common Architectural Features

* **🔌 Input**: **90 ~ 265 VAC** (50/60 Hz).
* **⏱️ Autonomous 10-Hour Cyclic Reboot**: Periodically power-cycles connected hardware every 10 hours to prevent system lockups.
* **🎛️ Event / Signal Monitoring (`LED` Pin)**: Hardware input line capable of detecting and reacting to external events, logic signals, or indicator states with digital debounce filtering to execute controlled power cutoff or reset.
* **🔀 Low-Side Switching with Soft-Start**: Efficient N-channel MOSFET ground-return switching with integrated soft-start. During output shutdown, the converter seamlessly switches to a small internal dummy load to maintain stability, preserve efficiency, and prevent output voltage ripple.
* **📦 Packaging**: **IP65** (encapsulated potted module resistant to dust and moisture).
* **🌡️ Operating Temperature**: **-25 °C to +60 °C**.
