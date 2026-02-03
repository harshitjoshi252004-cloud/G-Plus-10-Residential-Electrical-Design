# Electrical System Design: G+10 Premium Residential Tower

![Status](https://img.shields.io/badge/Status-Completed-success)
![Tools](https://img.shields.io/badge/Tools-AutoCAD%20%7C%20Excel-blue)
![Standards](https://img.shields.io/badge/Compliance-NBC%202016-orange)

## 🚀 Project Overview
This repository contains the end-to-end electrical system design for a **G+10 Premium Residential Tower** featuring 40 luxury flats. The design covers everything from initial load estimation and transformer sizing to Single Line Diagrams (SLD) and a comprehensive Bill of Quantities (BoQ).

The project adheres strictly to **NBC 2016 (National Building Code of India)** guidelines for safety, efficiency, and reliability.

---

## 📸 Design Visuals
*(Click images to expand)*

| **Single Line Diagram (SLD)** | **Load Calculation Sheet** |
|:---:|:---:|
| <img src="path/to/your/SLD_screenshot.png" width="400"> | <img src="path/to/your/Excel_screenshot.png" width="400"> |
| *Complete distribution hierarchy from 11kV to 415V* | *Demand factors & load scheduling per NBC 2016* |

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
│   ├── Load_Schedule_NBC_Compliant.xlsx   # Connected Load & Max Demand Calcs
│   └── Transformer_DG_Sizing.xlsx         # Capacity selection sheets
│
├── 📁 Drawings (AutoCAD & PDF)
│   ├── Electrical_SLD_G+10.dwg            # Main Single Line Diagram
│   ├── Typical_Floor_Layout.dwg           # Lighting & Power Layouts
│   └── SLD_Export.pdf                     # PDF Version for quick viewing
│
├── 📁 Costing
│   └── Bill_of_Quantities_BoQ.xlsx        # Detailed material costing
│
└── README.md
