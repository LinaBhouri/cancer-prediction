# 🧠 Cancer Prediction Using Random Forest

This project applies machine learning techniques to predict the likelihood of cancer based on various medical and lifestyle-related features. The goal is to build an accurate, interpretable model that can assist in early cancer diagnosis using a **Random Forest Classifier**.

---

## 📁 Dataset

The dataset used in this project was sourced from Kaggle:

📎 **[Cancer Prediction Dataset by Rabie El Kharoua](https://www.kaggle.com/datasets/rabieelkharoua/cancer-prediction-dataset/data)**  
It contains patient-level information such as:

- Age  
- Gender  
- BMI  
- Smoking habits  
- Genetic risk  
- Physical activity  
- Alcohol intake  
- Cancer history  
- Diagnosis label (0 = No Cancer, 1 = Cancer)

---

## ⚙️ Project Workflow

1. **Data Loading & Preprocessing**
   - Handling missing values
   - Label encoding (if needed)
   - Exploratory Data Analysis (EDA)

2. **Data Visualization**
   - Distribution plots (Age, BMI, Diagnosis)
   - Correlation heatmap
   - Impact of lifestyle factors

3. **Modeling**
   - Training a **Random Forest Classifier**
   - Evaluating performance: Accuracy, Precision, Recall, F1 Score
   - Confusion matrix visualization

4. **Conclusion**
   - Key feature insights
   - Model evaluation summary

---

## 📊 Tools & Libraries Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn (RandomForestClassifier, metrics)
- Jupyter Notebook

---

## 🔍 Results

The model achieved strong performance with a well-balanced confusion matrix, showcasing its ability to effectively distinguish between cancer and non-cancer cases.

---

## 📌 Project Structure

<pre> Cancer_prediction/
│
├── Dataset/
│   └── The_Cancer_data_1500_V2.csv
│
├── Model/
│   └── Cancer_pred.ipynb
│
└── README.md
 </pre>
