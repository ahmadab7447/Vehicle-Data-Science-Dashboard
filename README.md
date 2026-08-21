
# 🚗 VexarDrive Fleet Analytics & Risk Intelligence

An end-to-end data analytics and Power BI project designed to analyze driver behaviour, driving risk, vehicle sensor health, and maintenance-review priorities using fleet telemetry data.

The project combines Python-based data cleaning and feature engineering with a Power BI dashboard to transform raw fleet data into actionable insights for fleet managers and operations teams.

---

## 📌 Project Overview

VexarDrive operates a connected mobility fleet and collects data from:

- GPS
- Accelerometers
- Gyroscopes
- Vehicle information
- Driver information
- Trip records
- Service history

The objective of this project is to answer two key business questions:

### 1. Which drivers demonstrate risky or safe driving behaviour?

The analysis identifies:

- High-risk drivers
- Moderate-risk drivers
- Low-risk drivers
- Major driving-risk factors
- Risk-event frequency
- Drivers requiring behavioural attention

### 2. Which vehicles show signs of irregular sensor behaviour?

The analysis identifies:

- Vehicles with unusual acceleration variability
- Vehicles with unusual gyroscope variability
- Vehicles with frequent sensor spikes
- Maintenance-review candidates
- Vehicle health scores
- Primary vehicle health concerns

---

# 🎯 Business Objectives

The project focuses on four major objectives:

1. Identify risky driving behaviour
2. Rank drivers according to behavioural risk
3. Identify vehicles with unusual sensor signatures
4. Prioritize vehicles for maintenance review

The analysis is designed to support:

- Fleet safety management
- Driver coaching
- Preventive maintenance
- Operational monitoring
- Fleet performance analysis
- Management decision-making

---

# 📊 Dashboards

The final Power BI report contains two primary dashboards.

## 1. Driver Behaviour Dashboard

The dashboard provides:

- Total drivers
- Average driver risk score
- Number of high-risk drivers
- Total risk events
- Driver risk ranking
- Risk-category distribution
- Primary risk factors
- Risk events by driver
- Driver-level detail

### Example KPIs

| KPI | Result |
|---|---:|
| Total Drivers | 30 |
| Average Risk Score | 51.67 |
| High Risk Drivers | 8 |
| Moderate Risk Drivers | 14 |
| Low Risk Drivers | 8 |

### Highest-risk drivers

| Rank | Driver | Risk Score | Primary Risk Factor |
|---:|---|---:|---|
| 1 | Lakshmi Iyer | 98.42 | Harsh braking |
| 2 | Bhavani Raj | 95.17 | Harsh acceleration |
| 3 | Kavya Pillai | 93.08 | Harsh acceleration |
| 4 | Rajesh Subramaniam | 91.00 | High risk-event frequency |

---

# 🚘 Vehicle Health Dashboard

The Vehicle Health Dashboard focuses on sensor behaviour and maintenance-review prioritization.

It includes:

- Total vehicles
- Average vehicle health score
- Maintenance-review count
- High-priority vehicles
- Vehicle health ranking
- Health-category distribution
- Primary health concerns
- Maintenance priority
- Vehicle-level sensor metrics

### Vehicle Health KPIs

| KPI | Result |
|---|---:|
| Total Vehicles | 30 |
| Average Health Score | 48.33 |
| Maintenance Review | 15 |
| Monitor | 10 |
| Healthy | 5 |

### Highest-priority vehicles

| Maintenance Rank | Vehicle | Health Score | Primary Concern |
|---:|---|---:|---|
| 1 | V19 | 3.33 | High acceleration variability |
| 2 | V23 | 12.33 | High acceleration variability |
| 3 | V24 | 13.00 | High gyroscope variability |
| 4 | V02 | 19.83 | High acceleration variability |
| 5 | V14 | 20.33 | High sensor spike frequency |

> Important: The Vehicle Health Score is a relative sensor-anomaly and maintenance-review indicator. It is not a confirmed mechanical-failure diagnosis, because the dataset does not contain confirmed mechanical-failure labels.

---

# 🗂️ Project Structure

VexarDrive-Fleet-Analytics/
│
├── 01 Images/
│   ├── driver1.png
│   ├── driver2.png
│   ├── vehicle1.png
│   └── vehicle2.png
│
├── 02_Python Notebook/
│   ├──feature_selection.ipynb
    ├──python_preprocessing.ipynb
    

│   
│
├── 03_Processed_Data/
│   ├── drivers_clean.csv
│   ├── vehicles_clean.csv
│   ├── trips_clean.csv
│   ├── telemetry_clean.csv
│   ├── trip_behaviour_features.csv
│   ├── driver_behaviour_features.csv
│   ├── driver_risk_scores.csv
│   ├── vehicle_trip_features.csv
│   ├── vehicle_health_features.csv
│   └── vehicle_health_scores.csv
│
├── 04_PowerBI/
│   └── VexarDrive_Fleet_Analytics.pbix
│
├── README.md
└── requirements.txt


---

📌 Conclusion

VexarDrive Fleet Analytics transforms raw fleet telemetry into a practical fleet-intelligence solution.

The project provides two complementary perspectives:

Driver perspective

> Who is driving unsafely and why?



Vehicle perspective

> Which vehicles show unusual sensor behaviour and may require maintenance review?



By combining Python-based feature engineering, percentile-based scoring, anomaly detection and Power BI visualization, the project provides an interpretable framework for fleet safety and maintenance decision-making.


---

👨‍💻 Author

Abrar Ahmad

Data Analyst / Data Science Enthusiast

Core Skills Demonstrated

Python

Pandas

NumPy

Scikit-learn

Data Cleaning

Feature Engineering

Statistical Analysis

Anomaly Detection

Risk Scoring

Power BI

Dashboard Development

Business Intelligence

Data Storytelling



---

⭐ Project Highlights

End-to-end analytics workflow

30 drivers analyzed

30 vehicles analyzed

Driver risk scoring

Vehicle health scoring

Sensor anomaly detection

Fleet-relative percentile analysis

Maintenance prioritization

Interactive Power BI dashboards

Driver and vehicle drill-down architecture

Explainable scoring methodology

Business-focused insights
























                 ▼
        Fleet Intelligence



























































































