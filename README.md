# task-1
# Titanic Dataset - Data Cleaning & Preprocessing

This project shows how to clean and prepare raw data for machine learning using the Titanic dataset.

##  Objective

- Learn how to clean a dataset step-by-step.
- Understand handling missing data, encoding, normalization, and outlier removal.
- Prepare data for training ML models.

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

##  Steps Performed

1. **Loaded the dataset** using pandas.
2. **Explored** missing values and data types.
3. **Handled missing values**:
   - Filled `Age` with median.
   - Filled `Embarked` with mode.
   - Dropped `Cabin` column due to too many missing values.
4. **Encoded categorical features**:
   - Converted `Sex` to numeric.
   - One-hot encoded `Embarked`.
5. **Standardized numerical features**: 
   - `Age`, `Fare`, `SibSp`, `Parch` scaled using `StandardScaler`.
6. **Detected and removed outliers** using IQR method.


## 📁 Output

- Cleaned and ready-to-use dataset for ML models: `Titanic-Cleaned.csv`

## 🚀 Next Steps

You can now use this cleaned dataset to train machine learning models like logistic regression, decision trees, etc.

