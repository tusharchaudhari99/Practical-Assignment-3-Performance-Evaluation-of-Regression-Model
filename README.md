# Practical Assignment 3: Performance Evaluation of Regression Model

<p align="center">
  <img src="https://img.shields.io/badge/Practical-03-blue" />
  <img src="https://img.shields.io/badge/Domain-Machine%20Learning-purple" />
  <img src="https://img.shields.io/badge/Language-Python-yellow?logo=python" />
  <img src="https://img.shields.io/badge/Models-Linear%20Regression-green" />
</p>

---

## 1. Project Overview

This project focuses on implementing and evaluating regression models for salary prediction using a Salary dataset. It includes Scikit-learn Linear Regression and a manually implemented Gradient Descent algorithm. Both models are evaluated and compared using standard regression performance metrics.

## 2. Application

**Salary Prediction Using Regression Models**

The application predicts salary based on age, years of experience, and education level. It demonstrates how regression techniques can be applied to a real-world prediction problem.

## 3. Problem Statement

Develop a regression model for salary prediction and evaluate its performance using appropriate metrics. Additionally, implement Gradient Descent optimization for Linear Regression and analyze and compare the performance of both approaches.

## 4. Objectives

- Understand the fundamentals of regression.
- Prepare and preprocess the Salary dataset.
- Implement Linear Regression using Scikit-learn.
- Implement Batch Gradient Descent manually.
- Predict salary using selected input features.
- Evaluate the models using standard regression metrics.
- Compare the performance of both models.
- Visualize predictions and the optimization process.

## 5. Dataset Description

The project uses the Salary dataset stored in `salary.csv`.

| Attribute | Description |
|---|---|
| Age | Age of the individual |
| Years of Experience | Total years of work experience |
| Education Level | Education level represented numerically |
| Salary | Salary value to be predicted |

**Input features:** Age, Years of Experience, Education Level

**Target variable:** Salary

The dataset is checked for missing values, and rows with missing values in the selected columns are removed before model training.

## 6. Technologies and Libraries

| Technology | Purpose |
|---|---|
| Python | Model implementation |
| Jupyter Notebook | Development environment |
| Pandas | Data loading and preprocessing |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Scikit-learn | Linear Regression and evaluation |

## 7. Methodology

The project follows these steps:

1. Import the required Python libraries.
2. Load the Salary dataset.
3. Inspect the dataset and its columns.
4. Identify and remove missing values.
5. Select the input features and target variable.
6. Split the data into training and testing sets.
7. Standardize the input features.
8. Train the Scikit-learn Linear Regression model.
9. Generate predictions and calculate performance metrics.
10. Implement Batch Gradient Descent manually.
11. Train the model over multiple epochs.
12. Generate predictions using Gradient Descent.
13. Evaluate and compare both models.
14. Visualize actual versus predicted values and the cost function.

## 8. Algorithms Used

### 8.1 Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict continuous values. It models the relationship between input features and the target variable by fitting a linear equation.

In this project, Scikit-learn is used to train the model and predict salaries from the selected input features.

### 8.2 Batch Gradient Descent

Gradient Descent is an optimization algorithm that minimizes the cost function by updating the model's weights and bias iteratively.

In this project:
- Initial weights and bias are set to zero.
- A learning rate of 0.01 is used.
- The model is trained for 1000 epochs.
- The mean squared error is used as the cost function.
- The cost is recorded after each parameter update.

## 9. Performance Evaluation

The models are evaluated using the following metrics:

| Metric | Description |
|---|---|
| MAE | Measures the average absolute difference between actual and predicted salaries. |
| MSE | Measures the average squared prediction error. |
| RMSE | Represents the square root of MSE in the target's units. |
| R² Score | Measures how much of the variation in the target is explained by the model. |

### Model Performance Comparison

| Metric | Linear Regression | Gradient Descent |
|---|---:|---:|
| MAE | 11,328.0130 | 11,214.7617 |
| MSE | 262,458,894.4315 | 256,946,980.1866 |
| RMSE | 16,200.5832 | 16,029.5658 |
| R² Score | 0.8905 | 0.8928 |

### Observations

- Both models achieved similar R² scores.
- Gradient Descent produced slightly lower MAE, MSE, and RMSE in this experiment.
- The cost history helps observe how the Gradient Descent model learns over successive epochs.
- The actual-versus-predicted plot helps visualize the prediction performance.

## 10. Visualizations

The Jupyter Notebook includes the following graphs:

**Actual vs Predicted Salary**

A scatter plot comparing actual salary values with the predictions generated by Linear Regression.

**Cost vs Epoch**

A line plot showing the change in the Gradient Descent cost function over 1000 epochs.

These visualizations help examine prediction accuracy and the optimization process.

## 11. Results and Discussion

Both regression approaches were implemented using the same training and testing split. The performance was measured using four standard regression metrics.

The Scikit-learn Linear Regression model achieved an R² score of 0.8905, while the manually implemented Gradient Descent model achieved 0.8928. Both approaches produced comparable results on the test dataset.

The error metrics and visualizations provide a quantitative and graphical understanding of the models' performance.

## 12. Repository Structure

```text
Practical-Assignment-3-Performance-Evaluation-of-Regression-Model/
│
├── README.md
├── Practical_Assignment_03_Salary_Regression.ipynb
└── salary.csv
```

## 13. Learning Outcomes

After completing this practical, the following concepts were explored:

- Data loading and preprocessing using Pandas.
- Feature standardization using Scikit-learn.
- Training and testing regression models.
- Manual implementation of Batch Gradient Descent.
- Evaluation of regression models using performance metrics.
- Visualization of model predictions and cost reduction.
- Comparison of two regression approaches.

## 14. Conclusion

In this practical, Linear Regression and manually implemented Batch Gradient Descent were used for salary prediction using age, years of experience, and education level. Both models were evaluated using MAE, MSE, RMSE, and R² Score. The results showed similar performance, with Gradient Descent producing slightly lower error values in this experiment. The practical provided hands-on experience in regression implementation, optimization, evaluation, and visualization.

## 15. Author

**Tushar Vijay Chaudhari**

- **Institute:** MIT Academy of Engineering, Alandi, Pune
- **Department:** Electronics and Telecommunication Engineering
- **Practical:** Assignment 03
- **Subject:** AIML

---

<p align="center">
  <b>Practical Assignment 3 | Performance Evaluation of Regression Model</b>
</p>
