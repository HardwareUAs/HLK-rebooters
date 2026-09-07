# HLK-5M05

> High-reliability 5W AC-DC (90–265 VAC to 5V/1.0A) power supply module with integrated 10-hour cyclic reboot, low-side power switch, and external emergency shutdown.

<div align="center">

[![Input](https://img.shields.io/badge/INPUT-90~265%20VAC-cf222e?style=for-the-badge&logo=circuitverse&logoColor=white)](#)
[![Output](https://img.shields.io/badge/OUTPUT-5V%201.0A-0969da?style=for-the-badge)](#)
[![Reboot](https://img.shields.io/badge/REBOOT-10h-2da44e?style=for-the-badge)](#)
[![Enclosure](https://img.shields.io/badge/RATING-IP65-6f42c1?style=for-the-badge)](#)
[![Dimensions](https://img.shields.io/badge/DIMENSIONS-38%20%C3%97%2023%20%C3%97%2018%20mm-57606a?style=for-the-badge)](#)

</div>

<p align="center">
  <img src="HLK-5M05_3D.png" alt="HLK-5M05 3D Render" width="65%">
</p>

---

### ⚡ Electrical Specifications & Protection Features

* **🔌 Input**: **90 ~ 265 VAC** (50 / 60 Hz).
* **⚡ DC Output Power**:
  * **Regulated Output**: **5.0 VDC**
  * **Continuous Load Current**: up to **1.0 A** (5 W power class).
* **🔀 Switching Architecture**:
  * **Low-Side Switching with Soft-Start**: N-channel power MOSFET controlling the load return ground path with soft-start protection. During output shutdown, the module seamlessly switches to a small internal dummy load to maintain converter stability, preserve efficiency, and eliminate output voltage ripple.
* **🛡️ Integrated Hardware Protections**:
  * **Short-Circuit Protection (SCP)**: Fast cutoff upon output dead short with auto-recovery.
  * **Over-Current Protection (OCP)**: Safe current-limiting preventing power brick damage.
* **📦 Packaging**: **IP65** (sealed encapsulated module protecting against moisture, dust, and aggressive environments).
* **🌡️ Operating Temperature**: **-25 °C to +60 °C**.

---

### 🔌 Dedicated 220V Mains Filter Board

Dedicated external AC line filter board providing surge protection and Electromagnetic Interference (EMI) filtering (blocking high-frequency noise from 220V mains) — mandatory requirement for **EMC Certification**:

<p align="center">
  <img src="HLK-5M05_FILTER_3D.png" alt="220V Mains Filter Board 3D Render" width="48%">
  <img src="HLK-5M05_FILTER_DIM.png" alt="220V Mains Filter Board Dimensions" width="48%">
</p>

* **📏 Filter Board Dimensions**: **`24.8 × 18.4 mm`**.
* **🛡️ Mains Surge Protection**: High-voltage transient and surge clamping.
* **🧲 EMI Noise Filtering**: Differential high-frequency noise suppression.

---

### ⚙️ Operating Logic & `LED` Pin

* **⏱️ Cyclic Reboot Every 10 Hours**
* **🎛️ Event-Driven Control (`LED` Pin)**