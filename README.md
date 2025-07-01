# Data_analysis-by-python
# 🏠 Diwali Sales Data Analysis Project

Welcome to the **Diwali Sales Data Analysis** project! This repository provides a complete breakdown of data cleaning, exploration, and visualization steps performed on a dataset of Diwali sales to generate useful business insights.

---

## 🔍 Project Overview

This project aims to analyze sales trends based on demographic factors such as gender, age, marital status, state, and product categories to uncover useful insights for business strategy.

* **Dataset:** `Diwali Sales Data.csv` (11239 rows, 13 columns)
* **Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

---

## 🌐 Objective

* Clean the data by removing unnecessary/null columns
* Perform Exploratory Data Analysis (EDA)
* Visualize trends based on:

  * Gender
  * Age Group
  * State
  * Marital Status
  * Occupation
  * Product Categories
* Identify top-performing product categories and customer segments

---

## 📚 Dataset Info

**Columns:**

* `User_ID`, `Cust_name`, `Product_ID`, `Gender`, `Age Group`, `Age`, `Marital_Status`, `State`, `Zone`, `Occupation`, `Product_Category`, `Orders`, `Amount`

---

## ⚖️ Data Cleaning Steps

* Removed null columns: `Status`, `unnamed1`
* Dropped rows with null `Amount`
* Converted `Amount` from float to int
* Renamed `Marital_Status` to `shadi` (optional visualization clarity)

---

## 📊 Key Visualizations

### 1. **Gender-wise Count & Revenue**

* Count plot of purchases by gender
* Total revenue by gender (barplot)

### 2. **Age Group Analysis**

* Count of buyers by Age Group & Gender (hue)
* Revenue distribution across age groups

### 3. **State-wise Analysis**

* Top states by number of orders
* Top states by total sales revenue

### 4. **Marital Status & Sales**

* Count of orders by marital status
* Combined gender + marital status revenue analysis

### 5. **Occupation Analysis**

* Count of orders per occupation
* Revenue by different occupations

### 6. **Product Category Analysis**

* Top-selling product categories (by count & revenue)
* Most ordered Product IDs

---

## 🎓 Skills Practiced

* Data Cleaning (dropping, renaming, type conversion)
* Exploratory Data Analysis (EDA)
* GroupBy operations with aggregation
* Data Visualization using Seaborn & Matplotlib
* Understanding business metrics (Orders, Revenue)

---

## 📊 Insights & Conclusions

* Female customers made more purchases
* Age group 26-35 was the most active
* Married individuals tend to spend more
* Western zone and Maharashtra contributed the highest revenue
* Food category was the top-selling product type

---

## Dashboard review
[Dashboard_image](https://github.com/Krishna-0286/Data_analysis-by-python/blob/main/Dipavali_data_analysis.png)

## 💼 Usage

Clone the repo and run the notebook using Jupyter or any Python environment:

```bash
pip install pandas matplotlib seaborn numpy
jupyter notebook
```

---

## 🏆 Author

**Krishna Kumar**
Aspiring Data Analyst | Skilled in Python, Pandas, SQL, Power BI,

---

## ✨ License

Free to use for educational or portfolio purposes.
