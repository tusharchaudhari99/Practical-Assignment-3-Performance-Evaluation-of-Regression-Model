# Practical-Assignment-3-Performance-Evaluation-of-Regression-Model
Performance evaluation of Linear Regression and Gradient Descent models using a Salary dataset.  Select Public.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/Scikit--learn-Regression-orange?logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
  <img src="https://img.shields.io/badge/Assignment-03-purple" />
</p>

---

## 📌 1. Introduction

This practical focuses on the implementation and performance evaluation of regression models using a Salary dataset. Two approaches, Scikit-learn Linear Regression and manually implemented Gradient Descent, are used to predict salary based on age, years of experience, and education level.

## 🎯 2. Problem Statement

To implement and evaluate regression models for salary prediction using the Salary dataset and compare their performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

## 🎯 3. Objectives

- To understand the concept of regression.
- To implement Linear Regression using Scikit-learn.
- To implement Gradient Descent manually.
- To predict salary using the selected input features.
- To evaluate the models using different performance metrics.
- To compare the performance of both regression models.

## 📚 4. Theory

### Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict a continuous output. It models the relationship between input features and a target variable using a linear equation.

### Gradient Descent

Gradient Descent is an optimization algorithm used to minimize the cost function by iteratively updating weights and bias. In this practical, batch Gradient Descent is implemented manually.

## 📂 5. Dataset Description

The practical uses the `salary.csv` dataset.

| Parameter | Description |
|---|---|
| Dataset | Salary |
| Input features | Age, Years of Experience, Education Level |
| Target variable | Salary |
| Problem type | Regression |
| Training data | 80% |
| Testing data | 20% |
| Random state | 42 |

Missing values in the selected columns are removed before model training.

## ⚙️ 6. Algorithms Used

**1. Scikit-learn Linear Regression**
- Standardize the input features.
- Train the Linear Regression model.
- Predict salaries on the test dataset.
- Calculate the performance metrics.

**2. Batch Gradient Descent**
- Initialize weights and bias.
- Calculate predicted values and errors.
- Update weights and bias iteratively.
- Repeat for 1000 epochs.
- Calculate the final performance metrics.

## 🛠️ 7. Technologies and Libraries

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Jupyter Notebook | Implementation |
| Pandas | Dataset handling |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Scikit-learn | Linear Regression and evaluation |

## 🔄 8. Methodology

1. Import the required libraries.
2. Load the Salary dataset.
3. Check and remove missing values.
4. Select the input features and target variable.
5. Split the dataset into training and testing sets.
6. Standardize the input features.
7. Train the Linear Regression model.
8. Implement and train Gradient Descent.
9. Predict salary values using both models.
10. Calculate and compare performance metrics.
11. Visualize the model predictions and cost function.

## 📈 9. Performance Evaluation

The following metrics are used to evaluate the regression models.

| Metric | Description |
|---|---|
| MAE | Average absolute difference between actual and predicted values |
| MSE | Average of squared prediction errors |
| RMSE | Square root of MSE |
| R² Score | Proportion of target variance explained by the model |

### Model Comparison

| Performance Metric | Linear Regression | Gradient Descent |
|---|---:|---:|
| MAE | 11,328.0130 | 11,214.7617 |
| MSE | 262,458,894.4315 | 256,946,980.1866 |
| RMSE | 16,200.5832 | 16,029.5658 |
| R² Score | 0.8905 | 0.8928 |

### Observations

- Both models achieved R² scores close to 0.89.
- Both models produced similar prediction errors.
- Gradient Descent produced slightly lower error metrics in this experiment.
- The actual and predicted salary values were visualized using a scatter plot.
- The cost function was plotted over epochs to observe the optimization process.

## 📊 10. Visualizations

The notebook includes the following visualizations:

- **Actual vs Predicted Salary:** A scatter plot comparing actual salaries with the model's predictions.
- **Cost vs Epoch:** A line graph showing how the Gradient Descent cost changes over training epochs.

## 💻 11. How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone https://github.com/YOUR-USERNAME/Practical-Assignment-3-Performance-Evaluation-of-Regression-Model.git
```

**Step 2:** Open the project folder.

```bash
cd Practical-Assignment-3-Performance-Evaluation-of-Regression-Model
```

**Step 3:** Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

**Step 4:** Start Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open the notebook and run all cells. Keep `salary.csv` in the same folder as the notebook.


## ✅ 12. Conclusion

In this practical, Scikit-learn Linear Regression and manually implemented Gradient Descent were used to predict salaries using age, years of experience, and education level. Both models were evaluated using MAE, MSE, RMSE, and R² Score. The results showed similar performance for both models. This practical provided an understanding of regression model implementation, prediction, and performance evaluation.



<p align="center">
  <b>Practical Assignment 3 – Performance Evaluation of Regression Model</b>
</p>
