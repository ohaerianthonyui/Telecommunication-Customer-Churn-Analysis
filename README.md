# Telecommunication-Customer-Churn-Analysis
Customer Churn Analysis with Python


# Telecommunication Customer Churn Analysis


We have analyzed the churn dataset of a European Telecom Company, which includes cleaned customer activity data along with a churn label indicating whether a customer has canceled their subscription. Through this exploration and analysis, we aim to identify the key factors driving customer churn and develop strategies and recommendations to improve customer retention.

## Business Understanding of Telecommunicaion Customer Churn
The Telecom industry's customer churn refers to the loss of subscribers who cancel their services. 
Understanding and analyzing churn is crucial for telecom companies, as retaining customers is generally more cost-effective than acquiring new ones.
A high churn rate can lead to significant revenue loss, reduced customer lifetime value, and increased acquisition costs. Factors like service quality, pricing, customer support, and competitor offers play a major role in customer decisions to churn. 
Analyzing churn data helps uncover the key drivers and enables companies to implement strategies to improve customer satisfaction and retention.



#### Project Objective
The main goal of our project is to develop an understanding of the cause of customer churn which assist telecom operators to predict customers who are most likely subject to churn, and what to do to retain the most valuable customer.

### Tools and Methodology
The project was carried out using Python, and an exploratory data analysis was done on the dataset.  


The following questions were asked to extract insights from the dataset;

(1)  What is the distribution of churn among customers?
(2)  How does churn correlate with the number of customer service calls?
(3)  Is there a relationship between the total minutes of usage (day, evening, night, international) and churn?
(4)  What is the average number of calls in the day, evening, and night for churned vs non-churned customers?
(5)` What is the distribution of the "account length" for customers who churn vs those who don't?
(6)``What is the correlation between numerical features (e.g., total minutes, charges) and churn?
Selection deleted

(7)` How do churn rates differ based on area code?
(8)` Is there a difference in the total charges (day, evening, night, international) between churned and non-churned customers?
(9)  Are there significant differences in churn based on the "number of voicemail messages?


## Findings

#### Churn Rate:

14% of the customers have churned, indicating that a notable portion of the customer base has discontinued service.
Customer Service Calls and Churn:

Customers who churned tended to make more customer service calls compared to those who remained. This suggests that increased customer service interaction might be indicative of dissatisfaction or issues that could lead to churn.
Usage Patterns and Charges:

Churned customers exhibited higher overall call minutes, particularly in daytime usage, with higher total day charges and total day minutes. This suggests that customers who use the service more (during the day) tend to churn more frequently, possibly due to high service costs or dissatisfaction with the service.

Interestingly, international calls did not follow the same trend, with churned customers showing lower international charges compared to their non-churned counterparts.

#### Account Length:

Non-churned customers, on average, had a longer account length, indicating that customers who have been with the service for a longer time tend to stay longer, while newer customers may be more likely to churn.

#### Correlation with Churn:

Moderate positive correlations were found between churn and the following features:

Customer service calls: Higher interaction with customer service correlates with churn.

Total day minutes and total day charge: Churned customers tend to use more daytime minutes and incur higher charges.

Weak positive correlations:
Total evening minutes, total international charge, and total night minutes show weak correlations with churn, suggesting that while there is some relationship, it is not as strong.
Weak negative correlations:
International calls and number of voicemail messages were weakly negatively correlated with churn, indicating that customers who make more international calls or receive more voicemail messages may be less likely to churn, though this effect is minimal.

No meaningful correlations:

Features such as area code, total evening calls, and account length showed either no correlation or very weak correlations with churn.

#### Area Code and Churn:

The 415 area code represented the majority of customers and also had the highest churn rate, while the 408 area code exhibited the lowest churn rate. This could suggest regional factors influencing churn, such as network quality or pricing structures.
Significant Differences in Charges:

There is a statistically significant difference between the charges for churned and non-churned customers. Churned customers tend to have higher day and international charges, which may indicate that high service costs or billing issues contribute to their decision to churn. Conversely, night charges showed no significant difference.
Voicemail Messages and Churn:

Non-churned customers had a higher number of voicemail messages compared to churned customers, suggesting that churned customers might be less engaged or less satisfied with the service.

#### Conclusion:
The analysis reveals several key insights into customer churn. Customers who churned tend to have higher daytime usage and charges, suggesting that high service costs could be a significant factor influencing their decision to leave. Additionally, higher customer service interactions correlate with churn, indicating that unresolved issues may play a role in customer dissatisfaction. Interestingly, non-churned customers tend to have a longer account length and higher engagement with the service, including voicemail usage.

Geographic factors, such as area codes, also seem to influence churn rates, with the 415 area code experiencing the highest churn rate. These findings suggest that there may be regional or network-related factors impacting customer retention.

#### Recommendations:
Focus on High-Usage Customers:

Since customers with higher day and international charges are more likely to churn, the company should consider offering better pricing plans for heavy users. This could include daytime or international calling plans that are more cost-effective or flexible to reduce high charges.
Enhance Customer Service Interaction:

The moderate correlation between customer service calls and churn indicates that customers who frequently contact customer service may be facing unresolved issues. The company should improve its customer service experience, ensuring that concerns are addressed promptly to prevent churn. A proactive approach, such as offering personalized support for high-usage customers, could help reduce churn.
Increase Customer Engagement:

Since non-churned customers have a higher number of voicemail messages, the company should explore ways to engage customers more effectively, such as by encouraging the use of voicemail features or offering incentives for continued service usage.
Investigate Regional Factors:

Given the differences in churn by area code, the company should investigate whether there are specific network, service quality, or pricing issues that disproportionately affect customers in the 415 area code. Targeted interventions in these regions could help reduce churn.
Offer Long-Term Incentives:

Customers with longer account lengths are less likely to churn. The company should introduce loyalty programs or long-term discounts to reward customers who stay with the service for extended periods, thus incentivizing them to remain with the company.
Address Billing Concerns:

Since high charges are correlated with churn, ensuring clear billing practices and offering flexible payment options could mitigate churn caused by billing concerns.
By addressing these areas, the company can better target at-risk customers, improve satisfaction, and reduce overall churn.





