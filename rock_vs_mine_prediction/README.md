# Sonar Rock vs Mine Classifier

**What it does:** Predicts whether a sonar signal reflects off a rock or an
underwater mine, using a binary classification model.

**Dataset:** Sonar dataset (60 numeric features per sample, label = Rock/Mine)

**Approach:** Data loaded with Pandas, labels encoded with `LabelEncoder`,
split into train/test sets, and a Logistic Regression model trained on the
features to classify each sample as Rock (0) or Mine (1).

**Result:** Training accuracy and testing accuracy calculated using
`accuracy_score` from scikit-learn.

**What I learned:** How to load and preprocess tabular data, encode
categorical labels, split data for training/testing, and train a
classification model with scikit-learn — plus the difference between
Linear Regression (for numbers) and Logistic Regression (for categories).
