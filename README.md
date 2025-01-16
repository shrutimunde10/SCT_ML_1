# SCT_ML_1
This project builds a linear regression model to predict house prices using square footage, number of bedrooms, and bathrooms. It includes data preprocessing, EDA, model training, and evaluation with metrics like R-squared and MSE. Using Python and libraries like NumPy, Pandas, and Scikit-learn, it highlights key feature-price relationships.
# House Price Predictor

This project is a machine learning model implemented in Python that predicts house prices based on key features like square footage, number of bedrooms, and bathrooms. The prediction is powered by a linear regression model, and the application includes an interactive command-line interface for user input.

---

## Features

- **Linear Regression Model**: A simple yet effective regression model used to predict house prices.

- **Interactive User Input**: Users can input house details such as:
  - Square footage
  - Number of bedrooms
  - Number of bathrooms
  The model outputs a predicted price based on these inputs.

- **Data Visualization**: The application includes visualizations to enhance understanding of model performance:
  - Residual analysis
  - Predicted vs. actual price comparison
  - Feature importance analysis

---

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

### Dataset

Ensure the dataset (`train.csv`) is available in the project directory. This dataset should contain the following columns:
- `GrLivArea` (Above-ground living area in square feet)
- `BedroomAbvGr` (Number of bedrooms above ground)
- `FullBath` (Number of full bathrooms)
- `SalePrice` (Target variable: house sale price)

### Running the Application

1. Clone the repository and navigate to the project directory.
2. Run the script:
   ```bash
   python house_price_predictor.py
   ```
3. Follow the interactive prompts:
   ```
   Enter square footage (e.g., 1500):
   Enter the number of bedrooms (e.g., 3):
   Enter the number of bathrooms (e.g., 2):
   ```
4. The predicted house price will be displayed on the command line.

---

## Visualization

The project includes the following visualization capabilities:

1. **Residual Analysis**:
   - Visualizes the distribution of residuals to assess model accuracy.
   - Ensures the errors are normally distributed.

2. **Prediction vs. Actual Plot**:
   - Shows how well the model's predicted prices align with actual prices from the dataset.

3. **Feature Importance**:
   - Highlights the contribution of each feature to the model’s predictions.

---

## Acknowledgments

- The dataset used in this project was sourced from [Kaggle](https://www.kaggle.com/).
- Inspiration for this project was drawn from real estate price prediction challenges and tutorials.

---

## Future Improvements

- Implement additional machine learning models (e.g., Decision Trees, Random Forests) for comparison.
- Add support for more house features, such as lot size and year built.
- Deploy the model via a web or mobile application for broader accessibility.
- Enhance the user interface with a graphical or web-based design.

---

## License

This project is open-source and available under the [MIT License](LICENSE).


