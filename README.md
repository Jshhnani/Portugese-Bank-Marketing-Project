# Portuguese Bank Marketing Analysis & Prediction  

## Project Overview  
This project focuses on analyzing the **Portuguese Bank Marketing dataset** to predict whether a customer will subscribe to a term deposit. The goal is to help the bank’s marketing team improve campaign strategies and increase customer conversions through data-driven insights.  

---

## Objectives  
1. **Data Analysis:** Perform detailed EDA to understand customer behavior and key influencing factors.  
2. **Predictive Modeling:** Build classification models to predict potential customers likely to subscribe.  
3. **Recommendations:** Provide actionable suggestions to enhance marketing effectiveness.  

---

## Data Preprocessing & Feature Engineering  
- Handled missing values and cleaned categorical variables.  
- Converted categorical features using **Label Encoding** and **One-Hot Encoding**.  
- Applied **SMOTE** to handle class imbalance.  
- Scaled numerical features for model efficiency.  

---

## Exploratory Data Analysis (EDA)  
- Identified key patterns such as the impact of **age, occupation, and contact frequency**.  
- Found that customers aged **30–40** and **above 50** are more likely to subscribe.  
- Observed that **retired** and **student** categories show higher response rates.  
- Excessive contact attempts reduce campaign success.  

---

## Models Implemented  
| Model | Description | Result |
|--------|--------------|---------|
| Logistic Regression | Baseline linear model | Moderate accuracy |
| Random Forest | Ensemble model, best performer | **Highest accuracy** |
| Gaussian Naive Bayes | Fast probabilistic model | Lower accuracy |

 **Best Model:** Random Forest Classifier  

---

## Model Optimization  
- Used **GridSearchCV** for hyperparameter tuning.  
- Selected the best parameters to improve accuracy and stability.  
- Model evaluation done using **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **Confusion Matrix**.  

---

## Key Insights  
- Customers aged 30–40 & 50+ respond better.  
- Retired and students show higher subscription rates.  
- Campaigns in **May, August, and November** perform well.  
- Limiting contact attempts (≤4) improves results.  
- Digital channels (email/SMS) are more effective for younger customers.  

---

## Recommendations  
- Focus marketing on high-potential customer segments.  
- Personalize offers for specific occupations and age groups.  
- Schedule campaigns during favorable months.  
- Use past positive responses for targeted follow-ups.  
- Combine term deposits with bundled financial products.  

---

## Technologies Used  
- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Scikit-learn**, **SMOTE (imblearn)**  
- **Jupyter Notebook**  

---

## Conclusion  
The **Random Forest model** achieved the best predictive performance.  
With balanced data using **SMOTE** and optimized hyperparameters through **GridSearchCV**, the model provides reliable predictions for customer subscription behavior and valuable insights for strategic decision-making.  

---

## Author  
**Jaswanth Atupakam**  
Data Science Enthusiast | Machine Learning Practitioner  
