# 46770-IEG-Group8

This repository contains the Group 8 workspace for **46770 Integrated Energy Grids** (DTU, Spring 2026).

## Project Overview

The full implementation is in **[main.ipynb](main.ipynb)**.  
The notebook runs the complete workflow for **Task A–D**.

All input data is stored in **[data/](data)**:
- [data/electricity_demand.csv](data/electricity_demand.csv)
- [data/heat_demand.csv](data/heat_demand.csv)
- [data/offshore_CF.csv](data/offshore_CF.csv)
- [data/onshore_CF.csv](data/onshore_CF.csv)
- [data/solar_CF.csv](data/solar_CF.csv)

---

## How the Code Works

The notebook is structured to execute Tasks A–D in sequence:

1. **Load data** from CSV files in **[data/](data)**.
2. **Preprocess/align timeseries** for demand and capacity factors.
3. **Run calculations for each task (A–D)** in separate notebook sections.
4. **Present outputs** as tables/plots directly in the notebook.

Because everything is in one notebook, execution order matters:  
run cells in order to ensure intermediate variables from earlier tasks are available for later tasks.

---
