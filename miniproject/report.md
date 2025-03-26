# Used Cars Market Analysis (Kaggle Dataset)

## Overview  
This dataset contains scraped data from Cars24, a popular online marketplace for buying and selling used cars. It provides detailed information on various pre-owned car listings.

## Prediction Goal  
Predicting used car prices in market based on key factors such as:  
- Engine Capacity
- Model
- Manufacturing Year
- Price
- Kilometers driven
- Fuel type
- Transmission Type ( Automatic, Manual)
- Ownership History (First-hand, Second-hand, etc.)
- Availability of Spare Key
- Imperfections
- Repainted Parts

## Data Cleaning  
- The dataset had no missing values.  
- Removed SpareKey category, as it had no significant impact on price prediction.  
- Used Quick Build with default settings during training.  

## Model Performance  
- The model predicts car prices within ±45,491.872 of the actual price.  
- Achieved an R² score of 0.953, indicating strong predictive accuracy.  

## Key Findings  
- Engine capacity has the highest impact on price prediction.  
