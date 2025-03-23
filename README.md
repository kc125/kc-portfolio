# Project 1 
## Impact of Human Activities on Marine Biodiversity in European region
Utilized Machine Learning regression techniques to analyze the impact of human-induced habitat degradation on marine biodiversity across the Mediterranean, Baltic, and Black Seas. The study revealed significant biodiversity decline, particularly in the Baltic and Black Seas, as indicated by the Shannon Diversity Index. Support Vector Regression (SVR) was used to predict future trends, showing the highest accuracy in the Baltic Sea. The Mediterranean Sea exhibited a relatively stable pattern but still showed signs of biodiversity loss. Findings emphasize the urgent need for conservation efforts, including sustainable fishing, pollution control, and marine protected areas. This research highlights the critical role of proactive measures in preserving marine ecosystems for future generations.


## Key Findings:
Negative Impact: Human activities are significantly degrading marine biodiversity in the Baltic, Black, and Mediterranean Seas.

Baltic Sea: Strong negative correlation between human activity and biodiversity, confirmed by the Support Vector Regression (SVR) model.

Black Sea: Slightly weaker but still harmful impact on biodiversity.

Mediterranean Sea: Data is limited, but biodiversity loss is evident.

Human-driven degradation is a major concern across all three regions.

Immediate conservation efforts are essential to prevent further loss.

<img width="898" alt="Screenshot 2025-03-23 at 19 30 46" src="https://github.com/user-attachments/assets/ed43e6bc-5b9e-446c-9eeb-cc554691104a" />

## Data Extraction & Selection:
Extracted multiple datasets from the Ocean Biodiversity Information System.
Focused on Mediterranean, Black, and Baltic Seas across the European region based on the requirement.
## Data Cleaning & Preparation
Removed unnecessary fields to enhance dataset quality.
Identified null values and applied imputation techniques due to strong data correlation.
## Data Analysis & Visualization
Utilized Pandas for data manipulation and preprocessing.
Implemented Matplotlib & Seaborn for effective plotting and trend visualization.
Created informative visual representations to simplify complex marine biodiversity data.
## Key Outcome
A clean, structured dataset enabling accurate insights into marine biodiversity trends across the selected regions.
Effective visualization tools for a better understanding of human impact on marine ecosystems.
![image](https://github.com/user-attachments/assets/331a85fd-7d63-4f0f-bf91-7ab87809d05c)

<img width="770" alt="Screenshot 2025-03-10 at 10 34 10" src="https://github.com/user-attachments/assets/e1bbf8c7-6fca-459d-878e-a42fea864ab6" />

<img width="737" alt="Screenshot 2025-03-10 at 10 35 02" src="https://github.com/user-attachments/assets/a7e39ae7-15b1-4afe-8a6a-203af1401fc8" />


# Project 2:
## Birmingham House Price Analysis & Prediction(1995-2019)

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
Linear regression provided a reasonable price estimate but had limitations.
Neural networks showed potential but required fine-tuning for better accuracy.
### Tech Stack Used:
* Python, Pandas, NumPy (Data Processing)
* Matplotlib, Seaborn (Data Visualization)
* Scikit-Learn (Regression Models)
* PyTorch (Deep Learning Models)

<img width="534" alt="Screenshot 2025-03-23 at 19 44 58" src="https://github.com/user-attachments/assets/afebefe7-426f-412f-b24a-99e4a5ed2ca1" />

<img width="471" alt="Screenshot 2025-03-23 at 19 45 41" src="https://github.com/user-attachments/assets/4b5716de-491c-449f-88c3-6c374b1d48ac" />

<img width="595" alt="Screenshot 2025-03-23 at 19 47 13" src="https://github.com/user-attachments/assets/b64e9f94-0cbf-43bb-8b8e-0238b9197543" />





