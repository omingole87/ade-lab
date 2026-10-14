# Analog & Digital Electronics Lab (ADE) — SSGMCE

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-2563eb?style=for-the-badge&logo=githubpages&logoColor=white)](https://omingole87.github.io/ade-lab/)
[![Vercel Deployment](https://img.shields.io/badge/Deployment-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://ssgmce-ade-lab.vercel.app)
[![College](https://img.shields.io/badge/SSGMCE-Shegaon-1e3a8a?style=for-the-badge)](https://www.ssgmce.ac.in)
[![License: MIT](https://img.shields.io/badge/License-MIT-059669?style=for-the-badge)](LICENSE)

An interactive, zero-dependency web portal and digital companion for the **Analog & Digital Electronics Lab (31T204PC)** at **Shri Sant Gajanan Maharaj College of Engineering (SSGMCE), Shegaon** (Department of Information Technology, Semester III).

</div>

---

## 🚀 Live Access
Launch the portal directly in your browser without any installation:
* **GitHub Pages:** 👉 **[https://omingole87.github.io/ade-lab/](https://omingole87.github.io/ade-lab/)**
* **Vercel Mirror:** 👉 **[https://ssgmce-ade-lab.vercel.app](https://ssgmce-ade-lab.vercel.app)**

---

## ✨ Features & Enhancements

### ⚡ Direct Interactive Simulations
- **Falstad CircuitJS Integration:** Interactive real-time analog/digital SPICE simulation with active potentiometers, sliders, and oscilloscope waveforms.
- **CircuitVerse Integration:** Interactive multi-bit digital logic simulation with toggle switches and LED outputs.

### 📖 Built-in Viva-Voce & Formula Drawers
- Dedicated accordion drawer for each of the 10 experiments.
- **Core Governing Equations:** Voltage gain formulas ($A_v = -R_C \parallel R_L / r'_e$, $A_{CL} = 1 + R_f / R_1$), Shockley JFET equations, and characteristic equations.
- **Curated Viva Questions & Model Answers:** Detailed, examination-ready questions on virtual ground, slew rate, universal gates, race-around conditions, and cascading logic.
- **Lab Practical Tips:** Real-world breadboarding advice, common pitfalls, and IC pin connection warnings.

### ⚡ IC Pinout & Reference Cheatsheet Modal
- Interactive reference dialog featuring full pin configurations, function tables, and electrical ratings:
  - **IC 741** (8-Pin DIP General Purpose Operational Amplifier)
  - **IC 74153** (16-Pin DIP Dual 4:1 Multiplexer)
  - **IC 74155** (16-Pin DIP Dual 1:4 Demultiplexer / 2:4 Decoder)
  - **74xx Series Standard Gates** (7404, 7408, 7432, 7400, 7402, 7486, 7485, 7476)
  - **Breadboarding Best Practices & Lab Safety**

### 📋 Persistent Lab Progress Tracker
- Interactive checkboxes to mark practicals as completed.
- Dynamic percentage completion bar persisted automatically in `localStorage`.
- **⬇️ JSON Export:** Backup completed progress to a timestamped `.json` file.
- **⬆️ JSON Import:** Restore completed practical progress on any device or browser.
- **🔄 Reset:** Easily clear completion status when beginning a new term.

### 🔍 Real-Time Search & Course Outcome (CO) Filtering
- Filter experiments instantly by Course Outcome:
  - **CO1:** Amplifiers & Operational Amplifiers (Exps 1–3)
  - **CO2:** Logic Gates & Arithmetic Adders (Exps 4–5)
  - **CO3:** Multiplexers, Demultiplexers & Magnitude Comparators (Exps 6–8)
  - **CO4:** Field Effect Transistors & Sequential Flip-Flops (Exps 9–10)
- Filter by simulation platform (Falstad vs CircuitVerse).
- Full-text search across titles, IC numbers (741, 74153, 74155, 7485, etc.), and circuit keywords.

### 🖨️ Submission-Ready Print Stylesheet
- Hit **Print Index** (or `Ctrl + P`) to generate a clean, official submission index sheet.
- Automatically inserts a student metadata block (Name, Roll No, Batch, Evaluation Signature) while hiding navigation toolbars and simulator action buttons.

### 🌓 Adaptive Dark / Light Mode
- Smooth transitions between slate dark mode and crisp light mode with user preference persistence.

---

## 🔬 Syllabus Experiments List

| # | Practical Title | Outcome | Platform | Key Components / IC |
|---|-----------------|---------|----------|---------------------|
| 1 | CE Amplifier with variation of load resistance | **CO1** | Falstad CircuitJS | BJT, $R_C, R_E, C_E, R_L$ |
| 2 | Inverting mode of op-amp | **CO1** | Falstad CircuitJS | IC 741 Op-Amp, $R_1, R_f$ |
| 3 | Non-inverting mode of op-amp | **CO1** | Falstad CircuitJS | IC 741 Op-Amp, $R_1, R_f$ |
| 4 | Operation of basic & universal logic gates | **CO2** | CircuitVerse | 7404, 7408, 7432, 7400, 7402, 7486 |
| 5 | Half Adder and Half Subtractor | **CO2** | Falstad CircuitJS | XOR, AND, NOT logic gates |
| 6 | Multiplexer operation | **CO3** | CircuitVerse | IC 74153 (Dual 4:1 MUX) |
| 7 | De-multiplexer operation | **CO3** | CircuitVerse | IC 74155 (Dual 1:4 DE-MUX) |
| 8 | 4-bit Magnitude Comparator | **CO3** | CircuitVerse | IC 7485 / Comparator logic |
| 9 | Characteristics of JFET | **CO4** | Falstad CircuitJS | N-channel JFET, $V_{GS}, V_{DS}$ sweep |
| 10 | Truth table verification of JK Flip-Flop | **CO4** | Falstad CircuitJS | IC 7476 / JK Flip-Flop logic |

---

## 🛠️ Tech Stack & Architecture
- **Vanilla HTML5, CSS3, & ES6 JavaScript:** Zero external runtime dependencies or npm builds required. Fast, portable, and runs instantly in any modern web browser or offline file environment.
- **Hosting:** GitHub Pages & Vercel.
- **Reference Standard:** Lab Manual Reference `SSGMCE/WI/IT/C008/31T204PC`.

---

## 👥 Academic Credits
* **Department:** Information Technology, Shri Sant Gajanan Maharaj College of Engineering (SSGMCE), Shegaon
* **Faculty:** Prof. Aditi Ghive &amp; Pranav Lod
* **Approved By (H.O.D.):** Dr. S. D. Padiya
* **Portal Design & Engineering:** [Om Ingole](https://github.com/omingole87)

---

## 📄 License
This project is open-source under the [MIT License](LICENSE).
