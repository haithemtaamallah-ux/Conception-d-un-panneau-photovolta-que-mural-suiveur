# Wall-Mounted Photovoltaic Panel Design with Solar Tracking Device

**End-of-Year Project Report**  
**2nd Year Mechanical Engineering**  
**National Engineering School of Tunis (ENIT)**  
**University of Tunis El Manar**  
**Academic Year: 2025/2026**

**Prepared by:**  
- Snoussi Syrine Sara  
- Taamallah Haithem  

**Supervised by:**  
Mr. Jemmali Mohamed

## 📌 Project Context

This project aims to design a **wall-mounted photovoltaic panel** for self-consumption, equipped with a **single-axis solar tracking device** to optimize the panel’s orientation throughout the day and maximize the amount of solar energy harvested.

## 🎯 Main Objectives

- Study the Tunisian energy context and the operation of photovoltaic cells  
- Geometrically model the solar path and calculate the angle of incidence  
- Develop Python code to simulate irradiance and annual energy yield for different fixed and tracking inclinations  
- Mechanically design a single-axis tracker actuated by an electric actuator (CAD modeling in CATIA V5)  
- Dimension the components and validate the mechanism’s kinematics  

## 🗂 Repository Structure

*(Details to be added in the GitHub repository)*

## 📊 Detailed Report Content

### 1. Context and Problem Statement
- Current energy situation in Tunisia  
- Structure and operation of a PV cell  
- Effect of the incidence angle on energy production  

### 2. Numerical Modeling and Simulation
- Geometrical model of solar movement (declination δ, hour angle ω)  
- Calculation of incidence angle θ  
- Python algorithm + validation of results  
- Annual energy comparison: fixed vs. tracking panel (different β values)  

### 3. Mechanical Design of the Tracker
- Choice of tracker type: single-axis (rotation β)  
- Kinematic solutions studied:  
  - Motors / couplings  
  - Rack and pinion  
  - Pulley-belt systems  
  - **Electric actuator + linkages** (selected solution)  
- Overall panel and mechanism sizing  
- Detailed 3D modeling in CATIA V5  
- Exploded views, assemblies, functional clearances  

## 🛠 Technologies & Tools Used

- **CAD**: CATIA V5  
- **Programming**: Python (numpy, matplotlib, astronomical calculations)  
- **Key Concepts**: Direct/diffuse radiation, solar tracking, kinematics, mechanical sizing  

## Project Visual Overview

<p align="center">
  <img src="figures/schema-global-systeme.png" alt="Overall system diagram" width="600"/>
  <br><em>Overall diagram of the panel with single-axis tracker</em>
</p>

<p align="center">
  <img src="figures/solution-catia.png" alt="CATIA Modeling" width="600"/>
  <br><em>Final 3D assembly in CATIA</em>
</p>

<p align="center">
  <img src="figures/panneau-journee.png" alt="Panel During the Day" width="600"/>
  <br><em>Panel position throughout the day</em>
</p>
