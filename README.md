# VersaGrip
VersaGrip is a zero-electronic, battery-free assistive handle designed to help individuals with motor control challenges (such as tremors or cerebral palsy) independently eat and brush their teeth.
# VersaGrip: Passive 3-Axis Assistive Stabilization Hub

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CAD: Open-Source](https://img.shields.io/badge/CAD-Open--Source-blue.svg)](#)
[![Status: Concept & Architecture](https://img.shields.io/badge/Status-Concept%20%26%20Architecture-brightgreen.svg)](#)
[![Track: Assistive Tech](https://img.shields.io/badge/Track-Engineering%20Independence-orange.svg)](#)

> **Team ForgeNova** | *AssistX Hackathon Submission*

**VersaGrip** is a zero-electronic, battery-free assistive hardware architecture engineered to empower individuals—particularly children with motor control challenges such as Cerebral Palsy or Essential Tremor—to independently perform daily living tasks like eating and personal hygiene.

Unlike active motorized devices, VersaGrip utilizes **passive mechanical logic** and **physics principles** to absorb high-frequency physical hand tremors in real time without microcontrollers or external power.

---

## 📌 Table of Contents
- [System Architecture](#-system-architecture)
- [Key Engineering Features](#-key-engineering-features)
- [Human-Computer Interaction (HCI)](#-human-computer-interaction-hci)
- [Bill of Materials (BOM)](#-bill-of-materials-bom)
- [Repository Structure](#-repository-structure)
- [Manufacturing & Assembly](#-manufacturing--assembly)
- [Future Roadmap](#-future-roadmap)
- [License & Citation](#-license--citation)

---

## 📐 System Architecture

VersaGrip operates as a physical signal filter, translating erratic hand movement (input) into a steady, level utensil output through three functional layers:

### 1. Layer 1: Input Interface (Lattice Chassis)
* **Geometry:** Cylindrical Voronoi lattice mesh.
* **Material:** PLA+ (Fused Deposition Modeling / 3D Print).
* **Function:** Provides a lightweight, high-friction surface area for users with weak grip strength while remaining hollow to house the inner stabilization core.

### 2. Layer 2: Processing Core (Triple-Axis Magnetic Gimbal)
* **Mechanics:** Three concentric, de-coupled rings mounted on high-precision miniature steel ball bearings.
  * **Pitch (X-Axis):** Corrects forward/backward tilting.
  * **Roll (Y-Axis):** Corrects side-to-side rotation.
  * **Yaw (Z-Axis):** Absorbs horizontal lateral shaking.
* **Material:** SLA Resin for low-friction bearing mounting surfaces.
* **Passive Magnetic Dampening:** N52 Neodymium magnets embedded at pivot points generate **Eddy Currents** (magnetic friction) during movement. This physically "brakes" rapid tremors while allowing slow, deliberate movements without resistance.

### 3. Layer 3: Output Interface (Universal Modular Hub)
* **Mechanism:** Quick-release friction-lock mechanism.
* **Material:** Flexible Polymer (TPU).
* **Function:** Serves as a hardware "API," allowing users to snap in interchangeable everyday tools (spoons, forks, standard toothbrushes) without requiring extra tools.

---

## ✨ Key Engineering Features

* **Zero Electronics & Zero Power:** Completely waterproof, washable, maintenance-free, and battery-free.
* **Open-Source Fabrication:** Optimized for rapid manufacturing using standard FabLab desktop 3D printers (FDM/SLA).
* **Cross-Functional Modularity:** Supports eating and personal hygiene using a universal tool interface.

---

## 👁️ Human-Computer Interaction (HCI)

VersaGrip features an integrated **Glow-Alignment Spirit Level Guide** embedded directly into the chassis. This provides real-time visual feedback, enabling users to self-train motor alignment and build long-term muscle memory.

---

## 💰 Bill of Materials (BOM)

Estimated prototyping cost for fabrication in a local FabLab/3D printing facility:

| Item | Component / Description | Material / Spec | Qty | Est. Cost (INR) |
| :--- | :--- | :--- | :---: | :---: |
| 1 | Outer Lattice Handle | PLA+ Filament | 1 | ₹150 |
| 2 | Triple-Axis Gimbal Rings | SLA Resin | 1 | ₹300 |
| 3 | Pivot Bearings | Steel Ball Bearings (6mm OD) | 6 | ₹180 |
| 4 | Magnetic Dampeners | Neodymium (N52) Magnets | 6 | ₹120 |
| 5 | Output Collar Hub | TPU Flexible Polymer | 1 | ₹100 |
| 6 | Visual Alignment Guide | Spirit Level Vial | 1 | ₹50 |
| **Total** | | | | **~ ₹900** |

---

## 🛠️ Repository Structure
