# Online-Retail-Transactions-Study
## Project Overview
This project analyzes customer purchasing behavior using RFM analysis &amp; clustering, time series forecasting, customer churn prediction, market basket analysis, and sales analysis. In addition, a product recommendation system has been developed. The goal is to extract insights and build a predictive model for customer retention and revenue growth.
## 📂 Dataset
This project uses the **Online Retail II** dataset from Kaggle.  
🔗 **Download the dataset here:** [Online Retail II Dataset](https://www.kaggle.com/datasets/ukveteran/online-retail-ii)  
### 📥 How to Download & Use the Dataset
1. Go to the dataset link above.
2. Download the dataset files (`online_retail_II.csv`).
3. Place them inside the `data/` folder in this repository.
4. Run the project using the instructions below.
   
## Methodology
### 1. Exploratory Data Analysis (EDA)
    Data cleaning, handling missing values, remove duplicates, and correct any inconsistencies.
    Data Transformation: Convert data types as necessary, create new features (feature engineering), and extract time-based features from the invoice date.
    Sales Analysis: Analyze sales trends over time, identify peak sales periods, and assess product performance.
    Customer Analysis: Examine customer demographics, purchasing behavior, and identify top customers by revenue.
    Product Analysis: Determine best-selling products, analyze product categories, and assess product return rates.
### 2. RFM Analysis & Customer Segmentation
    RFM Analysis: Perform Recency, Frequency, Monetary analysis to segment customers based on their purchasing behavior.
    Clustering: Apply clustering algorithms (e.g., K-Means) to group customers into distinct segments for targeted marketing.
### 3. Time Series Sales Forecasting
    Using Random Forest Model (Machine Learning model) for demand forecasting.
    Sales Forecasting: Use time series analysis to forecast future sales and inventory requirements.
    Evaluating model with RMSE, MAE and MAPE.
### 4. Customer Churn Prediction
    Building a classification model to predict churn probability.
    Using Random Forest / XGBoost for feature importance analysis.
    Evaluating Model with Classification Report (Recall, AUC-ROC Score, Accuracy, Precision, F1-Score), and Confusion Matrix.
### 5. Market Basket Analysis
    Use the Apriori Algorithm to find frequent itemsets (combinations of products that appear together frequently).
    Generate association rules to identify relationships between products.
    Integrate RFM Segmentation with Association Rule Mining to create highly targeted marketing strategies.    
### 6. Building Recommendation System
    Implementing Content-Based Filtering relies on product attributes, recommending items similar to those a user has shown interest in.
    Implementing Collaborative Filtering depends on user interaction data, suggesting items preferred by users with similar behaviors.
    Implementing Hybrid Systems merge both approaches to mitigate their individual limitations, such as the cold-start problem in collaborative filtering and the       limited scope of content-based filtering.
