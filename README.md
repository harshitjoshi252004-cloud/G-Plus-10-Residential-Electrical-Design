# ⚡ Electrical System Design – G+10 Premium Residential Tower

![Status](https://img.shields.io/badge/Status-Completed-success)
![Tools](https://img.shields.io/badge/Tools-AutoCAD%20%7C%20Excel-blue)
![Standards](https://img.shields.io/badge/Compliance-NBC%202016-orange)

---

## 📌 Project Overview

This repository contains the **complete electrical system design** for a **G+10 Premium Residential Tower** comprising **40 luxury apartments** (4 flats per floor).

The project covers the **entire design lifecycle**:
- Electrical load estimation
- Maximum demand calculation
- Transformer & DG sizing
- Single Line Diagram (SLD)
- Typical floor layouts
- Bill of Quantities (BoQ) & cost estimation

All designs strictly comply with **NBC 2016 (National Building Code of India – Part 8)** and standard electrical engineering practices.

---

## 🏢 Building Details

| Parameter | Description |
|---------|-------------|
| Building Type | Residential (G+10 Floors) |
| Total Flats | 40 Units |
| Flats per Floor | 4 |
| Supply Voltage | 11 kV / 415 V |
| Distribution System | Rising Mains with Busbar Trunking |

---

## ⚡ Key Technical Specifications

| Item | Value |
|----|------|
| **Total Connected Load** | ~645 kW |
| **Maximum Demand** | ~347 kW |
| **Transformer Capacity** | 630 kVA (11/0.433 kV, Oil Cooled) |
| **DG Set Capacity** | 250 kVA (Essential Loads) |
| **Busbar Trunking** | 800 A |
| **Power Factor Considered** | 0.9 |
| **Estimated Project Cost** | ₹ 42.8 Lakhs |

---

## 📐 Design Visuals

| Single Line Diagram (SLD) | BoQ & Costing |
|:---:|:---:|
| <img src="Drafting_and_Schematics/Single_Line_Diagram.pdf" width="400"> | <img src="Cost_Estimation_BoQ/Bill_of_Quantities.pdf" width="400"> |
| Complete distribution from 11kV to LT panels | Detailed material take-off & costing |

---

## 📂 Repository Structure

```text
Electrical-System-Design-G+10-Residential/
│
├── README.md
├── LICENSE
│
├── docs/
│   ├── Single_Line_Diagram.pdf
│   ├── Typical_Floor_Detail.pdf
│   └── Bill_of_Quantities.pdf
│
├── calculations/
│   ├── Electrical_Load_Calculation.xlsx
│   ├── Electrical_Load_Calculation.pdf
│   └── Transformer_DG_Sizing.xlsx
│
├── drawings/
│   ├── sld/
│   │   ├── Single_Line_Diagram.dwg
│   │   └── Single_Line_Diagram.pdf
│   │
│   └── layouts/
│       ├── Typical_Floor_Layout.dwg
│       └── Typical_Floor_Layout.pdf
│
├── costing/
│   └── Bill_of_Quantities.xlsx
│
├── assets/
│   ├── sld_preview.png
│   └── boq_preview.png
│
└── .gitignore
