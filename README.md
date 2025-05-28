# Bevel Gearbox Design Project

![Bevel Gearbox](https://img.shields.io/badge/Mechanical-Design-blue) 
![AGMA Standards](https://img.shields.io/badge/AGMA-Compliant-green)

A comprehensive design and analysis of a bevel gear transmission system developed for Mechanical Design III at Alexandria University.

## 📌 Project Overview

This project presents a complete engineering solution for a bevel gear transmission system capable of:
- Transmitting **12.57 kW** power
- Converting **1200 rpm input** to **300 rpm output** (4:1 reduction ratio)
- Increasing torque from **100 N·m** to **400 N·m**
- Operating with **safety factors of 2.65** for both bending and contact stresses

## 🛠️ Technical Specifications

### ⚙️ Gear System
| Parameter        | Pinion       | Gear         |
|------------------|--------------|--------------|
| Teeth Count      | 15           | 60           |
| Pitch Diameter   | 180 mm       | 720 mm       |
| Cone Angle       | 14.04°       | 75.96°       |
| Module           | 12 mm        | 12 mm        |
| Face Width       | 100 mm       | 100 mm       |
| Pressure Angle   | 20°          | 20°          |

### 🔩 Key Components
- **Bearings:** SKF 6210 (Dynamic load: 37.1kN, Static load: 23.2 kN)
- **Shafts:** 
  - Pinion shaft: Ø48-62mm
  - Gear shaft: Ø50-55mm
- **Seals:** Radial mechanical seals (Ø62mm)

## 📂 Repository Structure

/Bevel-Gearbox
│── /CAD
│ ├── Assembly.SLDASM # Complete gearbox assembly
│ ├── Pinion.SLDPRT # Pinion 3D model
│ ├── Gear.SLDPRT # Gear 3D model
│ └── Assembly.DWG # 2D technical drawings
│
│── /Calculations
│ └── EES_Code.EES # Engineering Equation Solver script
│
│── /Documentation
│ └── Project_Report.pdf # Complete design report
│
└── README.md # This file

## 🧑‍💻 Team Members

| Name                                      | 
|-------------------------------------------|
| Ahmed Samy Elsaiid Mohamed Ahmed Elshimy  | 
| Ahmed Saiid Abdelnaby Abdelrahman         |
| Ahmed Mohamed Ahmed Saleh                 | 
| Ahmed Mohamed Refaat Bassiouny            |
| Ayman Muhammad Hussien El-sayed Muhammed  | 
| Ziad Ashraf Mohamed Ali                   |
| Mohamed Ashraf Ali Mohamed                | 
| Mohamed Alaa Hassan Mabrouk               |
| Mahmoud Mohamed Abdallah Elnahas          |

## 🔍 Key Features

✅ **Precision Gear Design**  
- AGMA-compliant tooth profiles
- Optimal cone angles for perfect meshing
- 100mm face width for load distribution

✅ **Robust Mechanical Design**  
- SKF 6210 bearings for radial/axial loads
- Properly sized shafts (Von Mises criteria)
- Integrated sealing solutions

✅ **Complete Documentation**  
- 3D CAD models (SolidWorks)
- 2D manufacturing drawings (AutoCAD)
- Detailed stress analysis (AGMA standards)

## 📚 References

1. AGMA 2003-B97 - Bevel Gear Rating Standard
2. ISO 6336-1:2019 - Gear Load Capacity
3. SKF Bearing Catalogue (2022)
4. GearTrax by Camnetics

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
  <i>Developed with ❤️ by Team 21 | Alexandria University | Mechanical Design III - Spring 2025</i>
</div>
