Project Title:
"Birmingham House Price Analysis & Prediction (1995-2019)"
Project Description:
This project explores 25 years of house price data in Birmingham, analyzing trends and building predictive models. Using Python, Pandas, Matplotlib, Scikit-Learn, and PyTorch, key insights are extracted to understand the real estate market.
Key Features:
Data Preprocessing & Cleaning:
* Removed unnecessary columns and missing values.
* Encoded categorical variables (new build, estate type, transaction category).
* Extracted numerical postcode values.
Time-Series Analysis & Visualization:
* Converted deed date into days since 1st Jan 1995.
* Created bar charts for sales distribution by property type, new build, estate type, and transaction category.
* Analyzed yearly sales trends of detached houses using scatter plots & regression lines.
Price Trends & Normalization:
* Computed mean detached house prices per year.
* Fitted a linear regression model to observe long-term trends.
* Normalized price data based on trend analysis.
Top 10 Expensive Postcodes Analysis:
* Identified postcodes with highest normalised detached house prices.
Machine Learning Models for Price Prediction:
* Sklearn Regression Model: Used days, postcode, new build status, estate type, and transaction category to predict prices.
* PyTorch Linear Regression: Built a simple model with manual normalization for training/testing.
* Multi-Layer Perceptron (MLP) in PyTorch: Implemented a neural network to improve predictions.
Results & Insights:
Trends indicate significant price fluctuations over the years.
Linear regression provided a reasonable price estimate but had limitations. Neural networks showed potential but required fine-tuning for better accuracy.
Tech Stack Used:
* Python, Pandas, NumPy (Data Processing)
* Matplotlib, Seaborn (Data Visualization)
* Scikit-Learn (Regression Models)
* PyTorch (Deep Learning Models)
This project provides valuable market insights while leveraging ML models for house price prediction. 
