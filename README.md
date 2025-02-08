# Aerofit-Customer-Demographics

AeroFit is a fitness company that sells treadmills to health-conscious individuals. They have three major products (treadmills): 
-KP281 valued at 1500$ 
-KP481 valued at 1750$ 
-KP781 valued at 2500$. 

Customer data from the last three months was analyzed for customer profiling, which will help the market research team better understand customer needs and preferences when selecting AeroFit treadmills, leading to an improved recommendation system. Categorization of the client is done based on their gender, age, education, marital status, fitness level and income. Furthermore, their expectations on how many days they will use the treadmill and how many miles they are planning to walk/run is also recorded.

The correlation matrix represents what impact certain factors have on the selection of the final product. As can be seen from the following figure that age greatly impacts income meaning that with age income also increases. Similarly, education also has significant correlation with income. And most customers with high income (85k to 105k usd per annum) prefer KP781. High usage of the treadmill is also directly related to higher fitness, income and miles covered each week.

![download (14)](https://github.com/user-attachments/assets/e3fd802d-9018-4c91-9712-83d34a8d7b14)

## Methodology
- **Data Cleaning and Exploration**
  - The shape of the dataframe is checked i.e. the number of rows and columns (180x9).
  - Datatypes for each column is checked to be consistent.
  - Data set does not have any duplicate values.
  - There are no missing values in each column.
  - The statistical summary of numerical and categorical data is analyzed to rule out any discrepancy in data.
  - Unique values for both numerical and categorical data and counts for the latter are checked to make sure there is no incorrect data.
  - Bins were used during data analysis but were not made a part of the dataframe.
- **Outlier Analysis**
  - Boxplots, Histograms and Tukeys IQR is used to identify the outliers in the dataframe for the numerical data.

  ![AudienceUnderstanding1](https://github.com/user-attachments/assets/d6d29f22-02a8-4e4d-926d-9b54e7b332ac)

  ![download (6)](https://github.com/user-attachments/assets/ba72b6c2-8012-4c3d-939d-73270adfb445)


## Key Insights

- Most of the customer-base of AeroFit prefers KP281 with KP481 having second highest demand leaving KP781 behind.
- 58% of the buyers are male and 59% of the buyer are partenered.
- Majority of the clientele 60.4% and 26.7% approx. is in their twenties and thirties respectively.
- AeroFit customers have 16, 14 and 18 years of education in order of their counts. With 47% having 16 years of education and 30% having 14 years of education. In short most of the clients are highly educated.
- Annual Income for majority of AeroFit customers ranges from 30,000$ to 70,000$. Hence medium income earners make up 74% of the clientbase.

## Actionable Recommendations
