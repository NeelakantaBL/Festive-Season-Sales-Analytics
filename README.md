# Festive-Season-Sales-Analytics
The analysis was performed using Python, Pandas, Matplotlib, and Seaborn.
# Diwali Sales Data Analysis

## 📌 Project Overview

This project analyzes **Diwali sales data** to understand customer purchasing behavior, sales patterns, product performance, and customer demographics.

The analysis was performed using **Python, Pandas, Matplotlib, and Seaborn**. Exploratory Data Analysis (EDA) was conducted to identify patterns across gender, age group, state, marital status, occupation, product categories, and product-level sales.

The project aims to identify the customer segments and product categories contributing most to sales and provide useful insights for improving marketing and sales strategies.

---

## 🎯 Business Problem

A retail business wants to better understand its customers and sales performance during the Diwali season.

The analysis focuses on questions such as:

* Which gender contributes more to sales?
* Which age group has the highest purchasing activity?
* Which states generate the most orders?
* How does marital status relate to purchasing behavior?
* Which occupations contribute the most to sales?
* Which product categories generate the highest sales?
* Which products are the most frequently ordered?

The objective is to use customer and sales data to identify high-performing customer segments, locations, and products.

---

## 📊 Dataset

The dataset contains customer demographic information and Diwali sales transaction details.

### Key Columns

| Column             | Description                |
| ------------------ | -------------------------- |
| `User_ID`          | Unique customer identifier |
| `Cust_name`        | Customer name              |
| `Product_ID`       | Product identifier         |
| `Gender`           | Customer gender            |
| `Age Group`        | Customer age group         |
| `Age`              | Customer age               |
| `Marital_Status`   | Customer marital status    |
| `State`            | Customer state             |
| `Zone`             | Geographic zone            |
| `Occupation`       | Customer occupation        |
| `Product_Category` | Product category           |
| `Orders`           | Number of orders           |
| `Amount`           | Purchase amount            |

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data loading, cleaning, transformation, and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development and analysis environment
* **CSV** – Source dataset

---

## 🔄 Project Workflow

```text
Raw Diwali Sales Dataset
          ↓
Data Loading
          ↓
Data Exploration
          ↓
Data Cleaning
          ↓
Exploratory Data Analysis
          ↓
Customer & Sales Analysis
          ↓
Visualizations
          ↓
Business Insights
```

---

## 🧹 Data Cleaning & Preparation

The raw dataset was prepared before performing the analysis.

### Key cleaning steps

* Loaded the CSV dataset using Pandas.
* Checked the dataset shape and structure.
* Inspected the first few records.
* Used `info()` and `describe()` for initial data understanding.
* Removed unrelated/blank columns:

  * `Status`
  * `unnamed1`
* Checked for missing values.
* Removed rows containing missing values.
* Converted the `Amount` column to integer format.
* Verified the cleaned dataset before performing EDA.

---

## 🔎 Exploratory Data Analysis

The project performs analysis across several dimensions.

### 1. Gender Analysis

Analyzed:

* Number of buyers by gender
* Total sales amount by gender

The analysis indicates that **female customers represent a larger share of buyers and have higher purchasing power** in the analyzed dataset.

---

### 2. Age Group Analysis

Analyzed customer purchasing behavior across different age groups.

The analysis shows that the **26–35 age group** represents a major customer segment, with female customers particularly prominent in this group.

---

### 3. State-wise Analysis

Analyzed the number of orders and total sales across states.

The analysis identifies **Uttar Pradesh, Maharashtra, and Karnataka** among the leading states by order volume.

---

### 4. Marital Status Analysis

Compared purchasing behavior across marital status and gender.

The analysis indicates that **married women** form an important customer segment and contribute significantly to purchasing activity.

---

### 5. Occupation Analysis

Analyzed customer distribution and total sales across different occupations.

The analysis identifies customers working in sectors such as:

* IT
* Healthcare
* Aviation

as important contributors to sales.

---

### 6. Product Category Analysis

Analyzed:

* Number of products/orders by category
* Total sales amount by product category

The analysis identifies **Food, Clothing, and Electronics** among the major product categories.

---

### 7. Top-Selling Products

Analyzed product-level order volumes using `Product_ID`.

The project identifies the **top 10 most-ordered products** based on total order count.

---

## 📈 Visualizations

The Python notebook uses **Matplotlib and Seaborn** to create visualizations such as:

* Customer count by gender
* Sales by gender
* Customer distribution by age group
* Age group by gender
* Sales by age group
* Orders by state
* Sales by state
* Customer distribution by marital status
* Sales by marital status and gender
* Customer distribution by occupation
* Sales by occupation
* Product category distribution
* Sales by product category
* Top 10 products by order volume

---

## 💡 Key Insights

The analysis highlights several important patterns:

* **Female customers** form a major portion of buyers and show higher purchasing power.
* Customers in the **26–35 age group** are a key customer segment.
* **Uttar Pradesh, Maharashtra, and Karnataka** are among the leading states by order volume.
* **Married women** are an important purchasing segment.
* Customers working in **IT, Healthcare, and Aviation** contribute significantly to sales.
* **Food, Clothing, and Electronics** are among the leading product categories.
* A small group of products contributes significantly to overall order volume.

---

## 📌 Business Recommendations

Based on the analysis, businesses can consider:

### 🎯 Target High-Value Customer Segments

Focus marketing campaigns on the **26–35 age group**, particularly female customers.

### 📍 Regional Marketing

Prioritize sales and promotional campaigns in high-performing states such as **Uttar Pradesh, Maharashtra, and Karnataka**.

### 👩 Customer-Specific Campaigns

Develop targeted offers for customer segments showing stronger purchasing behavior, particularly married women.

### 💼 Occupation-Based Marketing

Explore targeted campaigns for customers working in high-contributing occupations such as **IT, Healthcare, and Aviation**.

### 🛍️ Product Promotion

Focus promotional activities on high-performing categories such as **Food, Clothing, and Electronics**.

### ⭐ Best-Selling Product Strategy

Use top-selling products in promotional campaigns, bundles, and seasonal offers to increase sales.

---

## 📁 Project Structure

```text
Diwali-Sales-Data-Analysis/
│
├── Diwali Sales Data.csv
├── Python_Sales_Analysis-MM.ipynb
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open the Notebook

```bash
jupyter notebook
```

Open:

```text
Python_Sales_Analysis-MM.ipynb
```

### 4. Run the Analysis

Make sure the `Diwali Sales Data.csv` file is available in the appropriate project directory before running the notebook.

---

## 📦 Project Deliverables

* Python Jupyter Notebook
* Diwali Sales Dataset
* Exploratory Data Analysis
* Data Cleaning
* Data Visualizations
* Business Insights
* Business Recommendations

---

## 🧠 Skills Demonstrated

* Python
* Pandas
* NumPy
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis
* Customer Segmentation
* Sales Analysis
* Business Insights
* Data Storytelling

---

## 📄 Resume Project

**Diwali Sales Data Analysis | Python, Pandas, Seaborn**

---

## ⭐ Project Highlights

* Performed end-to-end **data cleaning and exploratory analysis**
* Analyzed **customer demographics and purchasing behavior**
* Identified **high-performing states and customer segments**
* Analyzed **product category and product-level performance**
* Created multiple visualizations using **Matplotlib and Seaborn**
* Derived business insights from real-world sales data
