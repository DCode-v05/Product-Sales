# Product Sales Prediction

## Project Description
This project focuses on analyzing and predicting product sales amounts using customer demographics and product information. By leveraging machine learning techniques, the project aims to provide insights into purchasing behavior and build predictive models for sales forecasting.

## Project Details

### Problem Statement
Given a dataset containing customer and product details, the objective is to predict the purchase amount for each transaction. This is a regression problem with the target variable being the `Purchase` column.

### Data Overview
- **Dataset:** `train.csv` contains 550,068 records with 12 columns, including user demographics, product categories, and purchase amounts.
- **Features:**
  - User_ID, Product_ID, Gender, Age, Occupation, City_Category, Stay_In_Current_City_Years, Marital_Status, Product_Category_1/2/3, Purchase

### Exploratory Data Analysis (EDA)
- Analyzed purchase trends by gender, age, occupation, city category, and marital status.
- Visualized spending patterns to identify high-value customer segments.

### Data Preprocessing
- Dropped irrelevant columns (e.g., Product_ID).
- Filled missing values in product categories with mean values.
- Encoded categorical variables using manual label encoding.

### Modeling
- **Linear Regression:** Used as a baseline model to estimate purchase values.
- **Random Forest Regressor:** Ensemble model that improved prediction accuracy over the baseline.

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/DCode-v05/Product-Sales.git
   cd Product-Sales
   ```
2. **Install Dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. **Launch the Notebook:**
   ```bash
   jupyter notebook "Product Sales.ipynb"
   ```

## Usage
- Open the Jupyter notebook and follow the step-by-step analysis, preprocessing, and modeling workflow.
- Modify the notebook to experiment with different models or preprocessing techniques.

## Project Structure
- `Product Sales.ipynb` — Main notebook containing EDA, preprocessing, and modeling steps.
- `train.csv` — Dataset with customer, product, and purchase information.
- `README.md` — Project documentation.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request describing your changes.

## Contact
- **GitHub:** [DCode-v05](https://github.com/DCode-v05)
- **Email:** denistanb05@gmail.com
