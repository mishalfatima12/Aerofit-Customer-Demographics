# Aerofit-Customer-Demographics

AeroFit is a fitness company that sells treadmills to health-conscious individuals. They have three major products (treadmills): 
-KP281 valued at $1500 
-KP481 valued at $1750
-KP781 valued at $2500

Customer data from the last three months was analyzed for customer profiling, which will help the market research team better understand customer needs and preferences when selecting AeroFit treadmills, leading to an improved recommendation system. Categorization of the clients is done based on their gender, age, education, marital status, fitness level and income. Furthermore, their expectations regarding how many days they will use the treadmill and how many miles they are planning to walk/run are also recorded.

The correlation matrix represents the impact certain factors have on the selection of the final product. As can be seen from the following figure, age greatly impacts income, meaning that as age increases, so does income. Similarly, education also has significant correlation with income. And most customers with high income (85k to 105k USD per annum) prefer KP781. High usage of the treadmill is also directly related to higher fitness, income and miles covered each week.

![download (14)](https://github.com/user-attachments/assets/e3fd802d-9018-4c91-9712-83d34a8d7b14)

## Methodology
- **Data Cleaning and Exploration**
  - The shape of the dataframe is checked i.e. the number of rows and columns (180x9).
  - Datatype for each column is checked to be consistent.
  - Data set does not have any duplicate values.
  - There are no missing values in any of the columns.
  - The statistical summary of numerical and categorical data is analyzed to rule out any discrepancy in data.
  - Unique values for both numerical and categorical data and counts for the latter are checked to make sure there is no incorrect data.
  - Bins were used during data analysis but were not made part of the dataframe.
- **Outlier Analysis**
  - Boxplots and Tukey's IQR are used to identify the outliers in the dataframe for the numerical data.

  ![download (6)](https://github.com/user-attachments/assets/ba72b6c2-8012-4c3d-939d-73270adfb445)


## Key Insights
### Customer Demographics
- Most of the customer-base of AeroFit prefers KP281 with KP481 having second highest demand leaving KP781 behind.
- 58% of the buyers are male and 59% of the buyer are partnered.
- Majority of the clientele, approximately 60.4% and 26.7%, is in their twenties and thirties, respectively.
- AeroFit customers have 16, 14 and 18 years of education in order of their counts. With 47% having 16 years of education and 30% having 14 years of education. In short, most of the clients are highly educated.
- Annual Income for majority of AeroFit customers ranges from $30,000 to $70,000. Hence medium-income earners make up 74% of the client base.

![AudienceUnderstanding1](https://github.com/user-attachments/assets/d6d29f22-02a8-4e4d-926d-9b54e7b332ac)

![AudienceUnderstanding](https://github.com/user-attachments/assets/3f7339db-606d-4249-b557-5bb89ab34eb9)

### Purchase Trends For AeroFit Products
- Purchase trend for KP281 and KP481 is approx. equal amongst both genders. There is equal probability that the buyer of these two products could either be male or female. However, most buyers (approx. 82%) of KP781 are men.

![download (7)](https://github.com/user-attachments/assets/2dce8a0a-666a-44d4-8d58-368de73c82ad)

- Majority of the buyers for each product are between ages 20-39 years old. However, it is worth noting that 25-30 year olds prefer KP781 over KP481 and 30-35 year olds prefer KP481 over the other products.

![download (9)](https://github.com/user-attachments/assets/da320f50-c0ae-424d-936b-a29503771c84)

- Customers with high income purchase KP781 whereas most medium income individuals prefer both KP281 and KP481. Amongst the 13% customers with high income status, 100% have purchased the KP781.

![download (13)](https://github.com/user-attachments/assets/6a29ab72-2ba2-4ad8-973d-d108f71a82d4)


## Actionable Recommendations
It can be concluded that education, fitness level and income greatly influence the purchase of the customer. To improve the recommendation system these factors must be taken into account.
- As middle class makes the biggest clientele, they should be educated about how KP781 has users with higher fitness levels.
- People with higher education and higher income are most likely to choose KP781.
- Since majority of female clientele prefers KP281 and KP481, the KP481 should be recommended as a starting point.
- People in 20s and 30s are the biggest demographic and since age is directly correlated to income, they are more likely to purchase KP281 and KP481.
- People who seem to be in good shape are more inclined to buy KP781.
