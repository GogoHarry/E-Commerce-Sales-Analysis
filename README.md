# Sterling E-Commerce Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Methodology & Data Source](#methodology-&-data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-(eda))
- [Key Results/Findings](#key-results/findings)
- [Recommendations](#recommendations)
- [Data Limitations](#data-limitations)
- [References](#references)
 
### Project Overview

This data analysis project aims to provide insights into the sales performance of an e-commerce company over the past year. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.

![ES Tableau Dashboard](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/56f06b27-0475-4e5a-a281-bcd1c006989f)


### Methodology & Data Source
To gain rich insights from Sterling's vast online sales data, we employed three key data analysis techniques:

- Customer Segmentation: First, we analyzed customers based on shared characteristics like demographics, purchase behavior, and preferred product categories. This allows us to understand distinct customer segments and tailor our analysis based on their specific needs.
- Market Basket Analysis: We then analyzed what items customers frequently purchase together.

- Time Series Analysis: Finally, we tracked sales and customer activity over time, uncovering seasonal trends and identifying periods of peak demand.

**Data Source:**  The primary dataset used for this analysis is Sterling's vast Online Sales Data.xlsx file, containing detailed information about each sale made by the company in the last year.
We meticulously cleaned and prepared the data in Microsoft Excel, resulting in a final dataset of 283,078 orders across 19 columns. We then leveraged Tableau's advanced visualization capabilities to delve deeper into customer behavior and uncover key insights.

### Tools

- Excel - Data Cleaning
  - [Download here](https://microsoft.com)
- Tableau - Data analysis and creating reports

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting

### Exploratory Data Analysis (EDA)

EDA involved exploring the sales data to answer key questions, such as:

- Customer Base:
  - Gender Breakdown: How are our customers distributed across genders? Is there a dominant demographic?
    ![image](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/8beaabc1-f22b-4e10-8ee0-b25135c57b86)
    

  - Revenue Generation: What is the total revenue generated in the last years?
    ![image](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/38ac3e7d-d774-43eb-ad02-589d74903f0b)


    
- Product Performance:
  - Top Sellers: Which products are ordered the most? Are there any unexpected best-sellers?
    ![image](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/7e4b07f8-8441-44d6-b119-638c8a317db9)


  - Revenue Stars: Which products generate the highest overall revenue? Do these align with the top sellers?
    ![image](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/e061d231-e382-4367-a1dc-9bae03953315)

    
  - Category Focus: How are orders and revenue distributed across different product categories? Are there any under-performing or over-performing categories?
    ![image](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/546a9b04-ae2b-42ac-8fc8-82138ef7520e)


- Payment Trends:
  - Preferred Payment Methods: Which payment methods do customers use most frequently? Is there a preferred method?
    ![image](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/8034e28d-e3ab-46bf-a844-b38fe1e39eb0)
    

  - Revenue by Payment Method: Which payment methods generate the highest revenue? Is there a disconnect between popularity and revenue?
    ![image](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/6ffee40c-d7c3-46bd-b21f-fa1928a14bbc)


- Revenue Trends:
  - Revenue Growth: How has the overall revenue evolved? Are there any seasonal patterns or significant fluctuations?
    ![image](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/b546da0f-8343-4f23-a28d-bfe747cacf20)
    

  - Local Presence: Which counties are the top 10 contributors to revenue and order quantity? Are there any emerging markets of interest?
    ![image](https://github.com/GogoHarry/Sterling-E-Commerce/assets/82883963/6130e9b9-c387-4464-a846-cdb2e0cbab42)
 


### Key Results/Findings
1. Gender distribution is almost equal: There's a near-even split between male and female customers (52% male, 48% female), aligning with the targeted market.

2. Mobiles & Tablets dominate sales and revenue: This category accounts for the most orders (29%) and the highest overall revenue (56%). Sterling should consider investigating profit margins for this category compared to others.

3. Cash on Delivery (COD) is the most popular, but Bankalfalah generates the most revenue: There's a disconnect between transaction volume and revenue. COD is the most used payment method (36% of orders) but contributes only 14% to revenue, whereas Bankalfalah (8% of orders) generates 20% of income. Further investigation is needed to understand this.

4. Revenue fluctuates with seasonal trends: There's significant fluctuation in revenue between months. Revenue surges from February to April (over 800% increase) and a substantive increase in December (500% increase), likely due to seasonal festivities. There's a drop in revenue in May.

5. Los Angeles is the top revenue generator, but other counties require attention: Los Angeles generates the highest revenue, indicating customer satisfaction. While Monroe and Jefferson also contribute significantly, counties like Winston, Polk, and Washington require targeted strategies to improve revenue.

### Recommendations

- Optimize product offerings based on performance and profitability: Prioritize categories like Mobiles & Tablets with high revenue despite lower order volume, while analyzing pricing and potential margin improvements for underperforming categories like School & Education/Books.

- Improve user experience and marketing for underutilized payment methods: Investigate user experience or technical issues hindering Cashatdoorstep and financesettlement usage, alongside targeted marketing campaigns to promote their benefits.

- Develop targeted strategies for emerging markets: Implement specific marketing and promotional campaigns focusing on counties like Winston, Polk, and Washington to capitalize on their revenue potential.

- Leverage seasonality trends for strategic promotions: Plan marketing and promotional activities around peak revenue periods like December festivities and February-April surge to maximize sales.

- Explore advanced data analysis techniques: Utilize predictive analytics and customer segmentation to personalize offerings, predict future behavior, and identify potential churn risk for targeted retention strategies.

By implementing these recommendations based on our data-driven insights, Sterling E-Commerce can optimize its product offerings, streamline operations, and enhance customer experience for continued growth and success.

### Data Limitations

While our analysis reveals valuable insights into Sterling's customers and operations, it's important to acknowledge some data limitations. First, this data represents only online sales for the last year, excluding potential insights from other channels like in-store purchases.

Additionally, the data lacks information on customer motivations and reasons behind their purchases. This limits our ability to fully understand the driving factors behind certain trends.

To address these limitations, we recommend expanding our data scope to include other sales channels and conducting customer surveys to gather deeper insights. This will refine our understanding and provide a more complete picture of Sterling's customer journey.

Despite these limitations, our analysis uncovers clear patterns and trends in customer behavior, spending habits, and product preferences. This provides a strong foundation for optimizing product offerings, streamlining operations, and improving the customer experience.

### References
1. Fundamentals of Data Visualization  by Claus O. Wilke
2. [Stack Overflow](https://stack.com)

