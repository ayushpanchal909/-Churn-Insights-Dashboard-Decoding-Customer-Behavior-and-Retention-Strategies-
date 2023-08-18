### Customer-Churn-Dashboard

In the BI project focused on customer churn analysis, the journey began with importing the dataset and ensuring its cleanliness. Essential DAX measures and calculated columns were introduced to bolster the analytical capabilities. Establishing relationships between diverse tables, including active customer data, bank churn, credit card usage, customer information, exit patterns, and demographic aspects like gender and geography, was the next step.

The resultant dashboard offers insightful KPI cards representing various customer categories: total customers, active customers, credit card holders, non-credit card holders, exit customers, and retained customers. User-friendly filters enable data exploration based on year, month name, geography, and customer status categories (active, exit). A bar chart visually captures the total customers across different years and active categories, while a line chart illustrates exit customers' trends in the previous month, segmented by year and month name.

The dashboard further leverages a chart to showcase exit customer patterns based on credit card type and a bar chart depicting exit customers' distribution by category. This project empowers a comprehensive understanding of customer behaviors, helping identify trends and actionable insights for improved retention strategies and decision-making within the realm of customer analysis.

### Objective

>Detect and understand the key patterns and factors that contribute to customer churn, focusing on variables such as credit score, geography, age, tenure, balance, and product usage.

>Provide insights into customer segmentation based on various criteria like gender, geography, credit card ownership, and active/inactive membership. This will help in targeting specific customer groups for retention strategies.

>Develop predictive models that leverage the identified variables to predict customer churn. These models can be used to assess the likelihood of churn for individual customers, enabling proactive retention efforts.

>Analyze the performance of credit card holders versus non-holders, as well as active versus inactive members. Determine if having a credit card or being an active member influences churn rates.

>Examine the historical trends of churn over time, considering factors like the customer's date of joining (DOJ) and other variables. This analysis can help in understanding how churn rates have evolved and whether any specific periods exhibit higher churn

### Dashborad
<img width="800" alt="1" src="https://github.com/ayushpanchal909/Customer-Churn-Dashboard/assets/142341609/8ea126de-66b8-4d3a-b90c-838ec976135b">
<br>
<br>
<img width="257" alt="2" src="https://github.com/ayushpanchal909/Customer-Churn-Dashboard/assets/142341609/8ac20aae-5454-4745-8e31-5f0ad7e9eab9">
<br>
<br>
In 2019, the ActiveCategory accounted for 17.22% of the total customers. On average, the count of Total Customers was greater for Active Members (1,287.75) compared to Inactive Members (1,212.25). Notably, the divergence between Total Customers for Active and Inactive Members was most pronounced in 2019, with Active Members exceeding Inactive Members by 131.
<br>
<br>
<img width="400" alt="3" src="https://github.com/ayushpanchal909/Customer-Churn-Dashboard/assets/142341609/91ae5435-ea1f-4627-8a5e-8960f67b8e26">
<br>
There exists a positive correlation between Exit Customers and the count of Total Previous Month Exit Customers. In 2019, the Month Name "Nov" contributed 4.76% of the total Exit Customers. Regarding monthly averages, "Nov" stood out with the highest average Exit Customers (76.75), succeeded by "Dec" and "Sep." Conversely, "Feb" recorded the lowest average Exit Customers (14.50), signifying varying exit patterns across months.
<br>
<br>
<img width="276" alt="4" src="https://github.com/ayushpanchal909/Customer-Churn-Dashboard/assets/142341609/4e95966b-9da6-4032-b473-84d49e315613">
<br>
"Fair" credit type exhibited the highest Exit Customers at 685, significantly surpassing "Excellent" with a 435.16% difference. The range of Exit Customers across all five credit types spanned from 128 to 685. This data highlights the considerable variation in exit patterns based on customers' credit scores, where "Fair" credit type takes precedence while "Excellent" maintains the lowest exit count.
<br>
<br>
<img width="177" alt="5" src="https://github.com/ayushpanchal909/Customer-Churn-Dashboard/assets/142341609/78786083-2f03-4822-a93c-61dea7bcaa47">

<br>
Exit Customers among credit card holders totaled 1424, surpassing non-credit card holders at 613. This comparison signifies that credit card holders exhibit a notably higher tendency to exit, indicating potential differences in retention strategies and customer behaviors between the two groups.
<br>
<br>
Several insightful patterns emerge from the analysis. A positive correlation between Exit Customers and Total Previous Month Exit Customers underscores their interdependence. In 2019, Month Name "Nov" represented 4.76% of all Exit Customers. Notably, "Nov" exhibited the highest average Exit Customers (76.75), followed by "Dec" and "Sep," while "Feb" had the lowest average (14.50). Comparing Active and Inactive Members, the most divergence occurred in 2019, with Active Members surpassing Inactive by 131. Credit type "Fair" stood out with 685 Exit Customers, 435.16% more than "Excellent" with the lowest at 128. Across all 5 credit types, Exit Customers spanned from 128 to 685, revealing the credit-related churn trends.
