# task-5-Exploratory-Data-Analysis-EDA-

# Exploratory Data Analysis (EDA) - Titanic Dataset

## 📋 Task Overview
This project was completed as part of the **Data Analyst Internship (Task 5)**.  
The objective was to perform **Exploratory Data Analysis (EDA)** on a dataset to uncover patterns, trends, and anomalies using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 🛠 Tools and Libraries Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Dataset
- Dataset used: **Titanic Dataset**  
- Source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)

---

## 🚀 Steps Followed
1. **Data Loading**  
   - Imported necessary libraries.
   - Loaded the Titanic dataset using `pandas`.

2. **Initial Data Exploration**  
   - Displayed the first few rows using `.head()`.
   - Checked dataset structure with `.info()`.
   - Summarized statistics with `.describe()`.
   - Identified missing values and data types.

3. **Univariate Analysis**  
   - Plotted histograms, boxplots for individual columns like `Age`, `Fare`, `Sex`, etc.

4. **Bivariate Analysis**  
   - Used scatterplots and countplots to explore relationships between two variables such as `Survived` vs `Sex`, `Pclass` vs `Survived`.

5. **Multivariate Analysis**  
   - Created heatmaps to visualize correlations between numerical features.
   - Generated pairplots to explore multiple feature interactions.

6. **Observations and Insights**  
   - After each visual, noted key insights and findings.
   - Highlighted important features impacting survival, such as `Sex`, `Pclass`, and `Fare`.

7. **Summary of Findings**  
   - Summarized the key patterns, trends, and anomalies discovered during EDA.



## 📊 Key Insights
- Women had a significantly higher survival rate than men.
- Passengers from higher classes (`Pclass = 1`) had better chances of survival.
- Higher fare prices were associated with a higher survival rate.
- Missing data was found mainly in `Age`, `Cabin`, and `Embarked` fields.

---

## 📎 Files Included
- `EDA_Titanic.ipynb` — Jupyter Notebook containing code, visualizations, and insights.
- `EDA_Titanic_Report.pdf` — Exported PDF version of the notebook.
- `README.md` — This file.
