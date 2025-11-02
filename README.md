# Current Challenges and Issues in Car Traffic Forecasting

This repository accompanies the research paper **"Current Challenges and Issues in Car Traffic Forecasting"**.  
It provides a curated collection of publicly available **traffic-related datasets** used for forecasting, analysis, and modeling of car traffic.

---

## 📂 Repository Structure

The repository includes:
- **Datasets Combined.xlsx** — a master spreadsheet containing all datasets categorized across multiple sheets.
- **Individual CSV files** — each dataset category (e.g., traffic counts, GPS trajectories, navigation data, etc.) is provided as a separate CSV file for easier programmatic access.
- **References list.csv** - a CSV file with list of surveys analized in paper **"Current Challenges and Issues in Car Traffic Forecasting"**

```
📁 traffic-forecasting-datasets-review/
├── Datasets Combined.xlsx
├── Open CDR Data.csv
├── Open Census Data and Survey Data.csv
├── Open GPS Trajectory Data.csv
├── Open LBS Data.csv
├── Open Road Sensors Data.csv
├── Open Trip Survey Datasets.csv
├── References list.csv
└── README.md
```
---

## 🧩 Purpose

This repository aims to:
- **Support reproducibility** in the study of traffic forecasting methods.  
- **Provide researchers** with a centralized list of open datasets across domains (sensor-based, trajectory, mobile, navigation).  
- **Facilitate future benchmarking** and comparative studies.

---

## 📊 Data Format

All datasets include the following columns (where applicable):

| Column | Description |
|--------|--------------|
| `Name` | Official dataset name |
| `Type` | Type of data (e.g., traffic flow, GPS, check-ins) |
| `Spatial Range` | Geographic coverage |
| `Temporal Range` | Years or update range |
| `Download Link` | Direct or source URL |

---

## 🧠 How to Use

You can:
- **Explore datasets** in Excel or Google Sheets format (`datasets.xlsx`).
- **Import CSV files** into your code or data pipeline (e.g., `pandas.read_csv()`).
- **Cite datasets** individually or collectively (see Citation below).

---

## ⚖️ License

This repository is released under the **MIT License**.  
Each dataset linked herein remains under its **original license and ownership**.  
Please refer to the source URLs for licensing terms and data usage conditions.

---

_Last updated: November 2025_
