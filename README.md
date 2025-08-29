# Data Science Assignment – Trader Behavior vs Market Sentiment

## 📌 Overview  
This project analyzes the relationship between **trader behavior** (profitability, risk, volume, and trade direction) and **market sentiment** (Fear vs Greed).  

The analysis uses two datasets:  
1. **Bitcoin Market Sentiment Dataset**  
   - Columns: `Date`, `Classification` (Fear / Greed)  
2. **Historical Trader Data from Hyperliquid**  
   - Columns include: `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, etc.  

> ⚠️ Note: The dataset provided did not include a `leverage` column, so leverage analysis could not be performed.

---

## 📂 Project Structure  


---

## ⚙️ How to Run  

1. Open `notebook_1.ipynb` in **Google Colab**.  
2. Download the datasets from Google Drive:  
   - [Historical Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)  
   - [Fear & Greed Index](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)  
3. Run the notebook step by step:  
   - Data loading & cleaning  
   - Merge trader data with sentiment  
   - Perform EDA (PnL, risk, volume, trade direction)  
   - Generate plots (saved in `/outputs/`)  
   - Export final report (`ds_report.pdf`)  

---

## 📊 Key Insights  

- **Profitability**: PnL varies significantly across Fear vs Greed.  
- **Risk**: Volatility of PnL is higher during extreme sentiment phases.  
- **Volume**: Trade sizes are generally larger in Greed phases.  
- **Direction**: Long vs Short preferences shift depending on sentiment.  

---

## 🚀 Submission  

- **Colab Notebook Link**: https://colab.research.google.com/drive/1Y2jEH8rSvSANd8Zkwo-ZXGb0o6CKLCXa?usp=sharing 
- **GitHub Repository Link**: https://github.com/NirjaraSK/ds_Nirjara  
