# 📈 AI-Powered Sales Forecasting Dashboard

## 🚀 Project Overview

This project delivers a complete end-to-end predictive analytics solution for **retail sales forecasting**. Using historical transaction data, advanced time series modeling with **Facebook Prophet**, and interactive **Power BI dashboards**, it empowers retail businesses to:

- Anticipate future sales trends
- Optimize inventory levels
- Make informed, data-driven decisions

---

## 🔑 Key Features

- 🧹 **Automated Data Cleaning & Feature Engineering** using Python & Pandas
- ⏳ **Time Series Forecasting** with Facebook Prophet
- 📊 **Interactive Power BI Dashboard** for actionable insights
- 🔍 **Filters** by Category, Region, and Product
- 💡 **Insight Cards** highlighting top-selling items, low-performing periods, and recommendations
- 📄 **Business-Ready Reporting** with forecast summaries

---

## 🗂️ Data & Workflow

1. **Data Preparation**  
   Clean and structure raw sales data from `superstore_dataset.csv`.

2. **Feature Engineering**  
   Generate features such as:

   - Time-based indicators (month, year, weekday)
   - Seasonality signals
   - Holiday flags

3. **Forecasting**

   - Train Prophet models
   - Generate future sales forecasts (national + regional)

4. **Dashboarding**

   - Visualize historical trends and forecasts
   - Build Power BI dashboard with filters, KPIs, and insights

5. **Business Insights**  
   Summarize key takeaways, trends, and strategic recommendations.

---

# 🚀 Quick Start

### **Python Data Pipeline**

```bash
pip install -r requirements.txt
# Run notebooks in order for data prep and forecasting
```

### 1. Jupyter Notebooks (Python)

- Navigate to the `notebooks/` folder
- Run the notebooks in order:
  - `01_exploration.ipynb` (EDA & cleaning)
  - `02_feature_engineering.ipynb` (feature creation)
  - `03_dashboard_data_preparation.ipynb` (forecast prep)
- Outputs (e.g., `forecast_results.csv`) are saved in `data/processed/`

### 2. Power BI Dashboard

- Open `dashboard.pbix` in Power BI Desktop
- Connect to the processed CSV files
- Explore interactive visuals, filters, and insight cards

  **Overview**

  - Executive KPIs (latest forecast, average, regions)
  - National forecast trend (with confidence intervals)
  - Regional performance comparison
    <img width="1401" height="784" alt="Screenshot 2025-07-21 154024" src="https://github.com/user-attachments/assets/ff71243d-3616-4249-953f-4906150371ab" />

  **National Forecast**

  - Interactive time series with date slicer
  - Monthly/seasonal breakdowns
  - Key statistics (average, max, min, volatility)
 <img width="1400" height="789" alt="Screenshot 2025-07-21 154030" src="https://github.com/user-attachments/assets/df804eca-3332-4b99-8df7-2b019fa73db7" />

    
  **Regional Analysis**

  - Multi-region comparison (line/bar charts)
  - Regional performance table and ranking
<img width="1397" height="791" alt="Screenshot 2025-07-21 154036" src="https://github.com/user-attachments/assets/4c4cfb7a-da00-4cf1-9a2c-90240620a58e" />
  

## 📂 Folder Structure

```
FUTURE_ML_01/
│
├── data/
│   ├── raw/                # Original datasets
│   ├── regions/            # Regional forecast CSVs
│   └── processed/          # Cleaned & forecasted data for Power BI
├── notebooks/              # Jupyter notebooks (EDA, features, prep)
├── dashboard.pbix  # Power BI dashboard
├── README.md
└── ...
```

## 📊 Business Value

- **Forecast demand** to optimize inventory and reduce stockouts
- **Identify sales drivers** by category, region, and season
- **Enable data-driven planning** for promotions and resource allocation

## 👤 Author

**Developed by:**

- Ankur Yadav
- [LinkedIn](https://www.linkedin.com/in/ankur-yadav-0403bb2a9)
- [GitHub](https://github.com/incendio221)
