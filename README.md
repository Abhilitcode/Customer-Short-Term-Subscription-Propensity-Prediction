# Customer Short-Term Subscription Propensity Prediction

## Project Overview

This project aims to predict the likelihood (propensity) of customers subscribing to WrightVideo's premium membership within a short period. WrightVideo, a subscription video on demand company, launched their paid-prime membership in November 2019. While many customers subscribed to the premium service, the company seeks to identify potential customers who are likely to subscribe in the coming months. This prediction will help WrightVideo strategically target their marketing campaigns.

## Problem Statement

WrightVideo approached us to develop a model that scores each customer's inclination to subscribe to the premium membership in the next two months. The company intends to use this information to enhance their marketing strategies, ensuring they reach out to customers with the highest subscription propensity.

## Dataset Information

The dataset used in this project includes 10,500 customers, covering the period from January 2020 to December 2020. The data includes information on customer demographics, viewing habits, and subscription history.

**Dataset Characteristics:**

- **Type:** Multivariate
- **Subject Area:** Marketing, Customer Analytics
- **Associated Tasks:** Classification, Propensity Scoring
- **Feature Type:** Categorical, Integer, Float
- **Number of Instances:** 10,500
- **Number of Features:** Variable based on feature engineering

The dataset file used is **Customer_dataset_OTT_subscription.xlsx**.

## Project Objective

The objective of this project is to build a predictive model that accurately identifies customers who are likely to subscribe to WrightVideo's premium membership. This involves extensive data preparation, feature engineering, and model development to ensure the model performs well and provides actionable insights.

## Project Workflow

1. **Data Preparation:**
   - Clean the dataset to handle missing values and inconsistencies.
   - Generate a training dataset including both subscribers and non-subscribers.
   - Create a test dataset focusing on non-subscribers to predict their subscription likelihood.

2. **Exploratory Data Analysis (EDA):**
   - Analyze customer demographics, viewing habits, and other relevant features.
   - Visualize the relationships between features and subscription status.
   - Identify trends and patterns that can be leveraged for feature engineering.

3. **Feature Engineering:**
   - Create new features that capture customer behavior and subscription tendencies.
   - Select key features that drive customer propensity to subscribe.
   - Transform and encode categorical variables to be used in modeling.

4. **Model Development:**
   - Experiment with various classification algorithms, including Random Forest.
   - Evaluate model performance using accuracy, precision, recall, and F1-score.
   - Ensure the model generalizes well to unseen data and avoids overfitting.

5. **Model Evaluation:**
   - Assess model performance on the validation set.
   - Fine-tune the model to improve accuracy and predictive power.
   - Identify the most important features driving customer subscription propensity.

## Tools and Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost
- **Development Environment:** Jupyter Notebook

## Results

The Random Forest model achieved an accuracy of 79%, effectively identifying customers with a high propensity to subscribe to WrightVideo's premium membership. The model's performance was enhanced through extensive feature engineering and careful evaluation of key driving factors.

## Repository Structure

```plaintext
├── DataScience Hackathon
│   ├── Customer Short-Term Subscription Propensity Prediction.ipynb
│   ├── Customer_dataset_OTT_subscription.xlsx
│   ├── feature engineering.ipynb
│   └── forecasts.xlsx
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/abhilitcode/customer-short-term-subscription-propensity-prediction.git
   ```
2. Open the Jupyter Notebook files in your local environment to explore the code and results:
   ```bash
   jupyter notebook
   ```
