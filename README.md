# -Supermart-Grocery-Sales--Retail-Analytics-Project
This project analyzes sales performance data from **Supermart Grocery**, a retail chain, to gain insights into sales trends, profitability, and customer behavior.   The project demonstrates **data cleaning in Excel**, **exploratory data analysis (EDA) and visualization in Python**, and concludes with actionable insights for decision-making.

## 📊 Dataset
**Source:** Internal dataset (cleaned and prepared manually).  
**File used:** `Supermart_Grocery_Sales_Cleaned.xlsx` / `.csv`  
**Rows:** ~10,000  
**Columns:** 16  

### Key Columns:
| Column | Description |
|:--------|:-------------|
| `Order_ID` | Unique ID for each order |
| `Customer_Name` | Customer’s name |
| `Category` | Product category (e.g., Fruits, Beverages) |
| `City`, `State`, `Region` | Customer location details |
| `Order_Date` | Date of the order |
| `Sales`, `Profit`, `Discount` | Financial metrics |
| `Order_Year`, `Order_Month_Name`, `Order_Day` | Derived date columns |
| `Profit_Margin_Pct` | Calculated profit margin |

---

## 🧹 Excel Stage — Data Cleaning & Transformation
1. Fixed inconsistent date formats (`Order Date` column).
2. Removed duplicates and blank rows.
3. Created new columns for:
   - `Order_Year`, `Order_Month_No`, `Order_Month_Name`, `Order_Day`
4. Verified `Sales`, `Profit`, and `Discount` for negative or missing values.
5. Exported the cleaned file to `Supermart_Grocery_Sales_Cleaned.csv`.

### 📈 Excel Dashboard Highlights:
- **KPIs:** Total Sales, Total Profit, Average Discount, Profit Margin %  
- **Charts:**  
  - Monthly Sales Trend  
  - Top 5 Product Categories  
  - Regional Performance Comparison  
  - Profit Margin Distribution  

---

## 🐍 Python Stage — EDA & Insights
Performed in Jupyter Notebook (`Supermart_Grocery_Sales_Analysis.ipynb`).

### Key Steps:
- Imported and explored the dataset (`pandas`, `numpy`).
- Checked data quality (missing values, types, outliers).
- Visualized:
  - Sales vs Profit trends by month (`matplotlib`, `seaborn`)
  - Top-performing regions and categories
  - Discount vs Profit correlations
- Derived insights:
  - Certain months drive 70% of total sales.
  - South region shows steady sales but lower margins.
  - Over-discounted categories underperform.

📊 Key Insights

✅ Top Category: Snacks & Beverages drive the highest revenue.
✅ Most Profitable Region: West region.
✅ Month with Peak Sales: March & December.
✅ Average Profit Margin: ~18%.

🛠️ Tools Used
Tool	Purpose
Microsoft Excel	Data cleaning, Pivot charts, Dashboard
Python (pandas, matplotlib, seaborn)	Data analysis and visualization
Jupyter Notebook	Documentation and reproducible code

🧠 What I Learned

How to clean and standardize real-world retail data in Excel.

Handling inconsistent date/time formats.

Automating analysis with Python.

Building dashboards and explaining business KPIs visually.

🧩 Author

  Yaswanth Rosannagari
📧 [yaswanth8460@gmail.com.com]
🔗 https://www.linkedin.com/in/yashwanthrosannagari123/
 | https://github.com/yashwanth9381

