# Food-Business-Data-Analysis

## 1) Goals of the project 🎯
### Business Goal: 
Increase the business profits by targeting features that help increase shopping cart value of an individual.
### Questions to answer:
- Which model is the best to explain the whole picture of the business?
- Determine which elements contribute to a customer’s cart value significantly?
- How important are those features? Statistical evidence?
- Which insights and solutions can be drawn from the analysis?

## 2) Data sources 🗂️
Name: Marketing Analytics
Link: https://www.kaggle.com/datasets/jackdaoud/marketing-data/data
The data set ifood_df.csv consists of 2205 customers of XYZ company with data on:
- Customer profiles
- Product preferences
- Campaign successes/failures
- Channel performance

## 3) Data overview 🔍
The datasets has 2205 rows and 39 columns with usability score of 9.41
| **Feature**             | **Description**                                                                 |
|-------------------------|---------------------------------------------------------------------------------|
| AcceptedCmp1            | 1 if customer accepted the offer in the 1st campaign, 0 otherwise               |
| AcceptedCmp2            | 1 if customer accepted the offer in the 2nd campaign, 0 otherwise               |
| AcceptedCmp3            | 1 if customer accepted the offer in the 3rd campaign, 0 otherwise               |
| AcceptedCmp4            | 1 if customer accepted the offer in the 4th campaign, 0 otherwise               |
| AcceptedCmp5            | 1 if customer accepted the offer in the 5th campaign, 0 otherwise               |
| Response (target)       | 1 if customer accepted the offer in the last campaign, 0 otherwise              |
| Complain                | 1 if customer complained in the last 2 years                                    |
| Customer_Days              | Date of customer's enrollment with the company                                  |
| education_2n Cycle      |  1 if Yes, 0 then No                                                                               |
| education_Basic         | 1 if Yes, 0 then No                                                                                |
| education_Graduation    | 1 if Yes, 0 then No                                                                                |
| education_Master        |  1 if Yes, 0 then No                                                                               |
| education_PhD           |  1 if Yes, 0 then No                                                                               |
| marital_Divorced        | 1 if Yes, 0 then No                                                                                |
| marital_Married         | 1 if Yes, 0 then No                                                                                |
| marital_Single          |  1 if Yes, 0 then No                                                                               |
| marital_Together        | 1 if Yes, 0 then No                                                                                |
| marital_Widow           | 1 if Yes, 0 then No                                                                                 |
| Kidhome                 | Number of small children in customer's household                                |
| Teenhome                | Number of teenagers in customer's household                                     |
| Income                  | Customer's yearly household income                                              |
| MntFishProducts         | Amount spent on fish products in the last 2 years                               |
| MntMeatProducts         | Amount spent on meat products in the last 2 years                               |
| MntFruits               | Amount spent on fruits in the last 2 years                                      |
| MntSweetProducts        | Amount spent on sweet products in the last 2 years                              |
| MntWines                | Amount spent on wines in the last 2 years                                       |
| MntGoldProds            | Amount spent on gold products in the last 2 years                               |
| MntRegularProds                 | Amount spent on regular products in the last 2 years                                         |
| NumDealsPurchases       | Number of purchases made with discount                                          |
| NumCatalogPurchases     | Number of purchases made using catalogue                                        |
| NumStorePurchases       | Number of purchases made directly in stores                                     |
| NumWebPurchases         | Number of purchases made through company's website                              |
| NumWebVisitsMonth       | Number of visits to company's website in the last month                         |
| Recency                 | Number of days since the last purchase                                          |
| AcceptedCmpOverall                 | Total offers customer accepted
          |
| Z_CostContact                 | Value of 3
          |
| Z_Revenue	                 | Value of 11
          

## 4) Analytical tools used in the project 📚
- Language: Python
- Analysis: pandas, numpy
- Visualization: matplotlib, seaborn, Power BI
- Modeling: statsmodels, scikit-learn
- Browser-based coding environment: Google Colab/Jupyter Notebook

## 5) Model 📊
- Model performance comparision
- Optimal Model: Random Forest (RMSE: 192.04, R²: 0.8909)

## 6) Hypotheses ✏️
Hypothesis 1: Customer's income is equivalent to the total cart value
Hypothesis 2: Customer tends to make more purchases by using business catalogue
Hypothesis 3: Customers love to pay more when going shopping at brick-and-mortar store
Hypothesis 4: Marketing Campaign 5 proven to be successful
Hypothesis 5: Business benefits the most from old customer
Hypothesis 6: A family with teen and kid comparison
Hypothesis 7: Recency shapes customer purchasing behaviors
Hypothesis 8: People visiting company website in last month, tends to pay less the following month

## 7) Summary and Suggestions 💡

With the income segmentation, catalogue engagement, and next Campaign optimization, the business can achieve the profit as high as the previous campaign 5 or even higher thanks to other considered factors found in the analysis.

The outcome can be seen to surpass more than 90% compared to previous campaign from 4 or earlier.

