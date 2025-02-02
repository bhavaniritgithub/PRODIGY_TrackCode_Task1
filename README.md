# README: Linear Regression Model for House Price Prediction

## Project Overview
This project implements a **Linear Regression** model to predict house prices based on key features such as square footage, number of bedrooms, and number of bathrooms. The dataset is taken from a real estate dataset containing various house attributes.

## Dataset
The dataset consists of:
1. `train.csv` - Contains historical house prices with features for model training.
2. `test.csv` - Contains houses without prices, used for making predictions.

### Selected Features:
- **GrLivArea**: Above-ground living area (square feet)
- **BedroomAbvGr**: Number of bedrooms above ground
- **FullBath**: Number of full bathrooms above ground
- **HalfBath**: Number of half bathrooms above ground

### Target Variable:
- **SalePrice**: The price of the house (dependent variable)

## Installation & Setup
### Prerequisites
- Google Colab / Jupyter Notebook
- Python 3.x
- Required Libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

## How to Run
1. Upload the dataset files (`train.csv` and `test.csv`) to your working directory.
2. Run the `house_price_prediction.py` script in Google Colab.
3. The script:
   - Loads and preprocesses the dataset
   - Splits data into training and testing sets
   - Trains a **Linear Regression** model
   - Evaluates performance using MAE, MSE, and RMSE
   - Generates a prediction file (`predictions.csv`)

## Model Evaluation Metrics
- **Mean Absolute Error (MAE)**: Measures average error in predictions.
- **Mean Squared Error (MSE)**: Penalizes larger errors more than MAE.
- **Root Mean Squared Error (RMSE)**: Standardized error metric.

## Output
- **Graph**: A scatter plot comparing actual vs predicted house prices.
- **predictions.csv**: File containing predicted house prices for test data.

## Troubleshooting
- If you get a `FileNotFoundError`, ensure the correct dataset path is used.
- Handle missing values in datasets before training.
- If predictions seem off, try feature engineering or advanced models.

## Author
This project was implemented as part of **Prodigy Infotech Internship Task 1**.

## License
This project is free to use for educational purposes.
