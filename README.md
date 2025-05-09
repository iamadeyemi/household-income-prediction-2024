# 🏠 Household Income Prediction Project

> A data analytics project using regression techniques, cross-validation, bootstrapping, and unsupervised learning to predict household income based on demographic and housing features.

---

## 🧾 Overview

This project explores the **Household Income Dataset**, aiming to predict annual household income using various socioeconomic and housing characteristics. The analysis includes:

- Regression modeling
- 10-fold cross-validation
- Bootstrapping for confidence intervals
- Unsupervised learning (PCA & clustering)

The goal is to understand which factors most strongly influence income levels and how accurately we can model these relationships.

---

## 📁 Dataset Description

🔗 [Dataset Source: Kaggle - Regression Dataset for Household Income Analysis](https://www.kaggle.com/datasets/stealthtechnologies/regression-dataset-for-household-income-analysis)

### 📊 Variables

| Variable | Type | Description |
|---------|------|-------------|
| `HouseholdID` | Qualitative (ID) | Unique ID for each household |
| `LocationType` | Qualitative | Urban vs. Rural area |
| `FamilySize` | Quantitative | Number of family members |
| `NumRooms` | Quantitative | Total number of rooms |
| `NumBedrooms` | Quantitative | Number of bedrooms |
| `NumCars` | Quantitative | Number of cars owned |
| `ElectricityAccess` | Qualitative (Yes/No) | Electricity availability |
| `WaterAccess` | Qualitative (Yes/No) | Clean water access |
| `InternetAccess` | Qualitative (Yes/No) | Internet availability |
| `OwnHouse` | Qualitative (Yes/No) | Whether the house is owned |
| `HouseholdIncome` | Quantitative (Target) | Annual income of the household |

---

## 🎯 Problem Statement

Can we **predict household income** using demographic and housing-related features?

This predictive model helps:
- Understand key drivers of income disparities
- Support policy-making or social impact initiatives
- Provide insights into living conditions and economic status

---

## 🛠️ Methods Used

| Method | Purpose |
|--------|---------|
| Linear Regression | Predict `HouseholdIncome` from input features |
| 10-Fold Cross-Validation | Evaluate model performance across multiple splits |
| Bootstrapping | Estimate confidence intervals and model stability |
| PCA (Principal Component Analysis) | Explore underlying structure in data |
| K-Means Clustering | Group households by similarity in features |

---

## 📁 Project Structure

```
household-income-prediction/
│
├── data/
│   └── HouseholdIncomeDataset.csv     # Original dataset
│
├── notebooks/
│   ├── exploratory_data_analysis.ipynb
│   ├── regression_modeling.ipynb
│   ├── cross_validation.ipynb
│   ├── bootstrapping.ipynb
│   └── unsupervised_learning.ipynb
│
├── reports/
│   └── final_report.pdf               # Final written report (Word/PDF)
│
├── src/
│   └── preprocess.py                  # Data preprocessing script
│
├── README.md                          # You are here!
│
└── requirements.txt                   # Python dependencies
```

---

## ⚙️ Requirements

To run this project locally, you need:

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyter

Install dependencies with:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/iamadeyemi/household-income-prediction-2024.git
cd household-income-prediction-2024
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open and run the notebooks in order:
   - EDA → Preprocessing → Modeling → Cross-Validation → Bootstrapping → Unsupervised Learning

---

## 📊 Results Summary

- Linear regression achieved an R² score of **X.XX**
- Cross-validation confirmed consistent performance
- Bootstrapped confidence intervals showed stable coefficients
- PCA revealed main components driving variation
- Clustering identified distinct groups of households

---

## 👨‍💻 **Contributors**  
- **Timothy Adeyemi** 🚀  
  - **GitHub:** [@iamadeyemi](https://github.com/iamadeyemi)  
  - **LinkedIn:** [iamadeyemi](https://www.linkedin.com/in/timothy-ade/)  

---

## 📜 **License**  
This project is licensed under the **MIT License** – feel free to use and improve it!  

---

## ⭐ **Show Your Support!**  
If you found this project useful, please **star ⭐ the repository** and share it!  

Happy coding! 🚀🏡💻 
