# Used Car Price Prediction

## Project Overview
This project aims to predict the prices of used cars using machine learning techniques on a dataset containing approximately 6,000 entries and 14 features. The dataset includes various attributes such as the make, model, year, mileage, and other relevant characteristics of used cars, which contribute to their pricing.

## Dataset
- **Number of Rows**: ~6000
- **Number of Columns**: 14
- **Features**: The dataset includes features such as:
  - Make
  - Model
  - Year
  - Kilometers Driven
  - Fuel Type
  - Power
  - Seats
  - Price (Target Variable)
- **Dataset Link**: [Used Car Price Prediction Dataset](https://www.kaggle.com/datasets/nitishjolly/used-car-price-prediction)

## Methodology
The project utilizes various regression models to predict car prices and evaluates their performance using two key metrics: R² (coefficient of determination) and RMSE (Root Mean Square Error).

### Technologies Used
- **Python**: Programming language for implementing machine learning algorithms.
- **Pandas**: Data manipulation and analysis library.
- **NumPy**: Library for numerical computations.
- **Scikit-learn**: Machine learning library for model training and evaluation.
- **Seaborn**: Statistical data visualization library for creating informative graphics.
- **Matplotlib**: Plotting library for generating visualizations.

### Models Evaluated

| Model                | R²       | RMSE      |
|----------------------|----------|-----------|
| Linear Regression     | 0.906300 | 0.253686  |
| Random Forest         | 0.918572 | 0.236490  |
| Decision Tree         | 0.866086 | 0.303278  |
| Gradient Boost        | 0.918940 | 0.235955  |
| Ridge                 | 0.906352 | 0.253616  |
| Lasso                 | 0.906618 | 0.253255  |

## Results
- The **Gradient Boost** model achieved the highest R² value of **0.918940** and the lowest RMSE of **0.235955**, indicating that it is the most effective model for this dataset.
- The **Random Forest** model also performed well with an R² of **0.918572** and RMSE of **0.236490**.

## Installation and Usage

To run the notebook, ensure you have the required libraries installed. You can install them using pip:

```bash
pip install -r requirements.txt
