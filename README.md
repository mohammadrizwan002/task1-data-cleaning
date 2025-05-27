Task 1: Data Cleaning & Preprocessing - Titanic Dataset

This task is part of the AI & ML Internship Program. The objective was to clean and preprocess the Titanic dataset to make it ready for Machine Learning models.

📌 Objective
To learn and apply essential data preprocessing techniques such as:
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Outlier detection and removal

📂 Dataset
Dataset used: [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

⚙️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

 Steps Performed

 1. Data Loading & Exploration
- Loaded dataset using `pandas`
- Checked data types, missing values, and statistical summary

 2. Missing Value Handling
- `Age`: filled with **median**
- `Embarked`: filled with **mode**
- `Cabin`: dropped due to excessive nulls
- Remaining nulls dropped (if any)

3. Categorical Encoding
- `Sex`: Label encoded (male=1, female=0)
- `Embarked`: One-Hot Encoded (first category dropped to avoid dummy trap)

 4. Feature Scaling
- Used `StandardScaler` to standardize `Age` and `Fare` columns

 5. Outlier Detection & Removal
- Visualized outliers using "boxplots"
- Removed outliers in `Fare` using "IQR method"

---

💾 Output
- Cleaned dataset: `titanic_cleaned.csv`
- Notebook: `Task1_Titanic_Data_Cleaning.ipynb`

---

📈 Outcome
A clean, scaled, and encoded dataset that’s ready for model building with significantly reduced noise and enhanced data quality.

---

✅ Author
Rizwan** — AI & ML Internship Candidate  
