# 🫀 Heart Disease Prediction

My **Machine Learning semester project** — predicting heart disease from patient health records using 7 classification algorithms.

## 🎯 Objective

Train and compare multiple ML classifiers on the Heart Disease dataset to find the most accurate model for predicting heart disease presence.

## 🧪 Models & Results

| Model | Best Accuracy |
|---|---|
| **K-Nearest Neighbors** (k=8) | **87.0%** ⭐ |
| Random Forest | 85.0% |
| Logistic Regression | 84.0% |
| Support Vector Classifier (linear) | 83.0% |
| XGBoost | 81.0% |
| Naive Bayes | 80.0% |
| Decision Tree | 79.0% |

**Winner: KNN with 87% accuracy!** 🏆

## 🔬 Methodology

1. **Exploratory Data Analysis** — distributions, histograms, correlation heatmap
2. **Preprocessing** — one-hot encoding of categorical features (`sex`, `cp`, `fbs`, `restecg`, `exang`, `slope`, `ca`, `thal`), StandardScaler on numerical features
3. **Train/Test Split** — 67/33 with `random_state=0`
4. **Hyperparameter Tuning** — K values (1–20), kernels, max features, n-estimators
5. **Evaluation** — accuracy scores, confusion matrices, classification report

## 📁 Project Structure

```
├── Heart_Disease_Prediction.ipynb   # Complete notebook (code + outputs + charts)
├── dataset_hdp.csv                  # Heart disease dataset
└── README.md
```

## ▶️ How to Run

**Google Colab** (easiest): upload the notebook + CSV to Colab and run all cells.

**Locally:**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
jupyter notebook Heart_Disease_Prediction.ipynb
```
Make sure `dataset_hdp.csv` is in the same folder as the notebook.

## 🛠️ Tech

- Python, pandas, NumPy
- scikit-learn (KNN, Logistic Regression, SVC, Decision Tree, Random Forest, Naive Bayes)
- XGBoost
- Matplotlib, Seaborn

## 👩‍💻 Author

**Ayesha Shoukat** — Computer Science @ UET Narowal
