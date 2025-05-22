# cnc-cost-estimation-

# CNC Cost Estimation – Data Science Intern Assignment

## 📌 Objective
The goal of this project is to estimate the machining cost of CNC-manufactured parts using machine learning techniques. This assignment demonstrates data cleaning, feature engineering, model training, and data visualization skills applied to a manufacturing context.

---

## 📁 Project Structure

- `CNC_Cost_Estimation.ipynb`: Main Jupyter notebook containing data processing, modeling, and visualizations.
- `sample_scraping.py` *(optional)*: Demo script for scraping basic CNC-related data.
- `README.md`: This file.

---

## 🔍 Approach Summary

### 1. Data Source
- The dataset was provided. As per the assignment requirements, a sample web scraping script is included to demonstrate scraping skills.

### 2. Data Cleaning
- Checked for null values, data types, and outliers.
- Removed or imputed missing values.
- Ensured consistency in material and categorical values.

### 3. Feature Engineering
- Created new features such as:
  - `Volume` = Length × Width × Height
  - `Cost_per_mm3` = Quoted Cost / Volume
- These features help relate physical attributes to machining cost.

### 4. Modeling
- Used Linear Regression and Random Forest to predict `Quoted_Cost`.
- Evaluation Metrics:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
- Feature importance and scatter plots were used for interpretation.

---

## 📊 Key Insights

- Volume and Material type are strong predictors of cost.
- Random Forest outperformed Linear Regression in terms of accuracy.
- Higher material density and larger volume generally lead to higher cost.

---

## 🔁 Improvements

- Incorporate real-world scraped data for better generalization.
- Introduce categorical encodings for better handling of material types.
- Include surface area and machining complexity for better predictions.

---

## 📌 Tools Used

- Python (pandas, scikit-learn, seaborn, matplotlib)
- Jupyter Notebook
- BeautifulSoup (for scraping)

---

## 👤 Author
Ranjith Kumar R  
Data Science Intern Applicant


