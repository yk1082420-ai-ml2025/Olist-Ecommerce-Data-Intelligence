# 📊 Olist E-commerce Data Intelligence Analysis

## 🌟 Executive Summary
This project is an end-to-end data analysis of the **Olist Brazilian E-commerce Dataset**. By integrating 9 separate relational tables, I uncovered critical business insights regarding sales drivers, customer demographics, and delivery efficiency.



## 🛠️ Tech Stack & Skills
- **Language:** Python 3.x
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Seaborn, Matplotlib
- **Key Skills:** Data Merging (Inner/Left Joins), Feature Engineering, Data Cleaning, Statistical Plotting.

## 📂 Data Architecture
The project involved linking multiple datasets to create a single **Master Dataframe**. The key relations included:
- **Orders & Customers:** Linked via `customer_id`
- **Orders & Items:** Linked via `order_id`
- **Items & Products:** Linked via `product_id`



## 📈 Key Insights & Findings
1. **Top Revenue Category:** **Health & Beauty** was identified as the highest revenue-generating category, indicating a strong online market for personal care in Brazil.
2. **Geographic Stronghold:** **São Paulo (SP)** is the primary hub, contributing to the majority of total sales.
3. **Logistics Analysis:** Engineered a `delivery_time` metric which revealed an average shipping duration of ~12 days.
4. **Data Integrity:** Cleaned ~3,000 missing delivery records by classifying order statuses (shipped, canceled, processing) to ensure 100% accuracy in sales reporting.

## 🚀 How to Use
1. Clone the repository.
2. Ensure you have the datasets in the `data/` folder.
3. Open `main.ipynb` in Jupyter Notebook or VS Code.
4. Run all cells to generate analysis and visualizations.

---
**Contact:** [https://www.linkedin.com/in/yogendrakumar-ai-ml2025]
