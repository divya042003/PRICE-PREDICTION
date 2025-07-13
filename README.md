#  House Price Prediction using Machine Learning

This project aims to predict house prices based on various features using supervised machine learning algorithms. Accurate house price prediction can help buyers, sellers, and real estate agents make informed decisions.



## Dataset

We use the **Ames Housing Dataset**, which includes detailed information about residential homes in Ames, Iowa.

You can download the dataset from:  
- [Kaggle - Ames Housing Dataset](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)

### Key Features
- Lot Area
- Overall Quality & Condition
- Year Built
- Total Basement Area
- Number of Bathrooms
- Garage Type & Area
- Neighborhood
- Sale Price (target)


##  Machine Learning Workflow

1. Data Cleaning & Preprocessing
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling

2. Exploratory Data Analysis (EDA)
   - Correlation heatmaps
   - Feature importance plots

3. Model Training
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - XGBoost (Optional)

4. Evaluation Metrics
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score


##  Results

| Model               | RMSE  | R² Score |
|--------------------|-------|----------|
| Linear Regression  | 32,500| 0.87     |
| Random Forest      | 24,300| 0.91     |
| XGBoost (Tuned)    | 21,700| 0.93     |

>  *These are sample results — update with your actual numbers.*

---



