# 🌊 HEC-RAS 2D Hydraulic Modelling of the Padma River

A GIS-integrated 2D hydraulic modelling workflow developed for a selected reach of the **Padma River, Bangladesh**, using **HEC-RAS**. The project covers the complete pipeline — from DEM preprocessing and coordinate transformation to terrain preparation, 2D flow-area development, hydraulic simulation, and visualization of model outputs.

---

## 📌 Project Overview

| | |
|---|---|
| **River** | Padma River, Bangladesh |
| **Study Area** | Pangsha, Rajbari & Faridpur |
| **Simulation Period** | 2-day flood event |
| **Model Type** | 2D Unsteady Hydraulic Model |
| **Software** | HEC-RAS 6.x, ArcGIS |
| **Coordinate System** | WGS 84 / UTM Zone 46N (EPSG:32646) |
| **Key Outputs** | Maximum Water Surface Elevation (WSE), Flow Velocity, Simulation Animation |

**Study Area:** Padma River reach covering **Pangsha (Rajbari)**, **Rajbari Sadar**, and **Faridpur** districts.

**Simulation Period:** 2-day flood event simulation.

---

## 🔄 Modelling Workflow

```
                         DEM Acquisition
                                │
                                ▼
                        DEM Preprocessing
                                │
                      WGS 84 → UTM Zone 46N
                                │
                                ▼
                        Study Area Mapping
                           Padma River
                                │
                                ▼
                      Terrain Preparation
                         for HEC-RAS
                                │
                                ▼
                       2D Flow Area Setup
                       & Mesh Generation
                                │
                                ▼
                         HEC-RAS 2D Model
                       Hydraulic Simulation
                                │
                    ┌───────────┴───────────┐
                    ▼                       ▼
             Maximum WSE               Flow Velocity
                Analysis                  Analysis
                    │                       │
                    └───────────┬───────────┘
                                ▼
                         Hydraulic Result
                           Visualization
```

---

## 🗺️ Coordinate System

All spatial datasets were reprojected to a projected coordinate system to ensure accurate distance, area, and hydraulic computations:

**WGS 84 / UTM Zone 46N — EPSG:32646**

---

## 📊 Model Outputs

### Maximum Water Surface Elevation (WSE)

<img width="1357" height="651" alt="image" src="https://github.com/user-attachments/assets/00b07ce3-10fa-44e7-baa8-673353ec7be6" />


*Spatial distribution of the maximum simulated water surface elevation (m) across the 2D flow area.*

### Flow Velocity

<img width="1365" height="679" alt="image" src="https://github.com/user-attachments/assets/2a14b3e1-b8ee-4c6d-8975-d5fb53dec049" />


*Simulated flow velocity magnitude (m/s) across the modelled reach.*

### Simulation Image

A 2D simulation animation is included to illustrate the spatial and temporal evolution of flow depth/velocity throughout the event.
### Simulation Video
* https://github.com/osmangonibu9/HEC-RAS/blob/main/Simulation.mp4*

> *<img width="1366" height="706" alt="WSEMax" src="https://github.com/user-attachments/assets/6ab1847f-9350-43f5-b745-44b206cd93d8" />
*

---

## 📁 Repository Structure

```
├── DEM/                    # Original and UTM-projected DEM datasets
├── GIS/                    # Study-area shapefiles, projection files
├── HEC-RAS/                # HEC-RAS project files (.prj, .g0x, .p0x, .u0x)
├── Outputs/                # Max WSE, velocity rasters, animation
└── README.md
```

> 

---

## Software & Tools

- **HEC-RAS** — 2D hydraulic modelling and simulation
- **ArcGIS** — Spatial data processing, DEM preprocessing, terrain preparation
- **DEM** — Digital Elevation Model for terrain representation

---

## 🎯 Skills Demonstrated

`GIS & Spatial Data Processing` `DEM Preparation` `HEC-RAS 2D Modelling` `Terrain Development` `Hydraulic Simulation` `Water Surface Elevation Analysis` `Flow Velocity Analysis`

---

## 👤 Author

**Md. Osman Goni**
Master's in Coastal Studies and Disaster Management
University of Barishal, Bangladesh

*This project was developed as a practical demonstration of GIS-integrated HEC-RAS 2D hydraulic modelling.*
