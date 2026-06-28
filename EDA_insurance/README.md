# 🏥 Insurance Dataset — EDA & Predictive Modeling

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-teal)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

---

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Medical Insurance dataset to uncover patterns, relationships, and key factors that influence insurance charges.

The goal is to understand the data deeply before building predictive models to estimate insurance costs based on patient attributes.

> 🚧 **Model Training coming soon!**

---

## 📂 Dataset

- **Source:** [Kaggle — Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Rows:** 1338
- **Columns:** 7

| Column | Description |
|--------|-------------|
| `age` | Age of the primary beneficiary |
| `sex` | Gender of the beneficiary |
| `bmi` | Body Mass Index |
| `children` | Number of dependents covered |
| `smoker` | Whether the beneficiary smokes |
| `region` | Residential region in the US |
| `charges` | Medical insurance cost (target variable) |

---

## 🔍 EDA Highlights

- ✅ Dataset overview — shape, dtypes, null values
- ✅ Univariate analysis — distributions of age, bmi, charges
- ✅ Bivariate analysis — charges vs smoker, region, sex
- ✅ Outlier detection — boxplots for numerical features
- ✅ Correlation analysis — heatmap of feature relationships
- ✅ Key insight: **Smoking** is the strongest predictor of high insurance charges

---

## 📊 Key Insights

- Smokers pay significantly higher charges than non-smokers
- BMI and age show a positive correlation with charges
- Region has minimal impact on insurance costs
- Most beneficiaries have 0–2 children

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — data manipulation
- **Matplotlib** — plotting
- **Seaborn** — statistical visualizations
- **Jupyter Notebook** — development environment

---

## 📁 Project Structure

```
Insurance-EDA/
│
├── insurance.csv          # Raw dataset
├── insurance_eda.ipynb    # Main EDA notebook
└── README.md              # Project documentation
```

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/insurance-eda.git

# Navigate to project folder
cd insurance-eda

# Install dependencies
pip install pandas matplotlib seaborn jupyter

# Launch Jupyter Notebook
jupyter notebook insurance_eda.ipynb
```

---

## 🔮 Future Work

- [ ] Feature Engineering
- [ ] Linear Regression model
- [ ] Random Forest model
- [ ] Model evaluation (MAE, RMSE, R²)
- [ ] Hyperparameter tuning

---

## 👤 Author

**Yogesh** — B.Tech CSE @ RVS College of Engineering and Technology  
📎 [GitHub](https://github.com/your-username) | [LinkedIn](https://linkedin.com/in/your-profile)

---

> ⭐ If you found this useful, consider starring the repo!