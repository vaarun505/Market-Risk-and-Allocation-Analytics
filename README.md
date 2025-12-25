# 📊 Market Risk & Portfolio Allocation Analytics

An end-to-end **investment analytics project** focused on **real-world market risk analysis and portfolio construction** using historical equity data.

This project mirrors how **actual portfolio managers and risk analysts** evaluate stocks, manage risk, and benchmark performance — not theoretical or academic finance.

---

## 📌 Project Overview

This project conducts a complete **market risk and portfolio analytics study** using real US equity market data.

### 🎯 Primary Objectives
- 📈 Analyze long-term stock behavior  
- ⚠️ Quantify market-level and asset-level risk  
- 🧩 Construct a diversified equity portfolio  
- 📊 Objectively compare portfolio performance against the **S&P 500 benchmark**

Every step is designed to reflect **practical investment decision-making**, not textbook formulas.

---

## ❓ Key Questions Addressed

This project answers four core investment questions:

1. 📆 How do selected large-cap stocks behave over long investment horizons?
2. ⚖️ How risky are individual stocks relative to the overall market?
3. 🧠 Can diversification effectively reduce portfolio-level risk?
4. 🏁 Does the constructed portfolio outperform the benchmark on a **risk-adjusted basis**?

---

## 🛠 Tools & Technologies Used

- 🐍 **Python**
- 🧹 **Pandas** – data handling & transformations  
- 🔢 **NumPy** – numerical computations  
- 📊 **Matplotlib / Seaborn** – data visualization  
- 🌐 **yFinance** – real financial market data  
- 🧠 **Statsmodels** – Fama–French factor regression  


---

## 📁 Project Structure

```text

📊 MARKET RISK & ALLOCATION ANALYTICS
│
├── 📂 data/
│   ├── 🗃 raw/            → raw downloaded market data
│   ├── 🧹 processed/      → cleaned, aligned & analysis-ready datasets
│
├── 📓 notebooks/
│   ├── 01_Data_collection.ipynb        → data sourcing & cleaning
│   ├── 02_Market_EDA.ipynb              → exploratory market analysis
│   ├── 03_Risk_Analysis.ipynb            → volatility, drawdowns & risk metrics
│   ├── 04_Factor_Analysis.ipynb          → Fama–French factor modeling
│   ├── 05_Portfolio_Construction.ipynb  → portfolio building & benchmarking
│
├── 📤 outputs/
│   ├── 📈 figures/        → final visualizations & plots
│   ├── 📊 tables/         → summary statistics & result tables
│
├── 🧩 src/                → helper utilities & reusable functions
├── 📝 README.md           → project documentation



## 🔹 Phase-Wise Project Breakdown
---
### 🟦 Phase 1 — Setup & Environment

**🎯 Purpose**  
Establish a clean, reproducible analytics environment.

**🔧 Key Actions**
- 📦 Imported required Python libraries  
- 📊 Defined stock universe (US large-cap equities)  
- 🗓 Fixed analysis window (2010–2024)  
- 🗂 Created a structured folder layout  

📌 *This phase ensures discipline, organization, and reproducibility.*

---

### 🟦 Phase 2 — Data Collection & Cleaning

**🎯 Purpose**  
Obtain clean, reliable, and aligned market data.

**🔧 Key Actions**
- 📥 Downloaded stock price & volume data using **yFinance**  
- 📈 Downloaded benchmark data (S&P 500)  
- 🧮 Downloaded **Fama–French factor data**  
- ✅ Used **Adjusted Close prices** for accuracy  
- 🧹 Removed missing values  
- 🔗 Aligned dates across all datasets  
- 🚦 Performed liquidity sanity checks  

**📁 Frozen Output Files**
- `prices_final.csv`  
- `benchmark_final.csv`  
- `ff_factors.csv`  

📌 *After this phase, all datasets are clean, aligned, and analysis-ready.*

---

### 🟦 Phase 3 — Market Risk & Performance Analysis

**🎯 Purpose**  
Understand how individual stocks and the market behave under risk.

**📊 Key Analyses**
- 📈 Daily & cumulative returns  
- 📉 Annualized volatility  
- 🔻 Downside risk  
- 🔄 Rolling volatility (market stress)  
- 📉 Drawdowns & maximum drawdown  
- ⚖ Risk-adjusted metrics (Sharpe, Sortino)  
- 🧠 Fama–French factor exposure (alpha & betas)  

**💡 Key Insights**
- Volatility and downside risk vary significantly across stocks  
- Market risk is cyclical but persistent  
- Drawdowns are normal and long-lasting in equity markets  
- Many stocks outperform mainly due to **market exposure**, not true alpha  

📌 *This phase builds strong risk intuition before portfolio construction.*

---

### 🟦 Phase 4 — Portfolio Construction & Evaluation

**🎯 Purpose**  
Convert asset-level analysis into a real investment portfolio and evaluate its effectiveness.

**🔧 Key Actions**
- 🧩 Constructed a diversified equity portfolio using cleaned returns  
- ⚖ Assigned and normalized portfolio weights  
- 📈 Computed daily and cumulative portfolio returns  
- 📊 Benchmarked portfolio against the **S&P 500**  
- 📉 Evaluated risk using volatility and maximum drawdown  
- 📊 Visualized allocation, performance, volatility, and drawdowns  

**🏁 Results & Findings**
- Portfolio is well diversified (no single stock dominance)  
- Higher cumulative returns than the benchmark  
- Smoother growth and lower volatility  
- Smaller maximum drawdown than the benchmark  
- Faster recovery during market stress periods  

📌 **Overall Outcome**  
The portfolio delivers **superior risk-adjusted performance**, outperforming the benchmark while taking **less downside risk**.




