# ✋ VersaGrip – Passive 3-Axis Assistive Stabilization Hub

<p align="center">

![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Prototype-brightgreen)
![Hardware](https://img.shields.io/badge/Hardware-3D%20Printed-blue)
![Track](https://img.shields.io/badge/Track-Assistive%20Technology-orange)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-success)

</p>

<p align="center">
<b>Zero-Electronic • Battery-Free • Passive Mechanical Stabilization Device</b><br>
Designed to improve independence for individuals with motor control challenges.
</p>

---

# 📖 Overview

VersaGrip is a **passive 3-axis mechanical stabilization hub** that reduces hand tremors without using electronics, batteries, sensors, or software.

The device is designed primarily for individuals with **Cerebral Palsy**, **Essential Tremor**, **Parkinsonian tremors**, and other motor-control disorders, enabling easier performance of daily activities such as:

- 🍽 Eating
- 🪥 Brushing teeth
- ✍ Writing (future attachment)
- 🧴 Personal hygiene

Instead of active electronic stabilization, VersaGrip relies entirely on **mechanical engineering** and **physics-based damping**.

---

# 🎯 Problem Statement

Many assistive devices available today are:

- Expensive
- Battery dependent
- Heavy
- Difficult to maintain
- Not easily customizable

VersaGrip provides a **low-cost**, **open-source**, **3D-printable**, and **maintenance-free** alternative.

---

# 🚀 Key Features

- ✅ Zero Electronics
- ✅ Battery-Free Operation
- ✅ Passive Magnetic Tremor Dampening
- ✅ 3-Axis Mechanical Gimbal
- ✅ Universal Attachment System
- ✅ Waterproof & Washable
- ✅ Lightweight Design
- ✅ Open Source CAD
- ✅ Low Manufacturing Cost (~₹900)

---

# 🏗 System Architecture

```
          User Hand
              │
              ▼
 ┌─────────────────────────┐
 │ Layer 1                 │
 │ Voronoi Lattice Handle  │
 └─────────────────────────┘
              │
              ▼
 ┌─────────────────────────┐
 │ Layer 2                 │
 │ Triple Axis Gimbal      │
 │ + Magnetic Dampening    │
 └─────────────────────────┘
              │
              ▼
 ┌─────────────────────────┐
 │ Layer 3                 │
 │ Universal Tool Holder   │
 └─────────────────────────┘
              │
              ▼
        Spoon / Fork /
       Toothbrush etc.
```

---

# ⚙ Engineering Principle

VersaGrip functions as a **physical signal filter**.

Instead of electronically detecting tremors,

```
Hand Tremor
      │
      ▼
Mechanical Gimbal
      │
      ▼
Magnetic Eddy Current Damping
      │
      ▼
Smooth Controlled Motion
```

The embedded **N52 Neodymium Magnets** create passive resistance through **eddy current damping**, reducing rapid unwanted movements while allowing intentional slow movements.

---

# 🧩 Component Breakdown

| Layer | Component | Material | Purpose |
|--------|-----------|----------|---------|
| Layer 1 | Lattice Handle | PLA+ | Lightweight ergonomic grip |
| Layer 2 | Triple Axis Gimbal | SLA Resin | Mechanical stabilization |
| Layer 2 | Ball Bearings | Steel | Low-friction movement |
| Layer 2 | N52 Magnets | Neodymium | Passive damping |
| Layer 3 | Universal Hub | TPU | Attachment mechanism |
| Feedback | Spirit Level | Acrylic | Visual alignment guidance |

---

# 💡 Human-Centered Design

VersaGrip includes a built-in **Glow Spirit Level** that provides visual feedback during movement.

Benefits include:

- Better wrist alignment
- Motor training
- Improved hand-eye coordination
- Long-term rehabilitation support

---

# 🧰 Bill of Materials

| Component | Qty | Estimated Cost |
|------------|----:|---------------:|
| PLA Handle | 1 | ₹150 |
| SLA Gimbal | 1 | ₹300 |
| Steel Bearings | 6 | ₹180 |
| N52 Magnets | 6 | ₹120 |
| TPU Collar | 1 | ₹100 |
| Spirit Level | 1 | ₹50 |

### **Total Cost**

**≈ ₹900**

---

# 📁 Repository Structure

```
VersaGrip/
│
├── CAD_Files/
│   ├── Chassis_Voronoi.stl
│   ├── Gimbal_Rings.stl
│   └── VersaGrip_Assembly.glb
│
├── Documentation/
│   ├── Architecture.png
│   ├── Mechanical_Logic.pdf
│   └── Assembly_Guide.pdf
│
├── BOM/
│   └── Budget.csv
│
├── Images/
│   ├── Prototype.png
│   ├── Exploded_View.png
│   └── Architecture.png
│
├── LICENSE
│
└── README.md
```

---

# 🛠 Manufacturing Process

### Step 1

Print the outer chassis using PLA+

- Layer Height: 0.2 mm
- Infill: 20%

---

### Step 2

Print the gimbal rings using SLA resin.

---

### Step 3

Insert:

- Steel Bearings
- N52 Magnets

into the pivot locations.

---

### Step 4

Assemble the three-axis gimbal.

---

### Step 5

Fit the gimbal into the lattice handle.

---

### Step 6

Attach the TPU universal tool holder.

---

# 🔬 Technologies Used

- CAD Design
- Mechanical Engineering
- Passive Dynamics
- Eddy Current Damping
- 3D Printing
- PLA+
- SLA Resin
- TPU
- Neodymium Magnets

---

# 🎯 Applications

- Assistive Healthcare
- Rehabilitation
- Occupational Therapy
- Daily Living Assistance
- Open-source Medical Hardware

---

# 🔮 Future Improvements

- ESP32 + IMU Integration
- Tremor Analytics Dashboard
- Mobile Application
- AI-Based Rehabilitation Insights
- Custom Parametric CAD Generator
- Additional Modular Attachments

---

# 📸 Project Images

> Add screenshots here.

```
images/
├── Prototype.png
├── Assembly.png
├── Exploded_View.png
└── Working_Demo.gif
```

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for details.

---

# 👨‍💻 Team ForgeNova

### AssistX Hackathon Submission

**Project:** VersaGrip – Passive 3-Axis Assistive Stabilization Hub

**Focus Areas**

- Mechanical Engineering
- Assistive Technology
- Human-Centered Design
- Open-Source Hardware
- Affordable Healthcare Innovation

---

## ⭐ Support

If you found this project interesting, consider giving it a **⭐ Star** on GitHub.

It helps others discover the project and supports future development.

---

<p align="center">
Made with ❤️ for Accessible & Affordable Healthcare
</p>
