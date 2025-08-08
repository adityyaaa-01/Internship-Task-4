# Logistic Regression Binary Classification – Internship Task 4

## 📌 Project Overview
This project is part of my **AI & ML Internship** Task 4, where the objective is to **build a binary classifier using Logistic Regression** and evaluate it using various performance metrics.  

I have implemented the model using **Scikit-learn**, **Pandas**, and **Matplotlib**, following the given internship guidelines.

---

## 📂 Dataset
- **Name:** Breast Cancer Wisconsin Dataset  
- **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)  
- **Type:** Binary Classification (Malignant / Benign)  

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📊 Steps Performed
1. **Data Loading** – Imported dataset into a Pandas DataFrame.  
2. **Data Preprocessing** – Handled missing values, dropped unnecessary columns (e.g., `id`,`Unnamed: 32`).  
3. **Feature Scaling** – Standardized features for better model performance.  
4. **Train-Test Split** – Divided the data into training and testing sets.  
5. **Model Building** – Implemented Logistic Regression using Scikit-learn.  
6. **Prediction & Evaluation** – Evaluated the model using:  
   - Confusion Matrix  
   - Precision  
   - Recall  
   - ROC-AUC Score  
   - ROC Curve  
7. **Threshold Tuning** – Adjusted the decision threshold to balance precision and recall.  
8. **Sigmoid Function Understanding** – Explained how the sigmoid function works in logistic regression.  

---

## 📈 Results
- **Accuracy:** 0.9736842105263158  
- **Precision:** 0.9761904761904762  
- **Recall:** 0.9534883720930233  
- **ROC-AUC Score:** 0.99737962659679  

---

## 📷 Visualizations
- Confusion Matrix Heatmap  
- ROC Curve  
- Sigmoid Function Plot  

---

## 📚 Key Learnings
- Difference between **Logistic Regression** and **Linear Regression**  
- Working of the **Sigmoid Function**  
- Understanding **Precision vs Recall**  
- Importance of the **ROC-AUC Curve**  
- Handling **Class Imbalance**  
- Choosing the right **decision threshold**  

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
