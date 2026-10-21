# Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs data cleaning, preprocessing, and exploratory data analysis (EDA) on the Titanic passenger dataset using Python. Real-world datasets often contain missing values, unneeded columns, and inconsistent formats. By applying data preprocessing techniques, this project produces a clean, structured dataset and visualizes key demographic factors influencing passenger survival.

---

## 🛠️ Data Cleaning & Preprocessing Steps
1. **Handling Missing Values:**
   - Imputed missing values in `Age` using the median strategy.
   - Filled missing entries in `Embarked` using the mode (`'S'`).
   - Dropped the `Cabin` column due to an excessively high missing rate (>75%).
2. **Removing Redundant Identifiers:**
   - Removed identifier columns (`PassengerId`, `Name`, `Ticket`) that do not contribute to demographic analysis.
3. **Encoding Categorical Features:**
   - Converted binary categorical feature `Sex` into numerical values (`female` -> `1`, `male` -> `0`).
4. **Exporting Clean Data:**
   - Exported the structured, cleaned dataset to `cleaned_titanic.csv`.

---

## 📊 Visualizations & Key Insights
- **Survival Rate by Passenger Class (Bar Chart):** Demonstrates that first-class passengers had a significantly higher survival rate compared to lower ticket classes.
- **Age Distribution by Survival (Histogram):** Highlights how passenger age influenced survival probabilities, showing priority given to young children during rescue efforts.

---

## 💻 Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Google Colab
- **Version Control:** Git, GitHub

---

## 👥 Authors / Team Members
- **Khwahish Jain (IU2441230660)**
- **Rajlaxmi Mishra (IU2441230684)**
- **Institute:** Indus University (B.Tech CSE)
