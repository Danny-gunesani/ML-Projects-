# Diabetes Detection

**What it does:** Predicts whether a patient is diabetic based on health
metrics (glucose, BMI, age, insulin, etc.), using classification models.

**Dataset:** Pima Indians Diabetes Dataset (Kaggle)

**Approach:** Data loaded with Pandas, features scaled with `StandardScaler`,
split into train/test sets. Two models were trained and compared:
- Logistic Regression
- Decision Tree Classifier

**Result:**
- Logistic Regression accuracy: ~72%
- Decision Tree accuracy: ~82%

Decision Tree was selected as the better-performing model for this dataset.

**What I learned:** How to compare multiple classification models on the same
dataset, the role of feature scaling (needed for Logistic Regression, not
needed for Decision Trees), and how to read a classification report
(precision, recall, F1-score) alongside accuracy.
