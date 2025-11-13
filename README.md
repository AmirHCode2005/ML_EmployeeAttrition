# 👔 Employee Attrition Prediction

## 📘 Overview
This project uses **Machine Learning** techniques to predict whether an employee is likely to leave the company.  
It is a **Binary Classification** problem where the target variable indicates **Attrition = Yes (1)** or **No (0)**.

## 🧠 Project Highlights
- **Type:** Binary Classification  
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Dataset:** `Employee Attrition Prediction.csv` — contains HR-related features such as job role, satisfaction level, work-life balance, and salary.  
- **Data Type:** All features are **numeric**, making preprocessing and model training more efficient.  

## ⚙️ Workflow
1. **Data Preprocessing** – cleaned and scaled numeric data; handled missing values and ensured data normalization.  
2. **Exploratory Data Analysis (EDA)** – studied correlations and feature importance related to employee attrition.  
3. **Model Training** – applied logistic regression and other ML models for prediction.  
4. **Class Imbalance Handling** – used `class_weight='balanced'` to improve detection of the minority (attrition) class.  
5. **Model Evaluation** – assessed using accuracy, precision, recall, and F1-score metrics.

## 🚧 Challenges
The dataset was **highly imbalanced**, with far fewer employees leaving compared to those staying.  
Initially, the model mainly predicted the majority class (employees staying).  
After applying **class balancing**, the model successfully recognized more attrition cases —  
however, this caused a **slight decrease in overall accuracy**, a common tradeoff for improving fairness and minority class recognition.

## 📊 Results
- Improved detection of employees likely to leave.  
- Slight accuracy drop due to balancing but better recall for attrition cases.  
- Visualized performance through **confusion matrix** and **ROC curve**.  

## 💡 Skills Used
- 🐍 Python  
- 🤖 Machine Learning  
- 📊 Data Science  
- 📈 Data Visualization  

## 📁 Files Included
- `Employee_attrition_prediction.ipynb` → Main Jupyter Notebook  
- `Employee Attrition Prediction.csv` → Dataset  

## 📬 Contact
📧 **amirhossin6825@gmail.com**  
💬 **Telegram:** [@AmirHossin6825](https://t.me/AmirHossin6825)
