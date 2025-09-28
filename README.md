#  Telecom Churn Analysis & Prediction

##  Introduction
This project analyzes and predicts **customer churn in the telecom industry**.  
The workflow includes:  
1. Creating an **interactive Power BI dashboard** for churn analysis.  
2. Training a **machine learning model in Python** to predict churn.  
3. Feeding the **predicted churn values back into Power BI** for visualization and comparison.  

---

##  Dashboard Overview
The **Power BI dashboard** provides a complete view of customer churn trends.

- **Total Customers:** 6,418  
- **New Joiners:** 411  
- **Total Churned Customers:** 1,732  
- **Overall Churn Rate:** 27%  

### Key Insights
- **Churn by Gender:** 64.15% Male, 35.85% Female  
- **Churn by Age Group:** Highest churn among customers aged **20–35**  
- **Churn by Contract:** **Month-to-month contracts** have the highest churn rate  
- **Churn by Payment Method:** Customers using **Mailed Check** churn more  
- **Churn by Services:** Customers without **Online Security** or **Premium Support** are most likely to churn  
 

---

##  Machine Learning Model
The **Python notebook (`Telecom_churn_prediction.ipynb`)** was used to build predictive churn models.

### Steps
1. **Data Preprocessing** – Cleaning, encoding categorical variables, and feature scaling.  
2. **Model Training** – Logistic Regression, Random Forest, and Support Vector Machine (SVM) were applied.  
3. **Evaluation** – Accuracy, precision, recall, and F1-score measured.  
4. **Prediction Integration** – Results exported and linked back to Power BI for visualization.  

### Model Performance

#### Logistic Regression
- Accuracy: 80.99%  
- Precision: 0.63 (class 1)  
- Recall: 0.56 (class 1)  
- F1-score: 0.60 (class 1)  

#### Random Forest
- Accuracy: 83.49%  
- Precision: 0.73 (class 1)  
- Recall: 0.53 (class 1)  
- F1-score: 0.61 (class 1)  

#### Support Vector Machine (SVM)
- Accuracy: 82.01%  
- Precision: 0.66 (class 1)  
- Recall: 0.58 (class 1)  
- F1-score: 0.61 (class 1)  

**Best Performing Model:** Random Forest with **83.49% accuracy**  

- **Predicted Churners :** 411  

---

##  Tech Stack
- **Power BI** – Data visualization & dashboards  
- **Python (Jupyter Notebook)** – ML model development  
- **Pandas, NumPy** – Data wrangling  
- **Scikit-learn** – Machine learning  
- **Matplotlib, Seaborn** – Visualization  

---


##  Project Structure
```
├── Telecom_Analysis.pbix              # Power BI dashboard
├── Telecom_Analysis_Dashboard.pdf     # Dashboard export
├── Telecom_churn_prediction.ipynb     # Python ML model notebook
```

---

## 🔍 Insights
- Customers on **month-to-month contracts** have the highest risk of churn.  
- Churn is strongly linked to the **absence of value-added services** (e.g., online security, premium support).  
- Predictive analytics helps **identify 411 potential churners**, enabling proactive retention strategies.  
- The **Random Forest model** is the most effective with **83.49% accuracy**.  

---

