# Cervical Cancer Risk Prediction (Supervised ML)

This project develops a supervised machine learning pipeline to predict cervical cancer risk based on medical features such as sexual health history, contraceptives, smoking, and screening results.

The aim is to demonstrate how ML can support early risk stratification — especially useful in areas with limited screening access.

---

## Key Features

- Dataset from Kaggle: "Cervical Cancer Risk Classification"
- Preprocessing: replaced "?" with NaN, numeric conversion, mode/median imputation
- Class balancing handled using **SMOTE** (applied correctly only on training data)
- Multiple ML models tested (Logistic Regression, Random Forest, SVM, XGBoost, Gradient Boosting, KNN)
- Feature visualization (histograms, correlation matrix)
- Model comparison table + confusion matrices

---

## Best Model Results

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------:|----------:|--------:|--------:|
| Logistic Regression | 96.38% | 96.49% | 96.38% | 96.43% |

(Logistic Regression performed best overall)

---

## Tech Stack

| Component | Library |
|----------|---------|
| Programming | Python |
| ML Framework | scikit-learn |
| Data Analysis | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Environment | Google Colab |

---

## Project Structure

```bash
Cervical_cancer_model/
│
├── Cervical_cancer_prediction_supervised_model.ipynb    # main notebook (ML project)
└── README.md                                            # documentation
