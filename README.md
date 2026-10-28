# Marine Age Prediction

## Project Overview
Marine Age Prediction is a machine learning project that uses physical measurements of abalone, a marine shellfish, to estimate its age using the number of rings in its shell. The project focuses on applying Linear Regression and regularization techniques to understand and predict the relationship between physical characteristics and ring count.

## Objectives
- Understand and preprocess the dataset.
- Explore relationships between physical measurements and ring count.
- Build a Linear Regression model.
- Compare Linear Regression with Ridge, Lasso, and ElasticNet Regression.
- Evaluate model performance using MAE, RMSE, and R².
- Apply cross-validation and hyperparameter tuning.
- Analyze residuals and multicollinearity to understand model limitations.

## Dataset
The project uses the Abalone dataset.

- **Target variable:** `Rings`
- **Input features:** Sex, Length, Diameter, Height, Whole Weight, Shucked Weight, Viscera Weight, and Shell Weight.
- **Dataset size:** 4,177 observations.

The number of rings is used as a proxy for age. It is not a direct measurement of age in years.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## Machine Learning Models
1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. ElasticNet Regression

## Evaluation Metrics
- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted values.
- **RMSE (Root Mean Squared Error):** Measures prediction error while penalizing larger errors more strongly.
- **R² Score:** Measures how much of the variation in the target variable is explained by the model.

Cross-validation and hyperparameter tuning are used to support model selection. Residual analysis and multicollinearity diagnostics help assess model assumptions and limitations.

## Project Structure
```text
Marine-Age-Prediction/
├── README.md
├── abalone.data.csv
└── Marine_Age_Prediction.ipynb
```

*Note: Update the filenames above if your uploaded files have different names.*

## How to Run the Project
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Ensure the dataset is in the correct folder.
5. Run the notebook cells in order.

Install the libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
```

## Conclusion
This project applies Linear Regression and regularization techniques to predict shellfish ring count from physical measurements. The models are evaluated using MAE, RMSE, and R², with cross-validation and hyperparameter tuning used to support model selection. Residual analysis and multicollinearity diagnostics help identify potential limitations. Since ring count is an age proxy, predictions may be less accurate for unusual observations.

## Author
**Chandana Yemul**

MSc Data Analytics | Machine Learning Project
