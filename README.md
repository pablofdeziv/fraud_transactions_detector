# fraud_transactions_detector🤖

This project explores predictive modelling techniques for supervised learning using real-life datasets. It focuses on handling **high-dimensional** and **class-imbalanced** classification problems through model tuning and evaluation.

## 🎯 Objectives

- Learn how to build and fine-tune classification models
- Work with challenging datasets:
  - `creditcard.csv` – extreme class imbalance (fraud detection)
- Evaluate performance using FPR (False Positive Rate) and FNR (False Negative Rate)
- Tune hyperparameters to achieve:
  - **FNR as low as possible**
  - **FPR < 0.5%**
 
## 📊 Datasets

| Dataset        | Description                            | Challenge            |
|----------------|----------------------------------------|----------------------|
| `creditcard.csv` | Credit card fraud detection (0/1)    | Class imbalance      |

---

## 🧠 Methods Used

- Logistic Regression
- Decision Trees
- Support Vector Machines
- Random Forests
- Grid Search for Hyperparameter Tuning
- Stratified Train/Test Splits
- Confusion Matrix, ROC Curve, FPR/FNR calculations

  
## 🧪 How to Run

1. Open `lab2_supervised_learning.ipynb` in Google Colab or Jupyter Notebook.
2. Upload the dataset `creditcard.csv` when prompted.
3. Run all cells and follow in-notebook instructions to:
   - Train models
   - Tune hyperparameters
   - Evaluate metrics


## 📁 Files

- `lab2_supervised_learning.ipynb` – main notebook with all steps
- *(Datasets not included for privacy, add your own copy of `creditcard.csv`)*

---

## 📌 Notes

- Based on the SpamAssassin project: [http://spamassassin.apache.org](http://spamassassin.apache.org)
- Key focus is **minimizing FNR** while keeping **FPR < 0.5%**

---

## 📝 License

This project is provided for educational purposes and is not licensed for commercial use.
