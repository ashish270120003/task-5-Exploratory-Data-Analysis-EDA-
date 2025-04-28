<img width="1470" alt="Screenshot 2025-04-28 at 9 38 21 AM" src="https://github.com/user-attachments/assets/e0157691-f5e7-44d0-8695-9f3fd608a0bd" />
<img width="1470" alt="Screenshot 2025-04-28 at 9 38 15 AM" src="https://github.com/user-attachments/assets/cdd3f72a-28fe-44c7-ab9a-b5cf434a5db6" />
<img width="1470" alt="Screenshot 2025-04-28 at 9 38 11 AM" src="https://github.com/user-attachments/assets/7b636acc-4a85-4669-8cf7-71e9e67aad7b" />
<img width="1470" alt="Screenshot 2025-04-28 at 9 38 07 AM" src="https://github.com/user-attachments/assets/91d8f541-71ec-456c-ad3f-32050b2aabae" />
<img width="1470" alt="Screenshot 2025-04-28 at 9 38 04 AM" src="https://github.com/user-attachments/assets/4072ad85-f10a-416e-ab4f-ff9b4b1bb460" />
<img width="1470" alt="Screenshot 2025-04-28 at 9 37 59 AM" src="https://github.com/user-attachments/assets/5aea974b-6232-4c37-9491-a793dd59c6e9" />
<img width="1470" alt="Screenshot 2025-04-28 at 9 37 55 AM" src="https://github.com/user-attachments/assets/87ac3bca-11fb-4b4d-ac16-c6b6b90c0a0c" />
<img width="1470" alt="Screenshot 2025-04-28 at 9 37 51 AM" src="https://github.com/user-attachments/assets/e875a241-e63f-40e3-9bba-1df9313cffa8" />
<img width="1470" alt="Screenshot 2025-04-28 at 9 37 48 AM" src="https://github.com/user-attachments/assets/a53000c3-0607-4a57-bb7b-a0a0698e6a03" />
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
