# Electrical System Design: G+10 Premium Residential Tower

![Status](https://img.shields.io/badge/Status-Completed-success)
![Tools](https://img.shields.io/badge/Tools-AutoCAD%20%7C%20Excel-blue)
![Standards](https://img.shields.io/badge/Compliance-NBC%202016-orange)

## 🚀 Project Overview
This repository contains the end-to-end electrical system design for a **G+10 Premium Residential Tower** featuring 40 luxury flats. The design covers everything from initial load estimation and transformer sizing to Single Line Diagrams (SLD) and a comprehensive Bill of Quantities (BoQ).

The project adheres strictly to **NBC 2016 (National Building Code of India)** guidelines for safety, efficiency, and reliability.

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

## 🛠️ Design Methodology

### 1. Load Calculation (Excel)
* Detailed calculation of connected loads: Lighting, Power, HVAC, Lifts, Pumps, EV Charging, and Fire Services.
* Application of **Diversity & Demand Factors** per NBC 2016 (Part 8).
* Determination of Transformer and DG capacities to ensure optimal performance without over-sizing.

### 2. System Design (AutoCAD)
* **SLD Development:** Comprehensive Single Line Diagram from the Utility Transformer to the final floor distribution.
* **Safety Interlocks:** Implemented mechanical interlocks between Grid and DG supplies to prevent back-feeding.
* **Floor Layouts:** Typical floor plans detailing meter rooms and sub-distribution boards.

### 3. Cost Estimation (BoQ)
* Market-rate estimation for key components: Transformers, LT Panels, XLPE Cables, Busbar Trunking, and Earthing systems.
* Detailed Bill of Quantities for material procurement and project budgeting.

---

## 📂 File Structure

```text
├── Electrical_Load_Schedule.xlsx  # Load calculations & Sizing
├── Single_Line_Diagram.dwg        # AutoCAD source file
├── Bill_of_Quantities.xlsx        # Detailed cost estimation
├── Drawings/                      # PDF & Image exports of SLDs
└── README.md                      # Project documentation
