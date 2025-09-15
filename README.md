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
- **Performance Metrics (on test set):**  
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
