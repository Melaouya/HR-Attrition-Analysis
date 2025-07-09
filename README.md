# HR-Attrition-Analysis
# HR Attrition Analysis with Machine Learning

This project investigates why employees leave or stay in a company by analyzing HR data using supervised machine learning models. The goal is to predict employee attrition and provide data-driven recommendations to improve retention and motivation.

---

## 🎯 Objective

- Predict employee attrition (Yes/No) using historical HR data
- Identify key drivers of attrition such as job satisfaction, work-life balance, overtime, etc.
- Provide actionable insights and strategies for improving employee retention

---

## 📊 Dataset

- **Source**: IBM HR Analytics Employee Attrition & Performance (Kaggle)
- **Features**: Age, Gender, Job Role, Monthly Income, Job Satisfaction, OverTime, Work-Life Balance, Years at Company, etc.
- **Target**: `Attrition` (binary classification: Yes or No)

---

## 🛠️ Tools & Technologies

- **Python**  
- **Pandas & NumPy** – Data manipulation and preprocessing  
- **Matplotlib & Seaborn** – Visualization  
- **Scikit-learn** – Machine learning models and evaluation  
- **Keras (TensorFlow backend)** – Artificial Neural Networks

---

## 🧠 Models Used

1. **Logistic Regression Classifier**  
   - Baseline linear model for binary classification  
   - Simple, interpretable, and fast to train

2. **Random Forest Classifier**  
   - Ensemble model using decision trees  
   - Handles nonlinear relationships and feature importance

3. **Artificial Neural Network (ANN)**  
   - Multi-layer perceptron built using Keras  
   - Captures complex patterns in the data

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  
- ROC-AUC Score (for comparison)

---

## 🔍 Key Findings

- **Age**, **Job Satisfaction**,**OverTime** and **Work-Life Balance** were top attrition predictors
- Logistic Regression performed well on baseline, but ANN showed better generalization
- Random Forest provided useful feature importance rankings

---

## 💡 Recommendations

- Monitor employee satisfaction regularly  
- Reduce excessive overtime and improve work-life balance  
- Offer clearer career advancement paths  
- Use predictive analytics for early intervention

---

## 📁 Project Structure

