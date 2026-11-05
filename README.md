# ML CIE-2 Activity 2 – House Price Prediction

**Student Roll Number:** AD3132

## 1. Project Overview

This project implements a Simple Linear Regression model to predict Indian house prices based on carpet area.

The activity is part of Unit II – Supervised Learning: Regression.

## 2. Objective

- Understand and inspect a real-world housing dataset.
- Perform data cleaning and preprocessing.
- Select input and target variables.
- Train a Simple Linear Regression model.
- Evaluate predictions using regression metrics.
- Predict the price of a new house.

## 3. Dataset Information

**Dataset:** House Price (India)  
**Author:** Juhi Bhojani  
**Source:** [Kaggle – House Price (India)](https://www.kaggle.com/datasets/juhibhojani/house-price)

The dataset contains Indian residential property listings with information about carpet area, location, bathrooms and property prices.

## 4. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Data Preprocessing

- Inspected 187,531 records and 21 columns.
- Checked missing values and duplicate records.
- Converted carpet area into numerical square feet.
- Converted property prices from Lakhs and Crores into rupees.
- Removed records with missing or invalid selected values.
- Filtered extreme observations using the 99th percentile upper limits.

**Final dataset:** 94,616 records.

## 6. Feature and Target Selection

- **Input Feature (X):** Carpet Area (sq. ft.)
- **Target Variable (y):** House Price (₹)

Carpet area was selected because it may have a relationship with residential property prices.

## 7. Model Training

**Algorithm:** Simple Linear Regression

**Training and Testing Split:** 80:20

- Training records: 75,692
- Testing records: 18,924

### Linear Regression Equation

y = 13,988.3896x − 4,635,544.8757

Where:
- x represents carpet area in square feet.
- y represents predicted house price in rupees.

## 8. Model Evaluation Results

| Metric | Result |
|---|---:|
| MAE | ₹49,12,634.24 |
| MSE | 57,731,081,132,080.96 |
| RMSE | ₹75,98,097.20 |
| R² Score | 0.5632 |

The model explains approximately 56.32% of the variation in house prices on the test dataset.

## 9. New House Price Prediction

A new property with a carpet area of 1,200 sq. ft. was used for prediction.

**Predicted Price:** Approximately ₹1,21,50,523.

## 10. Conclusion

The project demonstrates how Simple Linear Regression can be used to predict house prices based on carpet area.

The model identifies a positive relationship between carpet area and house price. However, its prediction errors indicate that carpet area alone is insufficient to explain all property price variations.

Additional features such as location, amenities and property condition could improve future model performance.

## 11. Faculty Reference and Acknowledgement

Faculty GitHub Profile: [Princy2129](https://github.com/Princy2129)

This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: https://github.com/Princy2129
