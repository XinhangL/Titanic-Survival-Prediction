# 🚢 Titanic Survival Prediction using Logistic Regression

This notebook builds a binary classification model to predict survival on the Titanic using logistic regression.  
It is a classic data science challenge widely used for machine learning (ML) practice and interviews.

---

## 📌 Project Overview

- **Dataset**: Titanic passenger manifest (train and test CSV)
- **Goal**: Predict whether a passenger survived based on features like sex, age, and class
- **Model**: Logistic Regression using `scikit-learn`

---

## 🧠 Key Techniques

- Handling missing values (e.g. age imputation)
- One-hot encoding for categorical variables (`Embarked`)
- Feature engineering and label encoding (`Sex`)
- Train/test split with `train_test_split`
- Evaluation with classification report, confusion matrix, and accuracy

---

## 📁 Files

| File                                      | Description                        |
|-------------------------------------------|------------------------------------|
| `Script Logistic Regression Titanic.ipynb`| Main notebook                      |
| `Titanic_train.csv`                       | Training data                      |
| `Titanic_test.csv`                        | Testing data                       |
| `README.md`                               | Project summary and instructions   |

---

## 🚀 How to Run

1. Place `Titanic_train.csv` and `Titanic_test.csv` in the same folder as the notebook
2. Open `Script Logistic Regression Titanic.ipynb` in Jupyter
3. Run all cells to preprocess, train, and evaluate the model

---

## 📈 Outputs

- Confusion matrix
- Classification metrics (precision, recall, F1-score)
- R² score (for reference)

---

## 🧰 Tools Used

- Python 3.x
- pandas, numpy, matplotlib
- scikit-learn (LogisticRegression, metrics, model_selection)

---

This notebook demonstrates an end-to-end supervised learning pipeline for binary classification, making it an excellent resource for showcasing my ML foundations.
