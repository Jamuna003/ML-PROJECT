# Bike Rental Demand Prediction

This project forecasts bike rental counts using the **Bike Sharing dataset**.  
It contains two complementary notebooks: a **baseline analysis** and an **incremental, improved version**.

---

##  Notebooks
- **Baseline Analysis:** [`bike_rental_analysis.ipynb`](./bike_rental_analysis.ipynb)  
- **Incremental Improvements:** [`bike_rental_incremental.ipynb`](./bike_rental_incremental.ipynb)  

---

##  Project Goals
- Explore rental usage patterns across time, weather, and seasonality.  
- Build regression models to forecast demand.  
- Show the progression from a baseline exploratory analysis to a more refined pipeline with advanced validation.  

---

##  Key Differences Between Notebooks
- **Data scope:**  
  - *Analysis:* Static dataset with exploratory analysis and first predictive models.  
  - *Incremental:* Extended pipeline with iterative processing and structured evaluation.  

- **Feature engineering:**  
  - *Analysis:* Basic datetime parsing, weather/temp features, categorical encoding.  
  - *Incremental:* Richer time-based features (hour, day, season, weekday), scaling, and polynomial features.  

- **Models:**  
  - *Analysis:* Linear Regression, Decision Tree, Random Forest.  
  - *Incremental:* Ridge, Lasso, ElasticNet, Polynomial Regression, Gradient models.  

- **Validation & tuning:**  
  - *Analysis:* Simple train/test split, reported only basic accuracy-like results.  
  - *Incremental:* Added **MAE, MSE, RMSE, R²** metrics, 5-fold cross-validation, and hyperparameter tuning.  

- **Outputs:**  
  - *Analysis:* Exploratory plots, correlation heatmaps, baseline model outputs.  
  - *Incremental:* Systematic results tables, evaluation metrics, cross-validation scores, and best-model selection.  

---

## Results
| Notebook        | Best Model                  | Metrics Available |
|-----------------|-----------------------------|------------------|
| Analysis        | Random Forest (baseline)    | Only basic outputs, no MAE/MSE/RMSE/R² |
| Incremental     | Ridge + Polynomial Features | MAE = 329.62, MSE = 187729.49, RMSE = 433.28, R² = 0.491 |

*(Values shown for Incremental come from cross-validation; Analysis was exploratory only.)*  

---

## Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

##  How to Run
Clone this repository and navigate to the project folder:

```bash
git clone https://github.com/Jamuna003/ML-PROJECT.git
cd ML-PROJECT/BikeRental
jupyter notebook bike_rental_analysis.ipynb
# or
jupyter notebook bike_rental_incremental.ipynb
