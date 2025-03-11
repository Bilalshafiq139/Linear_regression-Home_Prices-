# Linear_regression-Home_Prices-
This repository contains a Python script that implements Linear Regression to predict rental prices based on apartment square footage

# Linear Regression Model for Predicting Rent Prices

## Overview
This repository contains a Python script that implements **Linear Regression** to predict rental prices based on apartment square footage. The model is trained using real estate data and aims to provide an efficient way to estimate rent prices.

---

## **Problem Statement**
Real estate companies often need to estimate rental prices based on apartment size. This helps potential renters gauge the affordability of an apartment based on their needs. Using a linear regression model, this script predicts the **monthly rent** of an apartment based solely on its **square footage**.

### **How the Model Helps**
- Helps real estate agents and landlords set competitive rent prices.
- Enables renters to estimate costs based on apartment size.
- Provides a data-driven approach to rental price prediction.

### **Dataset Description**
The dataset contains two key columns:
- **square_footage**: The size of the apartment in square feet.
- **monthly_rent**: The monthly rental price in dollars.

---

## **How the Script Works**
1. **Data Loading**: The script reads the dataset from a CSV file.
2. **Data Preprocessing**:
   - Observes the relationship between `square_footage` and `monthly_rent` using a scatter plot.
   - Splits the dataset into **training (80%)** and **testing (20%)** sets.
3. **Model Training**:
   - Implements **Simple Linear Regression** using `sklearn.linear_model.LinearRegression()`.
   - Fits the model on the training dataset.
4. **Prediction**:
   - Makes predictions on the test dataset.
5. **Visualization**:
   - Plots the regression line against the actual data points.

---

## **Dependencies**
Ensure you have the following Python libraries installed:
```sh
pip install numpy pandas matplotlib scikit-learn
```

---

## **How to Run the Script**
1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Navigate to the project folder:
   ```sh
   cd <project_folder>
   ```
3. Run the Python script:
   ```sh
   python linear_regression.py
   ```
4. Follow the output to view predictions and plots.

---

## **Contributing**
Contributions are welcome! Feel free to fork this repository and submit a pull request with improvements or additional features.

---



