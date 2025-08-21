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

---

## 🔹 How to Run This Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/amazon-sales-analysis.git
cd amazon-sales-analysis

### 2️⃣ Install Dependencies
```bash
Make sure you have Python installed, then run:

pip install -r requirements.txt

3️⃣ Configure SQL Connection

Open Data Cleaning_Amazon-Sales.py (or your Python script)

Update your SQL Server credentials:

server = 'YOUR_SERVER_NAME'
database = 'YOUR_DATABASE_NAME'
username = 'YOUR_USERNAME'
password = 'YOUR_PASSWORD'

4️⃣ Run the ETL Pipeline
```bash
python Data Cleaning_Amazon-Sales.py

5️⃣ Run SQL Analysis

Open your SQL client (e.g., SQL Server Management Studio)

Execute queries in sql/Data Analysis_Amazon-Sales.sql to generate insights:

Top products by revenue

Best-selling products by region

Month-over-month sales comparison

Category-wise peak months

Sub-category profit growth


