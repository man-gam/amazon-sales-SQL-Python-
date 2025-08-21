# 📊 Amazon Sales Data Analysis (Python + SQL)

## 🔹 Project Overview
This project analyzes **Amazon Sales Data** (from Kaggle) to uncover trends in revenue, profitability, and regional sales patterns.  
The project demonstrates a full **ETL + Analytics workflow**:

1. **Extract & Load Data**: Pulled dataset via Kaggle API.  
2. **Data Cleaning (Python / Pandas)**:  
   - Handled null values  
   - Removed irrelevant columns  
   - Generated new calculated columns  
   - Converted date columns to proper datetime format  
3. **Load to SQL Server**: Stored cleaned data in SQL Server.  
4. **SQL Analysis**: Wrote advanced SQL queries (CTEs & Window Functions) to generate insights.  

---

## 🔹 Tech Stack
- **Python**: Pandas, NumPy, SQLAlchemy, pyodbc, Kaggle API  
- **SQL Server**: T-SQL, CTEs, Window Functions  
- **GitHub**: Version control & project showcase  

---

## 🔹 SQL Analysis Performed
1. **Top 10 highest revenue-generating products**  
2. **Top 5 best-selling products by region**  
3. **Month-over-Month sales comparison (2022 vs 2023)**  
4. **Category-wise highest sales month**  
5. **Sub-category with highest profit growth (2023 vs 2022)**  

## 🔹 Challenges & Solutions

This project involved several challenges which helped demonstrate problem-solving and technical skills:

1. **Data Collection & Access**
   - Challenge: Pulling data via Kaggle API and ensuring consistent dataset versions.
   - Solution: Configured Kaggle API keys and downloaded dataset programmatically.

2. **Data Cleaning**
   - Challenge: Handling missing/null values in critical columns and standardizing date formats.
   - Solution: Used Python (Pandas) to fill missing values, drop irrelevant columns, and convert `order_date` to datetime.

3. **ETL & SQL Loading**
   - Challenge: Duplicate `order_id` values causing primary key conflicts during insertion.
   - Solution: Identified and removed duplicates before loading data into SQL Server.

4. **SQL Analysis**
   - Challenge: Writing complex queries (CTEs, Window Functions) for top-N analysis and month-over-month comparisons.
   - Solution: Created modular queries with CTEs and window functions for accurate insights.

5. **Business Insights**
   - Challenge: Translating raw sales data into actionable insights.
   - Solution: Generated reports on top products, regional trends, seasonal patterns, and profit growth, and recommended business strategies.

---

## 🔹 Insights
- 📊 A small set of products contributed to the majority of sales revenue.  
- 🌍 Regional demand patterns varied significantly across markets.  
- 📅 Strong seasonality observed — peak months aligned with festive/holiday periods.  
- 🏷️ Different categories peaked in different months, showing diverse seasonality.  
- 💰 Some sub-categories saw **significant profit growth YoY**, indicating expansion opportunities.  

---

## 🔹 Business Recommendations
1. **Double down on high-revenue products** with strong marketing & inventory planning.  
2. **Adopt region-specific sales strategies** — tailor campaigns for local demand.  
3. **Leverage seasonality** — launch promotions during festive & year-end spikes.  
4. **Category campaigns** — maximize revenue by focusing on category-specific peak months.  
5. **Profit growth strategy** — invest in high-growth sub-categories, re-evaluate pricing for lagging ones.  





