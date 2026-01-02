# 📂 Machine Learning Projects Portfolio

This repository contains my machine learning projects. Each project is organized in its own folder with a Jupyter Notebook and a detailed README.

---
## 🔹 Projects

### 1. [Adult Income Classification](./AdultIncome/README.md)
Predict whether an individual earns more than $50K annually using the **Adult Census Income dataset**.  
- **Goal:** Classification (income >50K vs ≤50K)  
- **Best Model:** Random Forest  
- **Accuracy:** 84.92%  
- **F1 (weighted):** 84.91%  
- **Notebook:** [`adult_income_classification.ipynb`](./AdultIncome/adult_income_classification.ipynb)  
---
### 2. [Credit Card Customers Segmentation](./CreditCardSegmentation/README.md)
Cluster credit card customers into distinct groups to understand behavior and improve targeting strategies.  
- **Goal:** Customer segmentation with unsupervised learning  
- **Method:** K-Means clustering (with PCA for dimensionality reduction)  
- **Optimal Clusters:** 4
- **Key Insights:**  
  - Segment 1: [High-value customers]  
  - Segment 2: [Budget-conscious users]  
  - Segment 3: [Balanced users]  
  - Segment 4: [Irregular users]  
- **Notebook:** [`credit_card_customers_segmentation.ipynb`](./CreditCardSegmentation/credit_card_customers_segmentation.ipynb)
  
---

### 3. [Bike Rental Analysis](BikeRental/Bike_rental_analysis.ipynb)

Analyze and predict hourly bike rental demand using historical usage data, weather conditions, and temporal patterns.  
- **Goal:** Forecast hourly rental counts (Regression task)  
- **Methods Tested:** Linear Regression, Ridge, Lasso, ElasticNet, Polynomial Regression  
- **Best Model:** Ridge + Polynomial Features (d=2)  
- **Performance Metrics:**  
  - MAE: 329.62  
  - MSE: 187,729.49  
  - RMSE: 433.28  
  - R²: 0.491  

- **Key Insights:**  
  - Weather and seasonality significantly affect rental demand.  
  - Regularized regression (Ridge + Poly) outperformed plain linear models.  
  - Polynomial features captured non-linear relationships better.  

- **Notebooks:**  
  - [`bike_rental_analysis.ipynb`](BikeRental/Bike_rental_analysis.ipynb)  
  - [`Bike_Rentals_Incremental.ipynb`](BikeRental/Bike_Rentals_Incremental.ipynb)
### 4. [Sales Analysis](sales_analysis.ipynb)  
Analyze sales performance data to uncover key business insights, trends, and opportunities for growth.  

- **Goal:** Identify sales patterns, top-performing categories, and revenue drivers  
- **Methods Used:** Exploratory Data Analysis (EDA), Data Cleaning, Aggregations, Visualization  
- **Key Insights:**  
  - Seasonal trends influence sales peaks  
  - Certain product categories contribute disproportionately to revenue  
  - Customer segmentation highlights differences in buying patterns  
- **Visualizations:** Time-series sales trends, category-wise performance charts, customer behavior analysis  
- **Notebook:** [`sales_analysis.ipynb`](sales_analysis.ipynb)  
### 5 Spotify Cohort Analysis
Analyze user listening behavior over time using cohort analysis.

**Problem Type:** Behavioral Analytics  
**Domain:** Music Streaming  

**Highlights:**
- Cohort-based retention analysis
- Engagement trends over time
- Visual storytelling with heatmaps

**Notebook:** [spotify_cohort_analysis.ipynb](./03_Spotify_Cohort_Analysis/spotify_cohort_analysis.ipynb)
 ==============================================================================================================


### 6 Employee Turnover Prediction

**Domain:** HR Analytics

**Problem Statement:**
Employee attrition leads to high hiring costs and productivity loss.

**Objective:** Predict employee attrition

Identify key drivers of turnover
**Tools:** Python, Pandas, Scikit-learn, Seaborn

**Key Insights:** Job satisfaction and overtime strongly impact attrition

Lack of growth opportunities increases turnover risk

**Notebook:** [https://github.com/Jamuna003/ML-PROJECT/blob/main/Employee%20Turnover/Employee_Turnover.ipynb](https://github.com/Jamuna003/ML-PROJECT/blob/main/Employee_Turnover/Employee_Turnover.ipynb)


### 7 Lending Club Loan Data Analysis

Domain: Finance

Problem Statement:
Loan defaults pose financial risks to lending institutions.

Objective:

Analyze loan performance

Identify factors contributing to default risk

Tools: Python, Pandas, Visualization libraries

Key Insights:

High interest rates correlate with defaults

Lower credit grades show higher risk

### 8 Home Loan Data Analysis

Domain: Banking

Problem Statement:
Banks need data-driven insights to reduce home loan default risk.

Objective:

Analyze applicant and loan attributes

Identify approval and risk patterns

Key Insights:

Credit history and income heavily influence approvals

Loan-to-income ratio is a critical risk factor

### 9 Sales Data Analysis

Domain: Business Analytics

Problem Statement:
Businesses need insights into sales performance to improve revenue.

Objective:

Analyze sales trends

Identify high-performing products and regions

Key Insights:

Certain products drive majority of revenue

Sales show clear seasonal patterns

### 10 Bike Rental Demand Analysis (BikeEase)

Domain: Time Series / EDA

Problem Statement:
Bike rental companies must forecast demand to optimize operations.

Objective:

Analyze demand trends

Identify factors affecting bike rentals

Key Insights:

Weather and seasonality strongly affect demand

Peak usage occurs during weekdays and commute hours

### 11 Product Review Sentiment Analysis (NLP Capstone)

Domain: NLP

Problem Statement:
Customer reviews contain valuable sentiment insights.

Objective:

Perform sentiment analysis on product reviews

Extract actionable feedback

Tools: NLP preprocessing, TF-IDF, ML models

Key Insights:

Negative sentiment strongly impacts ratings

Keywords and review length influence sentiment

### 12 Customer Grievance Analysis

Domain: NLP

Problem Statement:
Organizations receive large volumes of customer complaints.

Objective:

Analyze grievance data

Identify recurring complaint themes

Key Insights:

Billing and service delays dominate complaints

Certain categories show repeated issues

### 13 Deep Learning Capstone Project

Domain: Deep Learning

Problem Statement:
Traditional ML models struggle with complex non-linear patterns.

Objective:

Apply neural networks to solve predictive problems

Tools: TensorFlow / Keras

Key Insights:

Deep learning captures complex relationships

Performance improves with tuning and architecture design

### 14 Nestlé HR Policy Chatbot (Generative AI)

Domain: GenAI / NLP

Problem Statement:
Employees struggle to find answers in lengthy HR policy documents.

Objective:

Build a chatbot to answer HR policy queries

Improve employee experience

Key Insights:

Chatbot significantly reduces search time

Demonstrates real-world GenAI usage

### 15 BikeEase Ad Generator (Generative AI)

Domain: GenAI / Marketing

Problem Statement:
Marketing teams need quick, personalized ad content.

Objective:

Generate ad copy automatically using AI

Key Insights:

Saves manual effort

Enables rapid campaign experimentation

### About Me
Jamuna Kumaresan Gomathi
Aspiring Data Analyst | Machine Learning | NLP | Generative AI
Python • SQL • AWS • Tableau

📌 Actively seeking Data Analyst / ML / AI opportunities
