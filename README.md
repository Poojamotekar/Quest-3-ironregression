# Quest-3 IronRegression
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/29e66c59-59be-4e88-b262-d02c4f56fd28)
# Problem Statement
dataset of house sale prices for King County, including Seattle, spanning one year from May 2014 to May 2015..
This project encompasses various computational tasks such as data loading, visualization, calculating returns, and portfolio analysis, tailored to the real estate domain..
Our primary focus is to understand which features most significantly impact the house price.
# Key Questions
What are the key factors that influence house prices in King County?
How does the age of a house affect its current market price?
What is the impact of location-related features (latitude, longitude) on house prices?
How do features like square footage (living area, lot size) and house grade affect pricing?
How do the findings from the predictive models compare with traditional valuation methods
# Methodology ![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/5d314bd4-40e1-416e-a9be-ad4686a97d95)
Obtain and Analyse Data
Investigate Features and gain insights
Build Prediction Model
The Data used for this proejct consists of around 21613 prices for house sales which occurred between May 2014 and 2015. 
# Checking our target distribution
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/0cb4b266-9951-4c14-8e89-dece8984780a)
Prices are skewed to the right, meaning that there are outliers in the higher price range. 
These outliers range from $2-8M, causing our mean ($540k) to be $100,000 more than our median ($450k). 50% of house sale prices are between $322K and $645K.
# Square footage vs. Price of Houses:
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/c017abc9-7366-4903-9a7e-ce8d2089444d)
Square footage (sqft) shows a positive correlation with price; for each unit increase sqft, there is also an increase in the value of the house. 
Majority of the houses are under 4,000sqft and under $2M.

# How does Grade affect House Sale Price?![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/8b96bdee-bf84-4392-b603-a142b790b0fd)


![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/11892df6-1afb-427c-8541-aa324c0bee89) ![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/73366670-f9df-4326-9631-c73d9851c916)
Grade : shows a positive correlation with price; houses with a higher grade tends to cost more.
 Houses with grade equal to or less than 6 do not have many outliers.
These houses have simple construction and design so it is difficult for them to be priced higher.
# Year Built




