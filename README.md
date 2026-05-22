# 🏥 Medical  Cost Prediction

A machine learning project that predicts annual medical insurance charges for customers using **Linear Regression** with Python and Scikit-learn.

---

## 📌 Problem Statement

ACME Insurance Inc. needs an automated system to estimate the **annual medical expenditure** for new customers based on personal information. These estimates are used to determine insurance premiums.

---

## 📊 Dataset

- **Source**: [Medical Charges Dataset](https://raw.githubusercontent.com/JovianML/opendatasets/master/data/medical-charges.csv)
- **Records**: 1300+ customers
- **Features**:

| Feature | Description |
|---|---|
| `age` | Age of the customer |
| `sex` | Gender (male/female) |
| `bmi` | Body Mass Index |
| `children` | Number of dependents |
| `smoker` | Smoking status (yes/no) |
| `region` | US region (northeast, southeast, southwest, northwest) |
| `charges` | Annual medical charges (target variable) |

---

## 🧠 What's Covered

- Exploratory Data Analysis (EDA)
- Linear regression with a single variable
- Linear regression with multiple variables
- Encoding categorical features
- Feature importance & regression coefficients
- Train/test split and model evaluation (RMSE)

---

## 🔍 Key Findings

Top features influencing insurance charges:

1. 🚬 **Smoker status** — highest impact
2. 👴 **Age**
3. ⚖️ **BMI**

---

## 🛠️ Tech Stack

- Python 3
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/medical-insurance-cost-prediction.git
cd medical-insurance-cost-prediction
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Run the notebook

```bash
jupyter notebook python-sklearn-linear-regression.ipynb
```

---

## 📁 Project Structure

```
medical-insurance-cost-prediction/
│
├── python-sklearn-linear-regression.ipynb   # Main notebook
├── medical.csv                              # Dataset
└── README.md                               # Project documentation
```

---

## 📈 Model Performance

| Split | RMSE |
|---|---|
| Training | ~5,974 |
| Test | ~6,632 |

---

## 🙋‍♂️ Author

**Farid** — Machine Learning
---

