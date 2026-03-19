# Used Car Price Prediction

**Authors:**  
Aniruddh Rajagopal | Dhatrija Sukasi | Haeyeon Jeong | Likhitha Reddy Bairu  

---

## Introduction

The used car market is highly dynamic, with prices influenced by multiple factors such as vehicle age, mileage, engine specifications, and ownership history. Accurately estimating a car’s price can help buyers make informed decisions and assist sellers in setting competitive prices.

This project applies machine learning techniques to analyze used car data and build predictive models for price estimation and classification tasks.

---

## Objectives

- Build models to predict used car prices  
- Identify key factors influencing car valuation  
- Analyze patterns in mileage, ownership, and transmission  
- Support data-driven decision making in the used car market  

---

## Dataset Description

The dataset contains detailed information about used cars, including specifications and usage history.
https://www.kaggle.com/datasets/sukhmandeepsinghbrar/car-price-prediction-dataset/data<img width="468" height="50" alt="image" src="https://github.com/user-attachments/assets/09b4b024-64aa-418d-93fe-04c949223462" />

**Key Features:**
- Car Name  
- Year  
- Selling Price  
- Kilometers Driven  
- Fuel Type  
- Seller Type  
- Transmission  
- Owner  
- Mileage  
- Engine  
- Max Power  
- Seats  

---

## SMART Questions

- Q1: How can we predict used car prices, and which features are most important?  
- Q2: What is the likelihood of a car being sold by its first owner?  
- Q3: Can we predict whether a car has exceeded 60,000 miles driven?  

---

## Data Preprocessing

- Removed unnecessary columns  
- Created car_age from year  
- Converted km_driven to miles_driven  
- Standardized price into price_in_usd  
- Cleaned and simplified mileage values  
- Encoded categorical variables  

---

## Modeling Approach

Models used:

- Decision Tree (interpretable model)  
- Classification models for mileage prediction  

**Training Setup:**
- Train/Test split  
- Feature encoding applied  
- Evaluation using accuracy and confusion matrix  

---

## Results

- Model Accuracy: ~74.5% – 76.6%  
- Good performance in classifying mileage thresholds  
- Decision tree provided interpretable rules  

---

## Feature Importance / Insights

Key influential features:

- Car Age  
- Mileage / Distance Driven  
- Engine Power  
- Transmission Type  
- Seller Type  

---

## Key Findings

- Older cars and higher mileage reduce price  
- Engine power and transmission significantly affect value  
- Ownership history impacts resale likelihood  

---

## Conclusion

This project demonstrates how machine learning can effectively predict used car prices and uncover key market trends. The insights can help buyers, sellers, and businesses make better decisions.

---

## How to Run

1. Open the `.Rmd` file in RStudio  
2. Install required libraries:

```r
install.packages(c("dplyr", "ggplot2", "caret", "rpart", "rpart.plot", "randomForest", "e1071"))
