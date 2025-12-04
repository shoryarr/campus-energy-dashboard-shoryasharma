# campus-energy-dashboard-shoryasharma

# CAMPUS_ENERGY_DASHBOARD-SNEHANSH-_JANGIR
Python Capstone Project


## 📌 Project Overview
This capstone project analyzes electricity consumption across campus buildings by automating data ingestion, processing, visualization, and report generation using Python.

The final output includes:
- Cleaned dataset  
- Aggregated building statistics  
- Multi-chart dashboard  
- Executive summary  
- Automated OOP-based data modeling  

---

## 📁 Repository Structure
├── main.py
├── library_block.csv
├── science_block.csv
├── cleaned_energy_data.csv
├── building_summary.csv
├── dashboard_modular.png
├── summary.txt
└── README.md


---

## 🔧 Technologies Used
- **Python**
- **Pandas** – Data cleaning & analysis  
- **Matplotlib** – Visualizations  
- **OOP Concepts** – Building & MeterReading classes  
- **CSV & TXT export**

---

## 🧠 Key Features

### ✅ 1. Data Ingestion  
Automatically loads multiple CSV files, cleans them, and merges into a single DataFrame.

### ✅ 2. Data Analysis  
- Daily electricity totals  
- Building-wise summary (mean, max, total)

### ✅ 3. Visualizations  
Generated dashboard includes:
- **Line Chart** – Total daily consumption  
- **Bar Chart** – Average usage by building  
- **Scatter Plot** – Peak usage events  

Saved as: **dashboard_modular.png**

### ✅ 4. OOP Implementation  
Custom classes:
- `Building`
- `MeterReading`

### ✅ 5. Report Generation  
Exports:
- `cleaned_energy_data.csv`  
- `building_summary.csv`  
- `summary.txt` (executive summary)

---

## 📊 Key Insights
- **Total Energy Consumption:** 2297.8 KWh  
- **Highest Consuming Building:** Science Block  

---

## 🚀 How to Run
```bash
python main.py
