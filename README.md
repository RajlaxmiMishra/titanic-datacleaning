# titanic-datacleaning
Data cleaning, preprocessing, and exploratory data analysis (EDA) of the Titanic dataset using Python, Pandas, Matplotlib, and Seaborn.

# Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

## 📌 Project Overview
The objective of this project is to clean, transform, and analyze the raw Titanic passenger dataset using Python. Real-world datasets often contain missing values, inconsistent formats, and unneeded columns. By applying structured data preprocessing techniques, this project produces a clean, reliable dataset to analyze key demographic factors influencing passenger survival rates.

---

## 🛠️ Dataset Use Case & Data Cleaning Steps
1. **Handling Missing Values:**
   - Imputed missing values in `Age` using the median strategy to preserve central tendency.
   - Filled missing entries in `Embarked` using the mode (`'S'`).
   - Dropped the `Cabin` column due to an excessively high missing rate (>75%).
2. **Removing Redundant Data:**
   - Removed identifier features (`PassengerId`, `Name`, `Ticket`) that do not contribute to numerical trend analysis.
3. **Encoding Categorical Features:**
   - Converted the binary categorical feature `Sex` (`female` -> `1`, `male` -> `0`).
4. **Data Export:**
   - Exported the structured output to `cleaned_titanic.csv`.

---

## 📊 Key Visualizations & Expected Outcomes
- **Survival Rate by Passenger Class (Bar Chart):** Visualizes how passenger ticket class (`1`, `2`, `3`) directly correlated with survival probability, showing that higher-class passengers had a significantly higher survival rate.
- **Age Distribution by Survival (Histogram / KDE Plot):** Examines age-based survival trends across demographic groups, highlighting that young children were prioritized during rescue efforts.

---

## 💻 Python Libraries & Tools
- **Pandas:** Data manipulation, handling missing values, and filtering.
- **NumPy:** Numerical operations and array calculations.
- **Matplotlib & Seaborn:** Data visualization and plot styling.
- **Google Colab:** Cloud Python execution environment.
- **Git & GitHub:** Version control and submission management.

---

## 📁 Repository Structure
