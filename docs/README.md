#English Readme
---
# 🌳 From Forest to Pasture — Guerrero (Terra)

**Team:** Dancing' Bros  
**Members:** Oliver Sebastián Ortega García, David Alejandro Ortega García, Yazid Itzayana Rodríguez Rodríguez, Jaquelin de los Ángeles García Constantino, David Israel Ortega González  
**Date:** October 4, 2025  
**Organizer:** NASA Space Apps Challenge

---

## 📂 Project Structure
``` dir
/source      → Google Earth Engine (GEE) scripts  
/data        → Raw CSV data  
/outputs     → Final tables and figures  
/figs        → Additional maps and visualizations  
/video       → Final video and frames  
/docs        → Project documents (en-US and es-MX)  
/site        → Backup of the project site in MHTML format
```

---

## 📊 Key Results

* **Cumulative Loss Guerrero (2001–2024):** 29,660 ha
* **Cumulative Loss Atoyac:** 1,567 ha (5.3%)
* **Peak Loss Year Guerrero:** 2024 (2,242 ha)
* **Peak Loss Year Atoyac:** 2014 (142 ha)

> 🔍 *Insights:* Deforestation in Guerrero has accelerated in recent years; Atoyac shows a more stable trend but with occasional peaks.

---

## ⚙️ How to Reproduce the Analysis

1. Export annual series from **MCD12Q1** and **NDVI (MOD13Q1)** using Google Earth Engine.
2. Run the scripts in `/source` to generate outputs in `/outputs`.
3. *(Optional)* Integrate **MCD64A1 (fire)** and **ASTER** for before/after inspection.

---

## 🧠 AI Usage Statement

Generative AI was used **only for writing and editing** this README.
All geospatial analysis was conducted **100% with Google Earth Engine**.

---

## 🚀 Tips & Extras

* Check `/figs` to easily compare changes across years.
* Frames in `/video` can be used to create time-lapse animations of land cover change.
* All raw data is stored in `/data` for **full reproducibility**.

---

### ⚙️ Requirements

* **Java Runtime Environment (JRE)**
* **Visual Studio Code (VSCode)**
* **Google Cloud SDK**
* **Google Earth Engine API**

### 🚀 Installation & Usage

1. Clone the private repository:

   ```cmd
   git clone <private-repo>
   cd Repository-GEE-NASA
   ```
2. Open the project in VSCode.
3. Configure your access to the Google Earth Engine API with an authorized account.
4. Run the scripts from the terminal or inside VSCode.

### 🌍 Project Objective

The goal is to leverage **TERRA satellite data** and the power of the **Google Earth Engine API** to create innovative solutions within the **NASA Hackathon** framework.

This repository serves as the collaboration hub for the **Dancing' Bros** team.

```

