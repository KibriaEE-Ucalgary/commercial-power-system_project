# commercial-power-system_project
# 🔌 Electrical Power Distribution System Design for 25 kV Underground Infrastructure

This repository contains the design, calculations, and supporting documentation for a **25 kV Underground Power Distribution System**, including both **normal and emergency Single Line Diagrams (SLDs)**, **generator and UPS recommendations**, **battery sizing**, and **site distribution strategies**.

## 📂 Repository Structure


## 📝 Project Description

The objective of this project is to design a robust and scalable underground power distribution system for a 28-room facility. The system includes:

- **Normal and Emergency SLDs**
- **25 kV Grid Supply**
- **Diesel Generator Backup (Kohler 250REOZJD)**
- **Uninterruptible Power Supply (UPS) System for Emergency Loads**
- **Battery Sizing and Configuration**
- **Transformer and Breaker Configuration**
- **Distribution Panel Planning**
- **Optional Solar Integration**

---

## 📊 Key Components

### 🔧 Generator Specifications

- **Model:** Kohler 250REOZJD
- **Power:** 250 kW
- **Fuel Type:** Diesel
- **Runtime:** ~10–12 hours at 75% load
- **Noise Level:** 69–72 dBA
- **Enclosure:** Soundproof and weatherproof

### ⚡ UPS Sizing and Backup

- **Required Load:** 16.55 kW (Apparent Power: 17.43 kVA)
- **UPS Rating:** 25 kVA (Schneider Electric Galaxy VS)
- **Units:** 2 (1 Active, 1 Standby)
- **Backup Time:** 1 hour
- **Battery Requirement:** 36× 12V, 90Ah (Trojan J185H-AC)
- **Total Battery Cost:** $27,394.92 CAD

### 🔋 Battery Sizing

- **Energy Required:** 16,550 Wh
- **UPS Efficiency:** 90%
- **Adjusted Energy:** 18,389 Wh
- **DC Bus Voltage:** 208V
- **Battery Capacity:** 90 Ah

---

## 🔌 Power Distribution Options

### Option 1: Grid + Generator + UPS
- Grid supplies 8 distribution panels.
- Diesel generator backs up essential systems.
- UPS supports critical loads (e.g. fire alarms, cameras, lights).

### Option 2: Grid + Solar + Generator + UPS
- Integration of renewable energy through Solar PV.
- Reduced dependency on grid power.
- Enhanced sustainability and resilience.

---

## 🔄 Feedback & Improvements

### Instructor Feedback:
> "Drafts are hard to read due to thin lines. Requires zooming for analysis."

### Actions Taken:
- Increased line widths and equipment sizes in AutoCAD.
- .DWG files are attached in the repository for high-resolution access.
- PDFs and images are embedded in the report for readability.

---

## 💰 Cost Summary

| Component | Unit Price (CAD) | Quantity | Total Cost (CAD) |
|----------|------------------|----------|------------------|
| UPS (Schneider Galaxy VS 25 kVA) | $19,866.99 | 2 | $39,733.98 |
| Batteries (12V, 90Ah) | $760.97 | 36 | $27,394.92 |

---



---

## 📎 Notes

> 💡 For best results, open `.dwg` files with AutoCAD or DWG TrueView.  
> 📄 All calculations and schematics are thoroughly documented in `Report.pdf`.

---


