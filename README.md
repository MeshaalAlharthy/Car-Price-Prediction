# Car-Price-Prediction

This project aims to predict car prices based on various features like year, mileage, and brand using machine learning models. The goal is to explore different regression models, evaluate their performance, and fine-tune them for accurate predictions.

## Features

* **Data Preprocessing**: Handling missing values and encoding categorical features.
* **Feature Engineering**: Creating new features like car age and price per kilometer.
* **Modeling**: Training multiple regression models such as Linear Regression, Random Forest, Gradient Boosting, and XGBoost.
* **Hyperparameter Tuning**: Using GridSearchCV for model optimization.
* **Model Evaluation**: Evaluating models using R², MAE, and RMSE metrics.
* **Model Saving**: Saving the best model using `joblib` for future predictions.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Car-Price-Prediction.git
   cd Car-Price-Prediction
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the notebook or script to load and preprocess the data.
2. Choose the model you want to train (e.g., `RandomForestRegressor`).
3. Evaluate the model’s performance using cross-validation.
4. Once the best model is selected, it is trained on the full dataset and saved as `car_price_model.pkl`.

## Dependencies

* pandas
* numpy
* scikit-learn
* seaborn
* xgboost
* joblib

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
