# 🛒 Product Sales Prediction

This project analyzes a product sales dataset and builds regression models to **predict purchase amounts** based on user demographics and product categories.  
It includes **data cleaning, EDA, feature encoding**, and modeling using **Linear Regression** and **Random Forest**.

---

## 📘 Problem Statement

Given customer and product information, the task is to **predict the Purchase amount** using machine learning models.  
This is a regression problem where the target is the `Purchase` column.

---

## 📂 Project Structure

- `train.csv` — The dataset containing customer, product, and purchase information  
- `Product_Sales_EDA_Model.ipynb` — Jupyter Notebook with full EDA, preprocessing, and modeling steps

---

## 🔍 Exploratory Data Analysis (EDA)

Explored key trends using seaborn bar plots:

- Purchase amount by **Gender**
- Purchase amount by **Age**
- Purchase amount by **Occupation**
- Purchase amount by **City Category**
- Purchase amount by **Marital Status**

### 📊 Visual Insights

Bar plots revealed:
- Male customers tend to spend more on average
- Certain age groups (e.g., 26–35) are high spenders
- Occupation and city also influence spending behavior

---

## 🧹 Data Preprocessing

- Dropped irrelevant columns like `Product_ID`
- Filled missing values in product categories with **mean**
- Encoded all categorical columns into numerical values using **manual label encoding**

---

## 🤖 Machine Learning Models

Trained two regression models:

### 1️⃣ Linear Regression
- A basic baseline model
- Learned weights for each feature to estimate `Purchase` values

### 2️⃣ Random Forest Regressor
- Used ensemble learning with decision trees
- Performed better than linear regression in most cases

---

## 🧰 Technologies Used

- Python 🐍
- Pandas & NumPy 🧮
- Seaborn & Matplotlib 📊
- Scikit-learn 🤖
- Jupyter Notebook 📓

---

## ▶️ How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Denistanb/Product-Sales.git
   cd Product-Sales
2. **Install Dependencies**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
3. **Launch the Notebook**:
   ```bash
   jupyter notebook "Product Sales.ipynb"
