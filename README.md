# Task-1: Titanic Data Preprocessing - Elevate Labs Internship

## Objective: Clean and prepare Titanic dataset for ML

### Steps Performed:
1. **Data Loading:** 891 rows, 12 columns
2. **Missing Values:** Age filled with median (177 missing), Embarked with mode (2 missing), Dropped Cabin (687 missing - 77%)
3. **Encoding:** Sex -> 0/1 Label Encoding, Embarked -> One-Hot Encoding
4. **Scaling:** StandardScaler on Age & Fare
5. **Outlier Removal:** IQR method on Fare column - Removed 116 outliers
6. **Final Data:** 775 rows x 12 cols - Saved as titanic_cleaned.csv

### Tools: Python, Pandas, Scikit-learn, Matplotlib, Seaborn
### Visualizations: Boxplots for outlier detection
