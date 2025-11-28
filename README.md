# UnifiedMentor-Coke-Pepsi-Stock--Live-and-Updated

📊 Global Stock, Financial & Brand Sentiment Analysis | Business Analysist

This project was developed as part of my **Business Analyst Internship at Unified Mentor Pvt. Ltd.**  
The objective was to compare **Coca-Cola (KO)** and **PepsiCo (PEP)** across stock performance, financial health, analyst sentiment, and geographic footprint using **Power BI**, **DAX**, and **Python (yfinance)** for automated data extraction.

---

## 🧠 Project Objective

The goal of the dashboard is to:

- Analyze **stock price performance** (short-term & long-term) for KO & PEP.
- Track **returns** across multiple horizons: 1D, 1W, 1M, 3M, 6M, 1Y, 5Y, YTD, 52W range.
- Evaluate **financial strength**: Revenue, Net Income, EBITDA, Free Cash Flow, Margins, ROI, Debt-to-Equity.
- Compare **analyst recommendations & sentiment** using rating distributions and sentiment score.
- Understand **geo-distribution of revenue/exposure** across key regions & countries.
- Provide an **Executive Summary** view for stakeholders: which brand is performing better overall and why.
- Offer **Settings & Search utilities** for a self-service analytics experience.

---

## ⚙️ Tech Stack

**Power BI** → Data modeling, dashboard development, storytelling  
**DAX** → KPIs, time intelligence, financial ratios, sentiment scoring  
**Python (yfinance)** → Stock price, financials, balance sheet, recommendations extraction  
**Excel / CSV** → Intermediate data cleaning and storage  
**GitHub** → Version control & documentation  

---

## 🧾 Data Sources

| Source | Description |
|--------|-------------|
| `stock_ko_pep.csv` | Daily OHLCV data for KO & PEP with technical flags (1D, 1W, 1M, 1Y, 5Y, YTD, 52W) |
| `finance_ko_pep.csv` | Annual financial statements (Revenue, NI, EBITDA, COGS, Opex, margins) |
| `balance_ko_pep.csv` | Balance sheet metrics (Total Debt, Net Debt, Equity, Liabilities) |
| `reco_ko_pep.csv` | Analyst recommendation trends (Strong Buy, Buy, Hold, Sell, Strong Sell) |
| `geo_performance.csv` | Regional & country-wise revenue / exposure split for KO & PEP |
| `DateTable` | Calendar table used for time intelligence & slicing |
| `DimCompany` | Small dimension for KO/PEP metadata: ticker, name, logo, brand color |

_All core market & fundamentals data were collected using **Python (yfinance)** and exported as CSV for Power BI._

---

## 🧩 Dashboard Pages

---

### 🏠 **Page 1 – Home / Navigation Hub**

**Focus:** Clean entry point + brand identity + navigation 
<img width="806" height="434" alt="KOPEPFRONTPAGE" src="https://github.com/user-attachments/assets/a10aa530-8274-4051-9c3e-ca76a9f32be1" />


**Includes:**

- 🔘 Navigation cards to:
  - Geo Distribution 
  <img width="892" height="453" alt="kopepGEO" src="https://github.com/user-attachments/assets/491fa2dc-0ffa-4ee6-9d64-706fd5657c08" />

  - Stock Analysis  
  <img width="896" height="452" alt="kopepStock" src="https://github.com/user-attachments/assets/1242e2cb-aa1a-46bf-91e1-0f729d7f1d75" />

  - Finance & Cost  
  <img width="895" height="451" alt="KOPEPFINANCE" src="https://github.com/user-attachments/assets/687db959-406b-4d75-8232-349d2abc7f4a" />

  - Brand Insights  
  <img width="897" height="456" alt="KOPEPBRAND" src="https://github.com/user-attachments/assets/5d8a92ed-5890-42f3-bcf0-201ec26db088" />

  - Executive Summary (Reports)  
  <img width="898" height="460" alt="KOPEPREPORT" src="https://github.com/user-attachments/assets/c96360bd-d50a-4bba-b96c-068a50afa215" />

- 🔄 Brand toggle (Coca-Cola / PepsiCo / Both)  
- ⚙️ Settings icon → opens Settings Panel page  
- 🔍 Search icon → opens Search & Insights page  
- 🥤 Split layout with Coca-Cola & Pepsi visual branding


