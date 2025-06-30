# 🧊 Heat Sink Design Variations — Experimental CAD Project

This project explores a series of custom-designed heat sinks, all based on a fixed 40×40 mm footprint. The objective was to analyze and visualize how different fin geometries affect surface area exposure, thermal dissipation potential, and structural manufacturability.

---

## 🔧 Project Goal

To explore, design, and compare **multiple heat sink geometries** for the same base dimensions using CAD (Fusion 360). These models are optimized for:

- 🔺 Improved airflow
- 📐 Maximized surface area
- 🖨️ 3D printability and manufacturability
- 🧱 Structural simplicity vs. complexity balance

---

## 📐 Design Parameters

- **Base dimensions**: 40 mm × 40 mm (constant)
- **Material assumed**: Aluminum (for thermal conductivity reference)
- **Design constraints**:
  - Passive cooling only (no fans)
  - Fins ≥ 1 mm thick for 3D printability
  - Geometries suitable for vertical or horizontal airflow

---

## 🧩 Design Variants

### 1. 🔳 Concentric Pyramid Fin
A layered concentric square pattern rising toward the center — ideal for uniform heat spread and unique visual appeal.

![Concentric](./assets/19.png)

---

### 2. 🟫 Linear Rectangular Fins
Traditional vertical fins with maximum parallel surface area — reliable for basic heat dissipation.

![Linear Fins](./assets/20.png)

---

### 3. 🪟 Slanted Fins with Angled Sidewalls
Angled fin structure for improved airflow dynamics, designed to guide heat-laden air outwards.

![Slanted Fins](./assets/21.png)

---

### 4. 🧱 Grid Fin Array
Grid-like vertical fins with open channels for enhanced vertical ventilation and easier printability.

![Grid](./assets/22.png)

---

### 5. ⚙️ Tapered Vertical Fins
Thick base-to-thin-top fin design, optimized for balancing print time with surface area increase.

![Tapered](./assets/23.png)

---

## 📊 Evaluation Criteria (To be analyzed further)

| Design | Surface Area ↑ | Airflow Resistance ↓ | Visual Complexity | Printability |
|--------|----------------|----------------------|-------------------|--------------|
| Concentric Pyramid | Moderate | Moderate | High | Moderate |
| Linear Fins | High | Low | Low | High |
| Slanted Fins | High | Moderate | Moderate | Moderate |
| Grid Fins | Very High | Low | Moderate | High |
| Tapered Fins | Moderate | High | Low | High |

---

## 🛠 Tools Used

- **CAD Platform**: Autodesk Fusion 360
- **Rendering**: Fusion 360 Native Viewports
- **Manufacturing Target**: FDM 3D printing (PLA or aluminum resin)

---

## 🚀 Future Work

- 🧪 Thermal simulation using Ansys or Fusion 360 Simulation workspace
- 💨 CFD analysis for airflow modeling
- 🖨️ Real-world 3D printing & testing
- 🔁 Parametric variation for automated optimization

---

## 📂 Folder Structure Suggestion

