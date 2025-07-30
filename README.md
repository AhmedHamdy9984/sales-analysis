# 🛍️ Shopping Trends Dashboard Project

This project is an end-to-end data analysis solution that explores shopping trends by combining **SQL, Python, and Power BI**.

---

## 📊 Project Overview

The goal of this project is to analyze consumer shopping behavior using historical shopping data and present actionable insights through an interactive Power BI dashboard.

---

## 🔧 Tools & Technologies Used

- **SQL Server**: Data storage and querying (via DirectQuery).
- **Python (Pandas, matplotlib, seaborn)**: Exploratory Data Analysis (EDA) and preprocessing.
- **Power BI**: Interactive dashboard creation.
- **GitHub**: Version control and project publishing.

---

## 🧩 Data Source

- **Dataset**: [Shopping Trends Dataset]
- **Tables Used**:  
  - `Customer_Profile`
  - `Purchase_Behavior`
  - `Spending_Data`
  - `Frequency_of_Purchases`

---

## ⚙️ Project Workflow

1. **Data Upload**  
   Uploaded raw CSVs to SQL Server database.

2. **Data Modeling**  
   Created relationships between key tables (customer ID, product category, etc.).

3. **EDA with Python**  
   Connected Python to SQL using `pyodbc` and `pandas` to:
   - Clean data
   - Understand customer segments
   - Perform insights like top products, spending patterns, seasonal trends

4. **Power BI Dashboard**  
   Built an interactive dashboard with pages:
   - Overview
   - Customer Profile
   - Spending Insights
   - Segmentation View

---

## 📈 Key Insights

- High-value and frequent buyers segmentation
- Average spending by gender, age, and category
- Product trends and seasonal behavior
- Rare buyers and low purchase frequency

---

## 📌 How to Use

1. Clone the repo or download the `.pbix` file
2. Open the dashboard in **Power BI Desktop**
3. Connect to your SQL Server (if you want live data)

---

## 📎 Project Author

👤 Ahmed Hamdy  
🔗 [LinkedIn]((https://www.linkedin.com/in/ahmed-hamdy-56a0972a3/))
📧 ahmed.hamdy9984@gmail.com
