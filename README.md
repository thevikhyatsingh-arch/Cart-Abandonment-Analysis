#  Cart Abandonment Analysis & Prediction

##  Project Overview

This project analyzes customer cart abandonment behavior for an e-commerce platform.  
The objective was to understand why customers add products to their cart but do not complete their purchase, identify the biggest drop-off points in the customer journey, and build a predictive model to support targeted recovery campaigns.

The project follows a complete analytics workflow:
- Business problem understanding
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Customer behavior analysis
- Feature engineering
- Predictive modelling
- Business recommendations

---

#  Business Problem

A significant number of customers were adding items to their shopping cart but leaving without purchasing.

The analysis aimed to answer:

1. Where do customers leave the purchase funnel?
2. Which customer segments have higher abandonment?
3. What factors increase or reduce abandonment probability?
4. How can the business improve conversion rates?

---

#  Dataset Information

The dataset contains customer session-level data from an e-commerce platform.

Key information:

- Time Period: January 2023 – December 2024
- Records Analyzed: 1,000+ customer sessions
- Unit of Analysis: One website session
- Data Sources:
  - Web analytics platform
  - Order management system

Features include:

- Customer journey stages
- Cart value
- Number of items
- Device type
- Traffic source
- City tier
- Customer history
- Discounts
- Session behaviour

---

#  Data Cleaning & Preprocessing

Performed a complete data quality improvement process:

### Issues handled:

✔ Duplicate records removed  
✔ Mixed date formats standardized  
✔ Inconsistent categorical values corrected  
✔ Invalid numerical values treated  
✔ Extreme outliers handled  
✔ Missing values analyzed and treated based on business logic  

Examples:

- Missing coupon codes treated as no coupon usage
- Payment failure missing values kept as structural missing values
- Customer history logically corrected
- Invalid page load/session values handled

---

#  Exploratory Data Analysis

The analysis focused on answering business questions instead of only creating charts.

## Customer Funnel Analysis

Identified where customers drop during:

Visited Site → Added to Cart → Checkout → Payment → Purchase


## Segment Analysis

Studied abandonment behaviour by:

- Device type
- City tier
- Month/seasonality
- Weekend vs weekday behaviour
- Cart value
- Website performance

---

#  Key Insights

### 1. Funnel Drop-off

The largest customer loss occurs before purchase completion, highlighting checkout optimization opportunities.

### 2. Device Impact

Different device types showed different abandonment patterns, helping prioritize UX improvements.

### 3. Seasonality Effect

Abandonment changes across months, indicating customer behaviour varies by shopping period.

### 4. Discounts Influence Conversion

Discount behaviour was analyzed as a potential lever for improving purchase completion.

---

#  Predictive Modelling

A Logistic Regression model was developed to predict whether a customer session would result in cart abandonment.

Model workflow:

- Feature engineering
- Dummy variable creation
- Train-test split
- Logistic regression training
- Model evaluation


Evaluation metrics:

- Accuracy
- Precision
- Recall
- Confusion Matrix

---

#  Business Recommendations

Based on the analysis:

### 1. Improve Checkout Experience

Optimize high drop-off stages to reduce customer friction.

### 2. Personalized Recovery Campaigns

Use predicted abandonment probability to target customers more effectively.

### 3. Optimize Marketing Strategy

Adjust campaigns based on customer segments and seasonal behaviour.

### 4. Continue Data Collection

Improve future models by capturing:
- Shipping cost
- Product availability
- Session-level marketing spend

---

#  Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Excel
- PowerPoint

---

#  Repository Structure

---

# Author

Vikhyat Singh

Data Analytics Portfolio Project
