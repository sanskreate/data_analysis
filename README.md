# **Telecom Customer Churn Analysis & Electric Vehicle Charging Demand Forecasting**

This repository contains two distinct but data-driven projects aimed at improving operational efficiency and customer retention strategies across different industries: telecom services and electric vehicle (EV) infrastructure.

## **Projects Overview**

### **1. Telecom Customer Churn Analysis**

This project focuses on analyzing and predicting customer churn in telecom services. The goal is to identify at-risk customers and provide actionable insights to develop targeted retention strategies using machine learning and data analytics.

#### **Key Insights:**
- Identifying patterns in **customer value**, **subscription length**, and **usage behavior** to predict churn.
- Proposing strategies such as **complaint resolution enhancement** and **usage-based interventions** to reduce churn.

#### **Technologies Used:**
- **Machine Learning**: Random Forest, Decision Tree Classifications
- **Data Analysis**: pandas, numpy, matplotlib, seaborn
- **SQL Database** for data aggregation

#### **Model Performance:**
- **Random Forest**: Precision (97%), Recall (95%), F1-Score (96%)
- **Decision Tree**: Precision (94%), Recall (97%), F1-Score (96%)

---

### **2. Electric Vehicle Charging Demand Forecasting**

This project uses time series forecasting to predict the demand for electric vehicle (EV) charging stations in Palo Alto, CA. It leverages historical charging data, weather conditions, and traffic events to recommend strategies for optimizing EV infrastructure.

#### **Key Insights:**
- Charging demand exhibits **temporal patterns** based on time of day and seasonality.
- Weather and **traffic congestion** influence charging duration and station accessibility.
- Forecasts inform strategies such as **capacity optimization**, **dynamic pricing**, and **station placement**.

#### **Technologies Used:**
- **Time Series Forecasting**: Prophet
- **Data Analysis**: pandas, numpy, matplotlib, seaborn
- **External Data**: Meteostat (weather), Traffic Data (events)

#### **Forecasting Results (kWh):**
- Next Day: **9.72 kWh**
- Next Month: **10.13 kWh**
- 1 Year: **11.65 kWh**

---

## **Repository Structure**

```bash
├── telecom-customer-churn-analysis/
│   ├── Churn.md
│   ├── Customer Churn.csv
│   ├── TeleChurnPred.ipynb
│   ├── Telecom Customer Churn Analysis.pptx
│   └── telecom churn.db
├── ev-charging-demand-forecasting/
│   ├── EV CHARGING TABLEAU DASHBOARD.docx
│   ├── EV.md
│   ├── EVCharging.twb
│   ├── EVForecast.twb
│   ├── EVforecast.ipynb
│   ├── Electric Vehicle Charging Demand Forecasting.pptx
│   ├── forecast 3months.csv
│   ├── forecast 6months.csv
│   ├── forecast_day.csv
│   ├── forecast_month.csv
│   ├── forecast_week.csv
│   └── forecast_year.csv
└── README.md
```

- **telecom-churn-analysis/**: Contains code, models, and notebooks related to the Telecom Customer Churn Analysis project.
- **ev-charging-demand-forecasting/**: Contains code, models, and notebooks for the EV Charging Demand Forecasting project.
- **README.md**: Contains the README file for both projects.

---

## **Requirements**

To get started with the projects, clone the repository and install the necessary dependencies:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Installation for Telecom Churn Analysis**

1. Navigate to the **telecom-customer-churn-analysis/** folder.
2. Open and run **TeleChurnPred.ipynb** in a Jupyter Notebook environment to reproduce the analysis and model training for customer churn prediction.
3. Use **telecom churn.db** for storing and querying data, and refer to **Churn.md** for project documentation.

---

## **Installation for Electric Vehicle Charging Demand Forecasting**

1. Navigate to the **ev-charging-demand-forecasting/** folder.
2. Open and run **EVforecast.ipynb** in a Jupyter Notebook environment to reproduce the time series forecasting and demand analysis for EV charging stations.
3. Use **EVCharging.twb** and **EVForecast.twb** for interactive Tableau visualizations.
4. Refer to **EV.md** for project documentation and insights.
5. Access the forecast data in **forecast_*.csv** files.

---

## **Key Features and Benefits**

### **Telecom Customer Churn Analysis**
- **Predict customer churn** with high accuracy.
- **Target at-risk customers** and implement retention strategies.
- **Optimize customer lifetime value (CLV)** through data-driven decision-making.

### **Electric Vehicle Charging Demand Forecasting**
- **Forecast EV charging demand** based on historical data and external factors.
- **Optimize infrastructure** by predicting station demand and operational strategies.
- **Improve user experience** with real-time availability forecasts and dynamic pricing.

---

## **Contributions**

Feel free to open issues, fork the repository, and submit pull requests if you'd like to contribute to either project. 

---
