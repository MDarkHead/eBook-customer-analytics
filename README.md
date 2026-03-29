# Online eBook Retailer Customer Analysis and Predictions

## Project Overview
This project analyzes customer behavior from an Online eBook Retailer to build machine learning models in order to predict customer spending and subscription likelihood with the goal of optimizing marketing efforts and inventory, improve customer targeting, and increase overall revenue.  

## Analytical Questions
- What factors influence customer spending behaviors? 
- Which customers are most likely to subscribe to eBooks?
- How can the retailer identify and target high-value customers?
- What customer segments should marketing efforts focus on?

## Objectives
### 1) Monthly Spend Prediction- Regression Model 
Predict the average monthly spending on books for each customer to optimize marketing efforts and inventory.

### 2) eBook Subscription Prediction- Classification Model
Predict whether a customer will subscribe to the eBook service to enable targeted promotional strategies in 
order to increase subscription rates. 

## Business Goals
The Online eBook Retailer wants to better understand their customers in order to:
- Estimate customer’s book expenditure
- Optimize marketing and inventory management
- Identify subscription probabilities for eBooks
- Implement data-driven promotional strategies to increase subscription rates

## Dataset
- Source: Online eBook Retailer Customer Data
- Features:
	- Customer demographics (Age, Gender, Marital Status)
	- Socioeconomic data (Income, Education, Occupation)
	- Household characteristics (Children, Homeownership, Cars)
	- Behavioral variables (Monthly Spend, Subscription Status)

## Technologies & Tools 
- Python (Pandas, NumPy)
- Scikit-learn, PyCaret
- Matplotlib, Seaborn
- Dython, AutoViz, ydata-profiling
- Tableau

## Project Structure
```
ebook-customer-analytics/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_regression_model.ipynb
│   ├── 03_classification_model.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── train.py
│   ├── evaluate.py
│
├── models/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Roadmap
- Phase 0: Project Framing ✅
- Phase 1: Data Cleaning ✅
- Phase 2: EDA + Insights (write insights.md)
- Phase 3: Dython (key drivers)
- Phase 4: Tableau Dashboard (storytelling)
- Phase 5: Feature Engineering
- Phase 6: Regression Model
- Phase 7: Classification Model
- Phase 8: Business Recommendations
- Phase 9: Portfolio Packaging (GitHub + Slides + Tableau + PDF)

## Disclaimer
This project is based on a simulated dataset provided as part of a data science training program. Any references to real-world entities are for illustrative purposes only.
