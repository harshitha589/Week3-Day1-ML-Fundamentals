# Machine Learning Fundamentals

## Overview

This project demonstrates the complete Machine Learning workflow using Python and Scikit-learn. The objective is to predict student marks based on Study Hours, Attendance, and Assignments using a Linear Regression model.

The project covers data exploration, feature selection, train-test splitting, model training, prediction, evaluation, and data visualization using Plotly.

## Dataset

The Student Performance Dataset contains the following attributes:

| Feature     | Description                              |
| ----------- | ---------------------------------------- |
| Study_Hours | Number of hours studied                  |
| Attendance  | Student attendance percentage            |
| Assignments | Number of assignments completed          |
| Marks       | Student marks obtained (Target Variable) |

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Plotly
* Google Colab

## Project Workflow

### 1. Dataset Exploration

* Loaded the dataset using Pandas
* Displayed first and last five rows
* Checked dataset shape
* Displayed column names
* Examined data types
* Generated summary statistics

### 2. Feature and Label Identification

* Features:

  * Study_Hours
  * Attendance
  * Assignments
* Label:

  * Marks

### 3. Train-Test Split

* Training Data: 80%
* Testing Data: 20%

### 4. Model Training

* Implemented Linear Regression
* Trained the model using training data
* Obtained slope (coefficients) and intercept

### 5. Predictions

* Predicted marks for new student records

### 6. Model Evaluation

* Mean Absolute Error (MAE)
* R² Score

### 7. Data Visualization

Created the following visualizations using Plotly:

* Study Hours vs Marks
* Attendance vs Marks
* Assignments vs Marks
* Regression Line Visualization
* Predicted Marks Trend

## Repository Structure

```text
Week3-Day1-ML-Fundamentals
│
├── assignment.ipynb
├── student_performance.csv
├── ml_workflow.txt
├── answers.txt
├── README.md
│
└── screenshots
    ├── plot1.png
    ├── plot2.png
    ├── plot3.png
    ├── plot4.png
    └── plot5.png
```

## Learning Outcomes

Through this project, I learned:

* Basics of Machine Learning
* Features and Labels
* Train-Test Split
* Linear Regression
* Model Evaluation
* Data Visualization with Plotly
* Making Predictions using New Data

## Conclusion

This project provided hands-on experience with the complete Machine Learning workflow. It helped in understanding how data is prepared, how models are trained, evaluated, and how predictions are made using Linear Regression.
