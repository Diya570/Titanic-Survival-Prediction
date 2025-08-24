# 🚢 Titanic Survival Prediction

## 📌 Project Overview
This project predicts whether a passenger survived the Titanic disaster using **Logistic Regression**.  
It includes **exploratory data analysis (EDA), data cleaning, feature engineering, model training, evaluation, and visualization**.

---

## 📊 Dataset
- Source: [Titanic Dataset on GitHub](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)  
- Contains passenger information such as **age, sex, class, and other features**.

---

## 🛠 Key Steps

### Exploratory Data Analysis (EDA)
- Visualized survival distribution by **gender** and **passenger class**.  
- Checked for **missing values** and feature distributions.

### Data Cleaning & Feature Engineering
- Filled missing `Age` values with **median**.  
- Dropped irrelevant columns: `Cabin`, `Ticket`, and `Name`.  
- Converted categorical features (`Sex` and `Embarked`) into numeric using **one-hot encoding**.

### Modeling
- Built a **Logistic Regression** model to predict survival.  
- Split data into **training (80%)** and **testing (20%)** sets.

### Evaluation
- Calculated **accuracy**, **confusion matrix**, and **classification report**.  
- Visualized the **confusion matrix** using a **Seaborn heatmap**.

---

## 📈 Results
- Logistic Regression Accuracy: ~**81%**  
- Confusion matrix shows **True Positives (TP), True Negatives (TN), False Positives (FP), and False Negatives (FN)**.

---

## 💻 Technologies Used
- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Scikit-learn** for machine learning

---

## 🚀 How to Run
1. **Clone the repository:**  
```bash
git clone https://github.com/Sumuk007/Titanic-Survival-Prediction.git
```

---

2. **Open the Jupyter Notebook:**
  Titanic_Logistic_Regression.ipynb

    *Run the notebook cells sequentially to:*

    - Explore the dataset

    - Train the Logistic Regression model

    - Visualize results
  
 ---
