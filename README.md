
# 💼 Financial KPI Analysis for a Startup

## 📌 Objective

Analyze key financial performance indicators (KPIs) for an early-stage startup to support strategic decision-making and investor reporting. Metrics include:

- Revenue
- Customer Acquisition Cost (CAC)
- Lifetime Value (LTV)
- Burn Rate
- Runway
- Cohort Retention

---

## 🛠️ Tools Used

- **Python**: `Pandas`, `Matplotlib`, `Seaborn`
- **Power BI**: Dashboard creation & visualization
- **Excel**: Data modeling & export

---

## 🧪 Step-by-Step Process

### 1. Data Cleaning & Preparation
- Imported dataset using Pandas.
- Cleaned column names and standardized formats.
- Converted date fields to `datetime`, extracted `Month-Year`.
- Removed duplicates, replaced missing values with 0.

### 2. Exploratory Data Analysis (EDA)
- Checked for nulls, duplicates, and outliers.
- Analyzed trends in revenue, customer growth, and expenses.
- Visualized patterns using `matplotlib` and `seaborn`.

### 3. KPI Calculations
- **CAC** = Marketing Expenses / New Customers
- **ARPU** = Revenue / Total Customers
- **Lost Customers** = Last Month Customers + New Customers - Current Customers
- **Churn Rate** = Customers Lost / Previous Month Customers
- **Average Lifespan** = 1 / Churn Rate
- **LTV** = ARPU × Average Lifespan
- **Burn Rate** = (Marketing + Operating Expenses) - Revenue
- **Runway** = Cash on Hand / Burn Rate
- **LTV:CAC Ratio** = LTV / CAC
- Customer Segmentation based on LTV vs CAC

### 4. Power BI Dashboard
- Line charts: Revenue, CAC, LTV, Burn Rate
- KPI Cards: CAC, LTV, Runway, LTV:CAC Ratio
- Interactive slicers for Month-Year and filters
- Scatter and column charts for customer value segmentation

### 5. Cohort Retention Analysis
- Created cohorts using signup month.
- Simulated 12-month retention with decay logic.
- Retention matrix heatmap (matplotlib + seaborn).
- Exported matrix to CSV for Power BI integration.
- Added dashboard bookmarks and summary cards (e.g. Avg Month 3 Retention).

---

## 🔍 Key Insights

- **Growth**: Steady increase in revenue and customer base.
- **Customer Acquisition**: LTV > CAC in later months—efficient acquisition strategy.
- **Financial Health**: Burn rate decreased, improving startup runway.
- **Retention**: Improved retention in newer cohorts, hinting at better onboarding or product-market fit.

---

## 📦 Deliverables

- 📁 `RAW_startup_data.xlsx` – RAW file(Not Cleaned dataset)
- 📘 `Financial KPI Analysis.ipynb` – Python notebook with KPI analysis & cohort logic
- 📊 `Startup.pbix` – Power BI interactive dashboard
- 📁 `cleaned_startup_data.csv` – Cleaned dataset
- 📈 `cohort_retention_percentage.xlsx` – Cohort matrix
- 📄 `Startup_KPI_Model_Template.xlsx` – Excel KPI model template
- 📑 Final Report – PDF summary

---

## 🧑‍💻 Prepared By

**M Chethan**  
Internship Project – *Financial KPI Analysis for Startups*  
📅 Date: 19-05-2025
