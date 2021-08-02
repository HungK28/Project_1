# Paycheck Protection Program (PPP) in California

![image](https://user-images.githubusercontent.com/85582682/127910899-ce4e3f31-3918-4587-9ebd-f1af30a6a789.png)  

The Paycheck Protection Program (PPP) is an SBA-backed loan program that helped businesses keep their workforce employed during the COVID-19 crisis.  The PPP was implemented in April 2020 to provide relief to small businesses that were impacted by the coronavirus by providing 2.5 months of a company's average payroll that would be 100% forgivable if funds were used to retain employees. In January 2021, a second round of relief (PPS) was offered with stricter criteria including proof of a
25% revenue reduction in at least one quarter of 2020 compared to the prior year.

![image](https://user-images.githubusercontent.com/85582682/127912511-68f90680-9453-437d-99ea-44a5634b4224.png)


Since the loans were funded through the SBA, the loan information has been made publicly available. Our data set includes the all the PPP loans that were funded in California for both PPP and PPS. In this project, we tried to analyze the publicly available PPP loan-disbursement data for California and get a birds-eye view of the program. The analysis sheds light on the small businesses in California that got access to these disbursed loans to counteract the economic impact of the pandemic.  To be specific, we tried to answer the following questions:

Total Amount of Loans ($B): $103B. Total Loan Count: 1.3 Million. The following table, bar diagram, and the pie chart provide more information on the distribution of the total loans by the two types: PPP and PPS.
    
    
    
    ![image](https://user-images.githubusercontent.com/85582682/127918069-016cd9a2-6397-4d6f-a15a-8ad8beeb0598.png)

    
    ![image](https://user-images.githubusercontent.com/85582682/127917816-fc1d5038-b000-43e1-9027-ded4c354c0d5.png) ![image](https://user-images.githubusercontent.com/85582682/127917941-3c2cdb18-94f0-4a10-8e43-d7cb9376c53e.png)





## 1. What is the total count and total amount of loans disbursed? 
    
    
    





## 2.	What is the industry-wide distribution of the loans? Which industries got more loans?

The dataset included NAICS code for each small business that got a loan. The North American Industry Classification System or NAICS is a classification of business establishments by type of economic activity (process of production). It is used by government and business in Canada, Mexico, and the United States of America. From the NAICS codes we could come up with the industry-wide loan distribution. Service industries got more loans compared to manufacturing.

![image](https://user-images.githubusercontent.com/85582682/127909938-75e675ba-838d-43bc-8839-adff0f1b8ea8.png)

![image](https://user-images.githubusercontent.com/85582682/127914191-0b5f4e7a-3d56-4a81-b8d1-62953a358d36.png) ![image](https://user-images.githubusercontent.com/85582682/127914969-05d6bc1a-e585-495b-8962-7ec561ba0849.png)





## 3.	Which banks provided most of the loans?

The following bar diagram shows that the traditional big banks were the biggest lenders in this case too.

![image](https://user-images.githubusercontent.com/85582682/127910562-5a01326c-2168-415c-b3a1-cf880c8fc575.png)

## 4.	What is the relationship between size of the loan and number of employees on the payroll?

Positive strong correlation (=0.72) between size of the loan and number of employees on the payroll. This can suggest that the size of the loan is determined on the employee count.


![image](https://user-images.githubusercontent.com/85582682/127915303-3b7e2aa3-6d6c-4d10-9b37-8a3e8a4e93c7.png)


## 5.	What is the geographical distribution of the loans made? Which county got the most loan?
    Analysis Breakdown
    
● Grouped data set by counties

● Broke out loans by PPP and PPS

● Compared total loan amounts by counties 

● Compared total loan amounts per the counties population

Results

● Total loan amounts for both PPP and PPS seemed consistent with population size.

● Loan amounts per capita showed more concentration in counties surrounding the bay area.

● More rural counties seemed to have lower loan amounts per capita.

![image](https://user-images.githubusercontent.com/85582682/127912227-61c454a4-dbf3-4d93-a51e-1be8700a0e09.png)  ![image](https://user-images.githubusercontent.com/85582682/127912348-78f0b6cc-6bc1-4ab6-a028-f33cb218af7a.png)




## 6.	Did business-owners of a particular race/ethnicity get more loans? If yes, is it statistically significant?

We used a Student’s T-test to answer the questions. Please see the folder Alex for the codes. The results of the test are as follows.

● Multi-group is not statistically different from any group(p>0.05) except white.

● White group is statistically different from all groups(p<0.05).

● White-owned small businesses benefited the most from PPP.

![image](https://user-images.githubusercontent.com/85582682/127913227-4ad537ef-4af7-4fc0-b3f2-b3cd2c24fee6.png)


![image](https://user-images.githubusercontent.com/85582682/127915126-205c1b92-c219-4ce9-9685-3f7404c66774.png)

## Summary:

● For 74% of the small business, the first round of government backed loans was enough to keep the business from having a 25% reduction in revenue in 2020 compared to prior year.

● Bank of America, JP Morgan Chase and Wells Fargo had the most presence in facilitating loans in California measured both by dollar value and loan counts.

● The data suggests that the number of employees does influence the loan amount.

● White-owned small businesses benefited the most in comparison with other ethnicities.

● The service industry needed more loans compared to manufacturing. The top 5 service industries accounted for more than 53% of the total loan counts.

● Counties clustered around the Bay area received the most loans per capita for both PPP and PPS

