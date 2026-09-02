# South India E-Commerce: Festival & Seasonal Sales Analysis (Electronics)

## 📌 Project Overview
This project analyzes electronics sales patterns across five South Indian states — Tamil Nadu, 
Karnataka, Kerala, Andhra Pradesh, and Telangana — to understand how regional festivals and 
seasons influence e-commerce buying behavior. The goal was to move beyond generic "sales trend" 
analysis and uncover region-specific, culturally-relevant insights that a typical pan-India 
analysis would miss.

## 🎯 Objective
- Identify which festivals (regional and national) drive the strongest sales spikes
- Determine seasonal buying patterns across the calendar year
- Compare festival vs. non-festival purchasing behavior across product subcategories
- Translate findings into actionable business recommendations

## 🗂️ Dataset
- **Source:** Amazon India e-commerce sales data (Kaggle)
- **Scope:** Filtered to 5 South Indian states, electronics category
- **Size:** 12,714 transactions (2021–2025)
- **Key fields:** order date, state, city, subcategory, brand, final amount, festival tags, 
  customer tier, payment method

## 🛠️ Tools & Technologies
- **Python** (Pandas, Matplotlib, Seaborn) — data cleaning, festival-date tagging, exploratory analysis
- **Google Colab** — analysis environment
- **Microsoft Excel / Google Sheets** — initial data merging and filtering
- **Power BI** — interactive dashboard

## 🔍 Methodology
1. **Data Sourcing & Merging** — combined order, product, and regional data; filtered to South India
2. **Data Cleaning** — verified no missing values or duplicate transactions across 12,714 rows
3. **Festival Enhancement** — layered regional cultural festivals (Pongal, Onam, Ugadi, Vishu, 
   Ramadan, Christmas, Karthigai Deepam, etc.) onto existing commercial sale-event tags, using a 
   20-day pre-festival purchase window based on typical shopping behavior
4. **Exploratory Analysis** — sales by festival, monthly seasonality, state-wise distribution, 
   subcategory performance during festivals vs. regular days
5. **Dashboard Build** — translated findings into an interactive Power BI report with KPIs, 
   trend charts, and state-level filtering

## 📊 Key Findings
- **December sales are 63.8% above the yearly average**, driven by the Christmas + Karthigai 
  Deepam overlap; November is also elevated (+14.9%)
- **Average order value drops 15–21% across every subcategory during festival periods** — 
  festivals drive purchase volume, not higher-ticket spending
- **Karthigai Deepam and Pongal outperform** several longer/national sale events despite short 
  durations, highlighting the value of region-specific campaigns
- **Tamil Nadu (35.9%) and Karnataka (34.9%)** account for the majority of sales — closely 
  proportional to their share of total orders in the dataset

## 💡 Business Recommendations
See [full recommendations](#) in the analysis notebook — includes inventory timing, festival 
discount strategy, regional campaign prioritization, and data collection guidance.

## 📁 Repository Contents
- `analysis_notebook.ipynb` — full Python analysis (cleaning, festival tagging, EDA, visualizations)
- `south_india_dashboard_ready.csv` — cleaned dataset used for the dashboard
- `dashboard_screenshot.png` — Power BI dashboard preview
- `README.md` — this file

## 📷 Dashboard Preview
<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/6b5c8f4b-1650-4296-80d7-273dd5af4672" />


## 👤 Author
Ashika — M.Sc. Mathematics | Aspiring Data Analyst
