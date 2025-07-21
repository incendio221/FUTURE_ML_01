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
    <img width="1378" height="774" alt="Screenshot 2025-07-16 151435" src="https://github.com/user-attachments/assets/71b98ad9-3125-405f-972a-351289833a90" />

  **National Forecast**

  - Interactive time series with date slicer
  - Monthly/seasonal breakdowns
  - Key statistics (average, max, min, volatility)
    <img width="1376" height="772" alt="Screenshot 2025-07-16 151445" src="https://github.com/user-attachments/assets/47b45d75-7d43-4878-bb8d-40efd20125cc" />

  **Regional Analysis**

  - Multi-region comparison (line/bar charts)
  - Regional performance table and ranking
    <img width="1375" height="768" alt="Screenshot 2025-07-16 151452" src="https://github.com/user-attachments/assets/a2a91624-0df5-46c6-beeb-f1838b3e3d70" />

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
