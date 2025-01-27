# Testing the Model - Exercise Solution

This repository contains the solution to the "Testing the Model" exercise from my Udemy data science learning course. It is part of my ongoing journey to develop proficiency in data science and machine learning.

---

## About the Exercise

In this exercise, we focus on testing a machine learning model to evaluate its generalization performance. Model testing is a crucial step in understanding how well a trained model performs on unseen data.

### Objectives
- Evaluate the model using testing datasets.
- Interpret key performance metrics.
- Compare testing performance with training results to identify overfitting or underfitting.

---

## Dataset Details

- **Dataset Name**: `real_estate_price_size_year.csv`
- **Target Variable**: Price (dependent variable).
- **Features**:
  - Size: Square footage of the property.
  - Year: Year of construction.

---

## Tools and Libraries Used

- **Python**
- **NumPy**: For numerical computations.
- **Pandas**: For dataset manipulation.
- **Matplotlib/Seaborn**: For data visualization.
- **Scikit-learn**: For model testing and evaluation.

---

## Key Steps in the Notebook

1. **Import Libraries and Load Data**:
   Load the dataset and inspect its structure.
2. **Split Data into Training and Testing Sets**:
   Divide the data into training and testing subsets.
3. **Train the Model**:
   Train a linear regression model on the training set.
4. **Evaluate the Model**:
   - Calculate performance metrics such as:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)
   - Analyze predictions on the test set.
5. **Draw Conclusions**:
   Compare testing and training results to assess model reliability.

![download](https://github.com/user-attachments/assets/7c8c9feb-1153-4cef-9103-21f19098dfcf)

---

## Learning Reflection
This exercise helped me understand the importance of testing models to ensure they generalize well to unseen data. Through this, I gained insights into balancing training and testing performance to prevent overfitting.
