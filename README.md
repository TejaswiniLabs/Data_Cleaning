# Data Cleaning and Preprocessing

## 📌 Project Overview

This project demonstrates basic **Data Cleaning and Preprocessing** techniques using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

The **Titanic dataset** is used to understand and implement different data preprocessing techniques such as:

- Handling missing values
- Mean and median imputation
- Mode imputation
- Group-based imputation
- Categorical encoding
- Label encoding
- One-hot encoding
- Ordinal encoding
- Feature scaling
- Standardization
- Normalization
- Data visualization

---

## 📂 Files in This Repository

| File | Description |
|------|-------------|
| `Tejaswini_SCFP126005.ipynb` | Jupyter Notebook containing the complete data cleaning and preprocessing code |
| `titanic.csv` | Titanic dataset used for analysis |
| `README.md` | Project documentation |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset

The project uses the **Titanic dataset**.

The dataset contains information about passengers such as:

- Passenger class
- Sex
- Age
- Fare
- Embarked location
- Survival information
- Passenger details

---

## 🔧 Data Cleaning

The following missing-value techniques are implemented:

### 1. Mean Imputation

Missing values in the `age` column are replaced using the mean age.

```python
df["age_mean"] = df["age"].fillna(df["age"].mean())
