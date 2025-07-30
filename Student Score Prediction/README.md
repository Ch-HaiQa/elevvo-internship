# Student Performance Factors - Score Prediction

This project predicts students' **exam scores** based on various performance factors using **Linear Regression** and **Polynomial Regression**. The dataset is taken from Kaggle (uploaded as `StudentPerformanceFactors.csv`).

## Project Objective

- Understand factors affecting student performance.
- Build regression models to predict exam scores based on given attributes.
- Compare linear and polynomial regression performances.
- Visualize actual vs predicted results and compare evaluation metrics.

## Dataset Overview

The dataset contains multiple features such as:
- Study hours
- Attendance
- Parental education level
- Gender
- Test preparation
- Internet access  
and more.

The target variable is:
- `Exam_Score`

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

## Workflow Steps

1. **Data Preprocessing**
   - Handle missing values.
   - Encode categorical features using `LabelEncoder`.

2. **Data Splitting**
   - Split into training and testing sets using `train_test_split`.

3. **Linear Regression**
   - Train a simple linear model.
   - Visualize and evaluate using R² and MSE.

4. **Polynomial Regression**
   - Apply 2nd-degree polynomial transformation.
   - Train a regression model and evaluate.

5. **Performance Comparison**
   - Visual comparison using scatter plots.
   - Metric comparison using bar chart.

## Model Evaluation

Models are evaluated using:
- **R² Score**
- **Mean Squared Error (MSE)**
- **Actual vs Predicted Score Scatter Plots**
- **Bar Chart for Performance Comparison**

## Bonus

- Tried **Polynomial Regression** to improve performance.
- Compared results visually and statistically.

