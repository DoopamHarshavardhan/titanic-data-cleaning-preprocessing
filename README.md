# Data Cleaning & Preprocessing – Titanic Dataset

__Project Overview__

This project focuses on cleaning and preprocessing raw data to make it suitable for Machine Learning models.
We used the Titanic dataset to perform essential data preparation steps like handling missing values, encoding categorical variables, scaling features, and removing outliers.

---
__Objective__

* Understand raw data structure
* Handle missing and inconsistent data
* Convert categorical features into numerical format
* Scale numerical features
* Detect and remove outliers
* Prepare a clean dataset for ML models

---

__Dataset__

* Dataset Used: Titanic Dataset
* Contains passenger details like Age, Gender, Fare, Class, and Survival status

---

__Tools & Technologies__

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Steps Performed

__1.Data Exploration__

* Checked dataset structure using ".info()" and ".describe()"
* Identified missing values using ".isnull()"

---

__2️.Handling Missing Values__

* Filled missing values in **Age** using median
* Filled missing values in **Embarked** using mode
* Dropped **Cabin** column due to excessive missing data

---

__3️.Encoding Categorical Variables__

* Converted **Sex** column using Label Encoding (male = 0, female = 1)
* Applied One-Hot Encoding on **Embarked** column

---

__4️.Feature Scaling__

* Used **StandardScaler** to standardize numerical features (Age, Fare)
* Ensured all features are on the same scale

---

__5️.Outlier Detection & Removal__

* Visualized outliers using **boxplots**
* Removed outliers using **IQR (Interquartile Range) method**

---

__6️.Final Dataset__

* Cleaned dataset saved as "cleaned_titanic.csv"
* Ready for Machine Learning model training

---

__Key Learnings__

* Importance of data cleaning in ML pipeline
* Handling missing values effectively
* Encoding categorical variables correctly
* Feature scaling techniques
* Identifying and removing outliers
