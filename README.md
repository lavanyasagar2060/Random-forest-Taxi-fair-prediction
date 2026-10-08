# 🚖 Taxi Fare Prediction using Machine Learning

## 📌 Project Overview
This project applies **regression techniques** to predict taxi fare amounts based on trip details such as pickup/dropoff coordinates, passenger count, and trip distance.  
The goal is to build a reliable predictive system that estimates fares and uncovers pricing patterns in urban transportation.

---

## ✨ Features
- Data cleaning (handling missing values, removing outliers, type conversion)
- Feature engineering (distance, time of day, etc.)
- Exploratory data analysis (correlation heatmaps, visualizations)
- Model training and testing (train-test split, regression models)
- Model evaluation (accuracy, confusion matrix, classification report, cross-validation)
- Visualizations (residual plots, error distributions)

---

## 🛠️ Tools & Technologies
- **Python**
- **Scikit-learn** – Regression & Evaluation  
- **NumPy** – Numerical Computation  
- **Pandas** – Data Manipulation  
- **Matplotlib & Seaborn** – Data Visualization  
- **Jupyter Notebook** – Development Environment  

---

## 📂 Dataset
- File: `taxi_fare.csv`  
- Contains trip details: pickup/dropoff coordinates, passenger count, and fare amount.

---

## ⚙️ Workflow
1. **Data Collection** – Load dataset  
2. **Data Cleaning** – Handle missing values, remove outliers, convert data types  
3. **Feature Engineering** – Create meaningful features (distance, time of day)  
4. **Feature Scaling** – Apply StandardScaler for balanced learning  
5. **Model Training** – Train-test split (80/20)  
6. **Prediction** – Estimate fare amounts on test set  
7. **Evaluation** – Accuracy, confusion matrix, precision, recall, F1-score, cross-validation  

---

## 📊 Results
- **Accuracy Score:** 96.3% (test set)  
- **Confusion Matrix Heatmap:**  
  - TN: 8861 (Low Fare correctly predicted)  
  - FP: 110 (High Fare predicted but actually Low)  
  - FN: 268 (Low Fare predicted but actually High)  
  - TP: 761 (High Fare correctly predicted)  
- **Cross-validation:** 5-fold CV applied for generalization  

---

## ✅ Conclusion
Taxi fare prediction is influenced by trip distance, passenger count, pickup time, and location coordinates.  
Preprocessing steps like handling missing values, scaling, and feature engineering significantly improve model performance.  
This project demonstrates how regression and classification approaches can be applied to real-world pricing problems.

---

## 🔮 Future Scope
- Incorporating **traffic conditions, weather, and events** for smarter predictions  
- Using **advanced ensemble models or deep learning** for higher accuracy  
- Leveraging **location data** to calculate exact trip distances and identify busy pickup zones  

---

## 📖 References
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)  
- [Seaborn Documentation](https://seaborn.pydata.org/)  
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)  

---

## 👩‍💻 Author
Lavanya B 
