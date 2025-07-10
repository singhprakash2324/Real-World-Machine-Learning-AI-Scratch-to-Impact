# 🛒 Walmart Data Analysis Project

## 📊 Overview

This project presents an end-to-end data analysis pipeline for Walmart sales data using Python and MySQL. The goal is to extract actionable business insights such as sales trends, customer behavior, and profit metrics from real-world retail data.

---

## 🔧 Tools & Technologies

- Python 3.x
- Jupyter Notebook
- MySQL
- Pandas, NumPy
- Matplotlib, Seaborn
- MySQL Connector (Python)

---

## 🗂️ Folder Structure

Walmart_Analysis_Project/
- |-- data/       # Raw and cleaned dataset
- |--notebook/    # Jupyter Notebook for analysis
- |--outputs/     #Saved charts/figures
- |--README.md    #Project overview ans instructions

## 📥 Dataset

- Source: [Walmart Sales Dataset on Kaggle](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)
- Format: `.csv`
- Size: ~10,000 transactions

---

## 🚀 Project Steps

### 1. Environment Setup
- Installed Python packages using pip
- Created MySQL database and table `walmart_dataset`

### 2. Data Ingestion
- Loaded the CSV into MySQL
- Imported data from MySQL into Pandas DataFrame

### 3. Initial Exploration
- Used `.head()`, `.info()`, `.describe()` to understand structure
- Checked column names, types, and data distribution

### 4. Data Cleaning
- Removed duplicates
- Handled missing values
- Converted date/time columns to proper formats
- Formatted currency values

### 5. Feature Engineering
- Created new column `Total_Amount = Unit_price * Quantity`
- Saved the cleaned dataset as `walmart_cleaned_dataset.csv`

### 6. Exploratory Data Analysis (EDA)
- Revenue trends across branches and cities
- Best-selling product categories
- Payment method breakdowns
- Peak sales periods and patterns
- Profit margin analysis

### 7. Documentation & Publishing
- Full analysis documented in Jupyter Notebook
- Uploaded raw & cleaned datasets
- Repository structured and published on GitHub

---

## 📈 Key Insights

- Branch A had the highest total revenue overall
- E-wallets became increasingly popular as a payment method
- Health and Beauty was the best-selling product category
- Peak sales occurred in the evening between 6–7 PM
- Customer type and city significantly impacted gross margins

---

## 💾 How to Run

1. Clone this repository
2. Install dependencies via `pip install pandas numpy matplotlib seaborn mysql-connector-python`
3. Run Jupyter Notebook:  
   ```bash
   jupyter notebook

📌 Credits
Dataset by: Najir0123 on Kaggle
Project created as part of a guided data analysis curriculum


Author
Prakash Singh
B.Tech in AI & ML
GitHub: [your_github_username]
