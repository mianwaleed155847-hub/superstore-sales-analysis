#  Superstore Sales Analysis

Exploratory Data Analysis (EDA) on US Superstore retail transactions using Python.  
Raw data was cleaned, engineered, and visualized to extract actionable business insights.

---

##  Tools & Libraries
- **Python** — Pandas, NumPy, Matplotlib, Seaborn

---

##  Project Structure
| File | Description |
|------|-------------|
| `superstore.ipynb` | Main notebook — cleaning + EDA |
| `Superstore.csv` | Raw dataset |
| `Superstore_Cleaned.csv` | Cleaned & feature-engineered dataset |

---

##  Data Cleaning & Feature Engineering
1. Loaded dataset and inspected shape, nulls, and duplicates
2. Checked and fixed data types for all columns
3. Converted `Order Date` and `Ship Date` to datetime format
4. Engineered new feature — `Shipping Days` (Ship Date − Order Date)
5. Extracted Month, Year, Day from Order Date for time-series analysis
6. Saved cleaned data as new CSV

---

## EDA & Visualizations
-  Sales Distribution (Histogram + KDE)
-  Sales Boxplot — Outlier Detection
-  Profit Distribution — Loss Detection
-  Discount vs Profit (Scatter Plot)
-  Total Sales by Category (Bar Chart)
-  Top 10 States by Profit (Horizontal Bar Chart)
-  Monthly Sales Trend 2014–2017 (Line Plot)

---

##  Key Insights
1. **Technology** is the highest-revenue category (~$830K total sales)
2. **California** and **New York** are the most profitable states (~$76K and ~$74K)
3. Discounts above **30%** consistently lead to **negative profit margins**
4. Sales show **year-over-year growth** with consistent **November peaks** (holiday season)
5. Sales distribution is **right-skewed** with significant high-value outliers

---

##  Author
**Waleed Ahmad**  
BS Data Science — Riphah International University  
[GitHub](https://github.com/mianwaleed155847-hub)
