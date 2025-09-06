# Medical Insurance Prediction Model

Medical insurance is one of the most crucial aspects of healthcare, and machine learning techniques can play a significant role in analyzing and predicting medical insurance costs. In this report, we will discuss a machine learning project that uses linear regression to analyze and predict medical insurance costs.

---

## Introduction
The goal of this project is to build a predictive model that can estimate the medical insurance costs for individuals based on their age, gender, BMI, smoking status, and other related factors. The dataset used in this project contains information about medical insurance costs for a group of people based on these factors.

---

## Data Collection and Preprocessing
- The dataset used in this project was obtained from **Kaggle**.  
- It contains **1338 records** and **7 columns**, including:
  - `age`
  - `sex`
  - `BMI`
  - `children`
  - `smoker`
  - `region`
  - `charges`  

- We removed the **region** column since it did not provide significant insights for our analysis.  
- We converted the **sex** and **smoker** columns into **binary variables (0 or 1)** for easier analysis.  
- Checked for **missing values** → none were found.  
- Split the data into **training (75%)** and **testing (25%)** sets.  

---

## Model Building
- We used **Linear Regression**, a machine learning algorithm that models the relationship between a dependent variable and independent variables.  
- Dependent variable: **Medical insurance costs (`charges`)**  
- Independent variables: **age, sex, BMI, children, smoker**  

Steps:
1. Created a linear regression model using the **training data**.  
2. Used the model to predict medical insurance costs on the **test data**.  
3. Evaluated performance using:
   - **Mean Absolute Error (MAE)**
   - **Mean Squared Error (MSE)**
   - **Root Mean Squared Error (RMSE)**  
4. Plotted a **scatter plot** of predicted vs. actual values to visualize performance.  

---

## Results
- **MAE:** 3,534.50  
- **MSE:** 25,306,900.17  
- **RMSE:** 5,030.47  

The scatter plot of predicted versus actual values showed a strong linear relationship, indicating a good fit of the model.

---

## Conclusion
In conclusion, our machine learning project successfully used **linear regression** to predict medical insurance costs based on **age, gender, BMI, smoking status, and other related factors**.  

The model performed well on the test data, and the results were consistent with our expectations.  

**Linear regression** is a simple and effective machine learning algorithm that can be used in various applications, including **medical insurance cost prediction**.
