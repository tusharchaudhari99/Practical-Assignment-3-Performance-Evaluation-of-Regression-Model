# Practical-Assignment-3-Performance-Evaluation-of-Regression-Model


## 2. Application
**Salary Prediction using Linear Regression**

## 3. Problem Statement
Develop a Regression Model for a real-world application and evaluate its performance using appropriate metrics. Additionally, implement Gradient Descent optimization for Linear Regression and analyze its performance.

## 4. Dataset
The **Salary Dataset** is used for salary prediction.

The dataset contains the following features:
- Age
- Years of Experience
- Education Level
- Salary

For this practical:
- **Input Features:** Age, Years of Experience, Education Level
- **Target:** Salary

## 5. Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 6. Methods Used

### Linear Regression
Linear Regression is used to predict salary based on age, years of experience, and education level.

### Gradient Descent
Gradient Descent is implemented manually to optimize the parameters of the Linear Regression model by minimizing the cost function.

## 7. Performance Metrics
The models are evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## 8. Implementation
The implementation is performed using Jupyter Notebook.

The notebook includes:

1. Importing required libraries
2. Loading the Salary dataset
3. Checking the dataset
4. Checking missing values
5. Selecting input features and target
6. Splitting the dataset into training and testing data
7. Standardizing input features
8. Implementing Linear Regression
9. Making predictions
10. Evaluating model performance
11. Plotting Actual vs Predicted values
12. Implementing Gradient Descent
13. Plotting Cost vs Epoch
14. Evaluating Gradient Descent performance
15. Comparing Linear Regression and Gradient Descent results

## 9. Results

The performance of both models is evaluated using MAE, MSE, RMSE, and R² Score.

| Performance Metric | Linear Regression | Gradient Descent |
|---|---:|---:|
| MAE | 11,328.0130 | 11,214.7617 |
| MSE | 262,458,894.4315 | 256,946,980.1866 |
| RMSE | 16,200.5832 | 16,029.5658 |
| R² Score | 0.8905 | 0.8928 |

The results show that both models achieved similar performance. The Gradient Descent cost decreases with increasing epochs, showing the optimization of model parameters during training.

## 10. Repository Contents

- `Practical_Assignment_03_Salary_Regression.ipynb` - Jupyter Notebook containing the implementation.
- `salary.csv` - Dataset used for salary prediction.
- `README.md` - Project information and performance results.

## 11. Conclusion

Linear Regression was successfully implemented for salary prediction using the Salary dataset. The model was evaluated using different regression performance metrics. Gradient Descent was also implemented manually, and its performance was analyzed using the cost function and evaluation metrics. Both models achieved similar results, demonstrating the application of regression techniques for salary prediction.
