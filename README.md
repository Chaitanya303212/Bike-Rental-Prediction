# Bike Rental Prediction Using Machine Learning

## Project Overview
This project predicts daily bike rental demand using machine learning techniques. It analyzes the relationship between bike rental counts and features such as weather, season, temperature, humidity, and other available variables.

## Objectives
- Explore and analyze the bike rental dataset.
- Perform data preprocessing and exploratory data analysis.
- Train and compare multiple machine learning models.
- Evaluate model performance using regression metrics.

## Models Evaluated
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

## Best Model Results
The Linear Regression model achieved the following reported results:

| Metric | Value |
|---|---:|
| MAE | 791.67 |
| RMSE | 1093.74 |
| R² Score | 0.66 |

These results are based on the project's current evaluation split.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Files
- `PRCP_1018_Bike_Rental_Prediction.ipynb` — Data analysis, model training, and evaluation.
- `day.csv` — Daily bike rental dataset.
- `hour.csv` — Hourly bike rental dataset, if used.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter Notebook or VS Code.
4. Ensure the dataset files are in the expected location.
5. Run the notebook cells in order.

## Conclusion
This project demonstrates how machine learning regression models can be used to estimate bike rental demand. The evaluated models provide a basis for comparing prediction performance and understanding factors associated with rental demand.