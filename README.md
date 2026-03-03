# Netflix Exploratory Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to identify content growth patterns and movie duration trends over time.

---

## 📌 Objective
- Analyze the growth of Movies and TV Shows on Netflix
- Study year-wise content addition trends
- Examine average movie duration over time

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Analysis Overview
- Movies vs TV Shows distribution
- Year-wise content growth analysis
- Average movie duration trend
- Targeted data cleaning and feature engineering (`year_added`, `duration_min`)

---

## 📈 Key Insights
- Netflix content additions increased significantly after 2016
- Movies dominate the platform in terms of total content
- Average movie duration has remained relatively stable over the years

---

## 📂 Dataset
Netflix Movies and TV Shows dataset  
Source: Kaggle

---

## 🚀 How to Run
1. Clone the repository
2. Install required libraries
3. Open the Jupyter Notebook
4. Run all cells sequentially

---
# AI/ML Learning Repository

This repository contains machine learning projects and implementations covering supervised learning algorithms including **AdaBoost**, **XGBoost**, and exploratory data analysis.

---

## 📌 Projects

### 1. AdaBoost & XGBoost Classification
Demonstrates classification using ensemble boosting methods.

**Objective**
- Implement AdaBoost Classifier for binary classification
- Implement AdaBoost Regressor for regression tasks
- Compare with XGBoost Classifier performance
- Evaluate model accuracy and performance metrics

**Algorithms Covered**
- **AdaBoost Classifier** - Adaptive Boosting for classification
- **AdaBoost Regressor** - Adaptive Boosting for regression
- **XGBoost Classifier** - Extreme Gradient Boosting

**Key Features**
- Binary classification using synthetic datasets
- Regression on continuous targets
- Model evaluation with `accuracy_score`, `r2_score`, `classification_report`
- Hyperparameter tuning (max_depth, n_estimators, learning_rate)

---

### 2. Netflix Exploratory Data Analysis (EDA)
Analyzes Netflix Movies and TV Shows content trends.

**Objective**
- Analyze content growth patterns over time
- Identify Movies vs TV Shows distribution
- Study year-wise content addition trends
- Examine average movie duration trends

**Analysis Performed**
- Movies vs TV Shows distribution
- Year-wise content growth analysis
- Average movie duration trends
- Data cleaning and feature engineering

**Key Insights**
- Netflix content additions increased significantly after 2016
- Movies dominate the platform in total content
- Average movie duration has remained stable over years

---

## 🛠️ Tools & Technologies
- **Python 3.8+**
- **Libraries**: scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn
- **Environment**: Jupyter Notebook, VS Code

---

## 📂 Repository Structure
```
Ai-ML/
├── supervised/
│   ├── adaboost.ipynb          # AdaBoost & XGBoost implementations
│   └── netflix_eda.ipynb       # Netflix dataset analysis
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

### Prerequisites
```bash
pip install scikit-learn xgboost pandas numpy matplotlib seaborn jupyter
```

### Steps
1. Clone the repository
   ```bash
   git clone https://github.com/aggarwal-navya/Ai-ML.git
   cd Ai-ML
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook
   ```bash
   jupyter notebook
   ```

4. Open desired notebook and run cells sequentially

---

## 📊 Model Performance

### AdaBoost Classifier
- Accuracy: ~95%+ on synthetic classification dataset
- Base Estimator: Decision Tree (max_depth=3)
- Estimators: 100

### XGBoost Classifier
- Accuracy: ~98%+ on synthetic classification dataset
- Learning Rate: 0.1
- Max Depth: 3
- Evaluation Metric: logloss

### AdaBoost Regressor
- R² Score: High correlation on regression tasks
- Suitable for continuous target prediction

---

## 📚 Learning Resources
- [scikit-learn AdaBoost Documentation](https://scikit-learn.org/stable/modules/ensemble.html#adaboost)
- [XGBoost Official Documentation](https://xgboost.readthedocs.io/)
- [Ensemble Methods in ML](https://en.wikipedia.org/wiki/Ensemble_learning)

---

## 👤 Author
**Navya Aggarwal**  
GitHub: [@aggarwal-navya](https://github.com/aggarwal-navya)

