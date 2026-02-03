# Electrical System Design: G+10 Premium Residential Tower

![Status](https://img.shields.io/badge/Status-Completed-success)
![Tools](https://img.shields.io/badge/Tools-AutoCAD%20%7C%20Excel-blue)
![Standards](https://img.shields.io/badge/Compliance-NBC%202016-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 🚀 Project Overview
This repository contains the end-to-end electrical system design for a **G+10 Premium Residential Tower** featuring 40 luxury flats. The design covers everything from initial load estimation and transformer sizing to Single Line Diagrams (SLD) and a comprehensive Bill of Quantities (BoQ).

The project adheres strictly to **NBC 2016 (National Building Code of India)** guidelines for safety, efficiency, and reliability.

---

## 📸 Design Visuals
*(Click images to expand)*

| **Single Line Diagram (SLD)** | **Bill of Quantities (BoQ) & Costing** |
|:---:|:---:|
| <img src="assets/sld_preview.png" width="400" alt="AutoCAD Single Line Diagram"> | <img src="assets/boq_preview.png" width="400" alt="Bill of Quantities Excel Sheet"> |
| *Complete distribution hierarchy from 11kV to 415V* | *Detailed material takeoff & project cost estimation (₹42.8L)* |

---

## ⚡ Technical Specifications

| Parameter | Value |
| :--- | :--- |
| **Building Type** | Residential (G+10 Floors) |
| **Total Flats** | 40 Units (4 Flats per Floor) |
| **Total Connected Load** | ~645 kW |
| **Maximum Demand** | ~347 kW |
| **Transformer Selected** | **630 kVA** (11/0.433 kV, Oil Cooled) |
| **Backup Power (DG)** | **250 kVA** (For Essential Loads) |
| **Distribution System** | Rising Mains – Busbar Trunking (800A) |
| **Estimated Project Cost**| ~₹ 42.8 Lakhs |

---

## 📂 Repository Structure

```text
├── 📁 Calculations
│   ├── Electrical_Load_Schedule.xlsx      # Connected Load & Max Demand Calcs (NBC Part 8)
│   └── Transformer_DG_Sizing.xlsx         # Capacity selection calculations
│
├── 📁 Drawings (AutoCAD & PDF)
│   ├── Single_Line_Diagram.dwg            # Main Distribution SLD (Source File)
│   ├── Typical_Floor_Layout.dwg           # Lighting & Power Layouts
│   └── SLD_Export.pdf                     # PDF Version for quick viewing
│
├── 📁 Costing
│   └── Bill_of_Quantities.xlsx            # Detailed material costing and estimation
│
├── 📁 assets                              # Project Screenshots
│   ├── sld_preview.png
│   └── boq_preview.png
│
└── README.md
