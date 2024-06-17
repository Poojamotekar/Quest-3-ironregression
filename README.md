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
Grade : shows a positive correlation with price; houses with a higher grade tends to cost more.
 Houses with grade equal to or less than 6 do not have many outliers.
These houses have simple construction and design so it is difficult for them to be priced higher.
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/6579e253-649e-4d4b-9b80-6e0c0fa762fa)
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/b29849af-ab5f-479e-81fa-ff848d29f68a)


# Year Built
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/2269321c-fd64-4b86-8aac-4fffa1d6f71e) ![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/c1ed18a4-d4b0-4f23-8148-04988549683d)
You can see that generally there has been an increase in the number of houses built over time, followed by around 3 to 5 years of decrease but there are notable declines in the 1930s and 1970s.
The decrease in the number of houses constructed during the 1930sis probably connected to the Great Depression that commenced with the 1929 Wall Street Crash.
In the 1970s, the presence of the Cold War and Vietnam War, as well as an oil crisis in 1973, could have all played a part in the decline of house construction during that era.
# Waterfront
The boxplot shows that the houses with waterfront attract more price than the houses without a waterfront.

![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/9f008720-0442-4f5e-8227-e94fe1cc0b1e)
# Latitude and Longitude![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/1f9392ab-d4b7-44b3-ad0c-d4a532f4ad70)
Upon observation, it becomes evident that costly homes are mostly situated near bodies of water, while less expensive ones are more inland
Additionally, it is notable that the pricier homes tend to be located further north compared to the most affordable ones. Thus we can add ‘latitude’ in our predictor variables candidates’ set.

![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/ce8d8a59-7f98-411e-83c6-0e39892cbc0a)
# Bedrooms and Bathrooms![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/6ec94d9d-ee39-4142-8233-4f2c4d48ba38)
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/410e9de7-7515-4111-9a94-ee3bd7dc2163) ![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/008920d8-9ad8-416c-b150-f1656eec6dae)
# Linear model, Ridge Regression, Lasso Regression![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/027dccc9-af37-479c-87b0-5803b6402608)
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/91a156b0-7878-4f38-ad0c-65338b92e1c9) ![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/6ab340b8-63a0-462d-94b1-c941eec2480d)
Metrics:
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/1e247ef5-75ec-4c16-a598-c05f0cce62cc)
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/92dc9586-3073-4321-96f6-205f4de22adf)
![image](https://github.com/Poojamotekar/Quest-3-ironregression/assets/66488693/00fe2de5-a94b-4f64-90cb-0d04e3949015)



















