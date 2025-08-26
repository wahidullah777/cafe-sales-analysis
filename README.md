# cafe-sales-analysis
☕ A complete end-to-end data cleaning + EDA project on cafe sales data. Cleaned messy dataset, handled missing values, and created visualizations to extract business insights.

### 1. Data Cleaning
- Removed rows with excessive missing values  
- Replaced `"Unknown"` / `"Error"` entries with `NaN`  
- Imputed missing values using:
  - **Mean** → numerical columns  
  - **Mode** → categorical columns  
  - **Forward fill (ffill)** → dates  
- Converted `Transaction Date` to proper datetime format  
- Converted `Quantity`, `Price Per Unit`, and `Total Spent` into numeric types  

### 2. Exploratory Data Analysis (EDA)
- **Total spending by payment method**  
- **Revenue distribution across locations**  
- **Top 10 items by quantity sold**  
- **Top 10 locations by revenue**  
- **Daily sales trend**  
- **Distribution of price per unit**  
- **Bubble chart: Item vs Total Spent vs Quantity**  

---

## 📊 Visualizations
Some of the visual insights include:
- 📊 **Bar Charts** → Payment methods, Locations, Top items  
- 📈 **Line Chart** → Daily sales trend  
- 🥧 **Pie Charts** → Payment method distribution, Item revenue share  
- 🔵 **Scatter Plot** → Quantity vs Total Spent  
- 🔮 **Bubble Chart** → Item-wise revenue contribution  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy** → Data cleaning & preprocessing  
- **Matplotlib, Seaborn** → Data visualization  

---
