# Week4-HR_attrition_EDA-ML
# 🧠 HR Attrition Prediction – Machine Learning Case Study

This project is a complete end-to-end analysis of employee attrition using machine learning models. It helps HR departments predict which employees are most likely to leave the organization.

---

## 📦 Tools & Technologies

- **Python**
- **Jupyter Notebook / Google Colab**
- **Libraries Used**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – ML models and preprocessing
  - `imbalanced-learn` – Handling class imbalance using SMOTE

---

## 🔍 Steps Performed

### 1. Load Dataset
- Used `pandas.read_csv()` to load data
- Previewed with `.head()`, `.shape`, `.columns`

### 2. Explore Data
- Inspected datatypes and missing values
- Explored key features like `JobRole`, `OverTime`, and `Attrition`

### 3. Clean & Preprocess
- Encoded categorical variables using `LabelEncoder`
- Scaled features using `StandardScaler`
- Addressed class imbalance with **SMOTE**

### 4. Perform EDA
- Correlation heatmaps
- Countplots and boxplots for visualizing attrition across roles, income, and overtime

### 5. Build ML Models
- Trained **Logistic Regression** and **Random Forest** models
- Used `train_test_split` and `cross_val_score` for model validation

### 6. Evaluate Performance
- Measured with **Accuracy, Precision, Recall, F1-score**
- Displayed confusion matrix
- Focused on **Recall** to minimize false negatives

### 7. Interpret Results
- Extracted and visualized **feature importance** from Random Forest
- Identified key drivers of attrition (e.g., OverTime, MonthlyIncome)

### 8. Final Touch
- Structured like a case study with markdowns and clear section headers
- HR Recommendations added for practical application

---

## 🎯 Business Impact

- Helps HR predict and retain high-risk employees
- Reduces hiring and training costs
- Data-driven decision support for workforce planning

---

## 📁 Files

- `HR_Attrition_Case_Study.ipynb` – Full notebook
- `HR_Employee_Attrition.csv` – Dataset (place in the same folder)
- `README.md` – Project overview and instructions

---

## ✅ How to Run

1. Clone the repo or download the notebook and dataset
2. Open the notebook in Jupyter or Google Colab
3. Run all cells step-by-step

---


