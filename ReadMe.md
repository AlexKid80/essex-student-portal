# MSc Artificial Intelligence — Student Portal

Coursework archive and project resources by **Alexandros Tsangarides**, created during the MSc in Artificial Intelligence programme delivered by **Aegean College** in partnership with the **University of Essex**.

**[Visit the Student Portal](https://alexkid80.github.io/essex-student-portal/)**

## Modules

| Module | Subject | Content | Portal page |
|---|---|---|---|
| 01 | Databases & SQL | SQL queries and OLAP analysis | Coming later |
| 02 | R Studio | Statistical analysis and visualisation in R | Coming later |
| 03 · AI117 | Introduction to A.I. and Machine Learning | Decision Trees, Linear Regression, K-Means, Neural Networks and imbalanced datasets using Altair AI Studio | [Open](rapid.html) |
| 04 · AI104 | Machine Learning & Python | Exploratory analysis, energy-consumption datasets, regression, K-Means and Jupyter notebooks | [Open](mlai.html) |
| 05 · AI105 (AG704) | Neural Nets & Deep Learning | Telecom customer churn prediction with TensorFlow/Keras, hyperparameter tuning and SHAP | [Open](deep.html) |

## Module 05 — Telco Customer Churn

The AI105 coursework uses the **IBM Telco Customer Churn** dataset to compare **nine classification models**: Logistic Regression, six MLP variants (including the tuned MLP), Random Forest and XGBoost.

- **Neural networks:** Basic MLP, Batch Normalization, Dropout, L2 regularization, residual connections and KerasTuner Random Search.
- **Explainability:** SHAP analysis of model predictions.
- **Final test results:** Tuned MLP achieved the highest **F1-score (0.6101)**; XGBoost achieved the highest **ROC-AUC (0.8381)**.
- **Resources:** [Jupyter notebook](deeplearn/script/assignment.ipynb), [coursework dataset](deeplearn/dataset/assignment.csv) and downloadable trained models via the [module page](deep.html).

**Dataset credit:** IBM Sample Data Sets, *Telco Customer Churn*, available on [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The dataset is not original work by the repository author.

## Repository overview

```text
index.html                 Student portal homepage
rapid.html                 Module 03 — AI117
mlai.html                  Module 04 — AI104
deep.html                  Module 05 — AI105
assets/                    Shared CSS, JavaScript and images
deeplearn/
  dataset/assignment.csv   Telco dataset used in AI105
  script/assignment.ipynb  AI105 Jupyter notebook
  models/                  Saved trained models
```

Other module folders contain their respective coursework files, exported plots and supporting resources.

---

*Academic coursework and learning projects — academic years 2025–2027.*
