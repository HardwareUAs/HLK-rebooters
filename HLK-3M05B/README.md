# HLK-3M05B

> Ultra-compact AC-DC (90–265 VAC to 5V/0.6A) power supply module with integrated 10-hour cyclic reboot and external signal emergency cutoff.

<div align="center">

[![Input](https://img.shields.io/badge/INPUT-90~265%20VAC-cf222e?style=for-the-badge&logo=circuitverse&logoColor=white)](#)
[![Output](https://img.shields.io/badge/OUTPUT-5V%200.6A-0969da?style=for-the-badge)](#)
[![Reboot](https://img.shields.io/badge/REBOOT-10h-2da44e?style=for-the-badge)](#)
[![Enclosure](https://img.shields.io/badge/RATING-IP65-6f42c1?style=for-the-badge)](#)
[![Dimensions](https://img.shields.io/badge/DIMENSIONS-34.8%20%C3%97%2020.5%20%C3%97%2015%20mm-57606a?style=for-the-badge)](#)

</div>

<p align="center">
  <img src="HLK-3M05B_3D.png" alt="HLK-3M05B 3D Render" width="65%">
</p>

---

### ⚡ Electrical Specifications & Protection Features

* **🔌 Input**: **90 ~ 265 VAC** (50 / 60 Hz).
* **⚡ DC Output Power**:
  * **Regulated Output**: **5.0 VDC**
  * **Maximum Continuous Load Current**: up to **0.6 A** (3 W power class).
* **🔀 Switching Architecture**:
  * **Low-Side Switching with Soft-Start**: Efficient N-channel MOSFET ground-line switching with soft-start inrush protection. During output shutdown, the module seamlessly switches to a small internal dummy load to maintain converter stability, preserve efficiency, and eliminate output voltage ripple.
* **🛡️ Integrated Hardware Protections**:
  * **Short-Circuit Protection (SCP)**: Instant power cutoff under short-circuit conditions.
  * **Over-Current Protection (OCP)**: Built-in overload limiting.
* **📦 Packaging**: **IP65** (sealed encapsulated module resistant to moisture, dust, and vibration).
* **🌡️ Operating Temperature**: **-25 °C to +60 °C**.

---

### 🔌 Dedicated 220V Mains Filter Board

Dedicated external AC line filter board providing surge protection and Electromagnetic Interference (EMI) filtering (blocking high-frequency noise from 220V mains) — mandatory requirement for **EMC Certification**:

<p align="center">
  <img src="HLK-3M05B_FILTER_3D.png" alt="220V Mains Filter Board 3D Render" width="48%">
  <img src="HLK-3M05B_FILTER_DIM.png" alt="220V Mains Filter Board Dimensions" width="48%">
</p>

* **📏 Filter Board Dimensions**: **`24.8 × 18.4 mm`**.
* **🛡️ Mains Surge Protection**: High-voltage transient and surge clamping.
* **🧲 EMI Noise Filtering**: Differential high-frequency noise suppression.

---

### ⚙️ Operating Logic & `LED` Pin

* **⏱️ Cyclic Reboot Every 10 Hours**
* **🎛️ Event-Driven Control (`LED` Pin)**