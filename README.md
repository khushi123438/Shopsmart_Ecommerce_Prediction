# 🛒 ShopSmart E-Commerce Purchase Prediction

A Machine Learning project to predict whether an online visitor will complete a purchase based on their browsing behavior.

---

# 📌 Problem Statement

ShopSmart, an e-commerce company, wants to understand user behavior on its website and predict whether a visitor is likely to make a purchase.

The dataset contains **12,330 user sessions** collected over one year, capturing detailed browsing activity such as page visits, time spent on pages, bounce rate, exit rate, and traffic source.

The goal is to build a **Decision Tree based classification model** that predicts purchase behavior and helps improve marketing strategies.

Since the dataset is **imbalanced**, model performance is evaluated using the **F1 Score (benchmark: 0.55)**.

---

# 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Preprocess and clean the dataset
- Handle categorical and numerical features
- Build a Decision Tree Classifier
- Apply pruning techniques (pre-pruning & post-pruning)
- Improve model performance for imbalanced data
- Evaluate using F1 Score

---

# 📊 Dataset Information

The dataset includes the following features:

- Administrative, Administrative_Duration
- Informational, Informational_Duration
- ProductRelated, ProductRelated_Duration
- BounceRates, ExitRates
- PageValues
- SpecialDay
- Month
- OperatingSystems, Browser, Region
- TrafficType
- VisitorType
- Weekend
- Revenue (Target Variable)

---

# ⚙️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🧠 Machine Learning Workflow

## 1️⃣ Data Preprocessing
- Handling missing values (if any)
- Encoding categorical variables
- Feature scaling where required

## 2️⃣ Exploratory Data Analysis (EDA)
- Understanding distribution of features
- Analyzing purchase vs non-purchase behavior
- Identifying correlations

## 3️⃣ Model Building
- Decision Tree Classifier
- Train-test split
- Handling class imbalance

## 4️⃣ Pruning Techniques
- Pre-Pruning (max depth, min samples split, etc.)
- Post-Pruning (cost complexity pruning)

## 5️⃣ Evaluation
- Accuracy (supporting metric)
- F1 Score (main evaluation metric)
- Confusion Matrix

---

# 📈 Key Concepts Used

- Decision Tree Classification
- Entropy / Gini Impurity
- Information Gain
- Pre-Pruning & Post-Pruning
- Feature Encoding
- Handling Imbalanced Dataset
- F1 Score Evaluation

---

# 💡 Key Insights

- User behavior strongly depends on page engagement and duration
- High bounce rate often indicates lower purchase probability
- Page values are strong indicators of conversion likelihood
- Pruning significantly improves generalization and reduces overfitting

---

# 🚀 Results

- Built a Decision Tree model for purchase prediction
- Improved performance using pruning techniques
- Evaluated model using F1 Score (benchmark: 0.55)

---

# 📌 Future Improvements

- Try ensemble models (Random Forest, XGBoost)
- Hyperparameter tuning using GridSearchCV
- Feature engineering for better accuracy
- Deploy model using Flask / Streamlit

---

# 👨‍💻 Author

**Khushi Pandey**  
#30DaysOfML Journey 🚀

---

# 📌 Status

✔ Completed EDA  
✔ Completed Model Building  
✔ Completed Pruning Techniques  
✔ Evaluation Done (F1 Score based)

