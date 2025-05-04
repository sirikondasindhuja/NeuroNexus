# NeuroNexus
Titanic Survival Prediction using Random Forest
This project uses the Titanic dataset to predict whether a passenger survived the tragic sinking of the Titanic. It is a classic machine learning problem and a great starting point for data science enthusiasts.

🔍 Project Overview
The goal of this project is to build a binary classification model that can accurately predict passenger survival using features such as:

Passenger class (Pclass)
Sex
Age
Number of siblings/spouses aboard (SibSp)
Number of parents/children aboard (Parch)
Fare
Embarked port
Cabin (optional)

I used the Random Forest Classifier for its robustness, ability to handle missing data, and interpretability.

🧠 Model & Approach
Data Cleaning:

Handled missing values in columns like Age, Embarked, and Cabin.

Converted categorical variables (e.g., Sex, Embarked) into numerical using encoding.

Feature Engineering:

Created new features such as FamilySize, Title, and processed the Cabin data where applicable.

Modeling:

Trained a Random Forest classifier using scikit-learn.

Performed cross-validation to evaluate performance.

Evaluation Metrics:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

📁 Dataset
The dataset used is from the Kaggle Titanic: Machine Learning from Disaster competition.

📊 Results
The Random Forest model achieved an accuracy of approximately 86 on the test data.
