# US-Home-Prices-Influencing-Factors

## **Objective:**

Find publicly available data for key factors that influence US home prices nationally. Then, build a data science model that explains how these factors impacted home prices over the last 20 years.

The project aims to build a data science model to predict U.S. home prices based on key economic factors over the last 20 years.

## **Steps**

1. **Data Collection:**

Utilized the S&P Case-Schiller Home Price Index as a proxy for home prices, sourced from the Federal Reserve Economic Data (FRED) website.

2. **Key Factors:**

Gathered publicly available data on factors influencing home prices nationally, including Per Capita GDP, Consumer Price Index (CPI), Construction Material Costs, Median Income, Subsidies, and Population Demographics, etc.

3. **Data Cleaning and Processing:**

Cleaned and processed the data, addressing missing values, converting date formats, and handling outliers.

4. **Exploratory Data Analysis (EDA):**

Conducted EDA to understand the distribution of variables, identify correlations, and visualize trends over time.

5. **Model Selection:**

Explored various regression models, including Linear Regression, ElasticNet, Random Forest, Gradient Boosting, Support Vector Regression (SVR), and XGBoost.

6. **Model Training and Evaluation:**

Trained each model using a subset of the data, evaluated performance using metrics such as Mean Squared Error (MSE) and R-squared.

7. **Feature Importance:**

Analyzed feature importance for models like Random Forest, XGBoost, and Gradient Boosting to understand the factors influencing home prices.

8. **Model Comparison:**

Compare the performance of different models based on metrics such as Mean Squared Error (MSE) and R-squared.

Select the best-performing model that provides accurate predictions and insights into the factors influencing home prices over the last 20 years.

9. **Visualization:**

Create visualizations to illustrate the relationships between actual and predicted home prices for each model.

Visualize the importance of different features or coefficients in influencing home prices.

![Screenshot 2024-08-02 050246](https://github.com/user-attachments/assets/46ac7634-a126-486e-b86e-316cfead9edb)

![download](https://github.com/user-attachments/assets/9b575ec3-6141-4287-b03e-b02d4a51bdd5)


10. **Conclusion:**

Identified strong contender for the best model, considering their low MSE and high R-squared values.

Draw conclusions about the key factors that have historically influenced US home prices.

11. **Overall Implication:**

The project contributes to understanding the key factors influencing U.S. home prices over the last 20 years and provides a foundation for building robust predictive models in the real estate domain.

## Results

The project involves understanding and predicting patterns rather than just describing historical trends or providing actionable recommendations.

![Screenshot 2024-08-02 045452](https://github.com/user-attachments/assets/256af323-b7fd-4259-97be-909761aa7d50)

![Screenshot 2024-08-02 045135](https://github.com/user-attachments/assets/e23ae79d-c61f-4cb2-9482-7673e6b4f01b)



# Data Availability

**The following variables are chosen for the study-**

1. Unemployment Rate
2. Employment Rate
3. Per Capita GDP
4. Real Median Household Income
5. Construction Prices
6. CPI
7. Houses
8. Interest Rates
9. Number of new houses supplied
10. Working Population
11. Urban Population
12. Percentage of population above 65
13. Housing subsidies
14. Number of Households

As a proxy to the home prices, S&P CASE-SHILLER Index is used.

Most of the data is downloaded from [https://fred.stlouisfed.org/].

**Following sources were used to gather data:**

CASE-SCHILLER Home Price Index - https://fred.stlouisfed.org/series/CSUSHPISA

Interest rates - https://fred.stlouisfed.org/series/FEDFUNDS

Unemployment rate - https://fred.stlouisfed.org/series/UNRATE

Working Population - https://fred.stlouisfed.org/series/LFWA64TTUSM647S

Employment rate - https://fred.stlouisfed.org/series/LREM64TTUSM156S

Consumer price index (CPI) - https://fred.stlouisfed.org/series/CPIAUCSL

Real Median Household Income - https://fred.stlouisfed.org/series/MEHOINUSA672N

Per Capita GDP - https://fred.stlouisfed.org/series/A939RX0Q048SBEA

Construction price index - https://fred.stlouisfed.org/series/WPUSI012011

percent urban population - https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS?end=2021&locations=US&start=2001

Houses - https://fred.stlouisfed.org/series/MSACSR#0

Housing Subsidies (Federal) - https://fred.stlouisfed.org/series/L312051A027NBEA

Total households - https://fred.stlouisfed.org/series/TTLHH


**Article referred** -

https://www.investopedia.com/articles/mortgages-real-estate/10/understanding-case-shiller-index.asp
