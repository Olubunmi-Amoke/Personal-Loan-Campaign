# Personal-Loan-Campaign

### Problem Statement
AllLife Bank is a US bank that has a growing customer base. The majority of these customers are liability customers (depositors) with varying sizes of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors).

A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio.

The goal of this project is to build a model that will help the marketing department to identify the potential customers who have a higher probability of purchasing the loan.

**Objective**

To predict whether a liability customer will buy personal loans, to understand which customer attributes are most significant in driving purchases, and identify which segment of customers to target more.

### Actionable Insights and Business Recommendations
The Decision Tree with post-pruning showed the highest accuracy, recall, precision, and F1 score on the test set. Thus, the final recommendation is to deploy the **post-pruned decision** tree model for predicting customers who are more likely to purchase loans.

From the analysis of features like age and education, customers with higher education levels tend to show a slightly higher interest in purchasing loans. I found that higher education levels correlate with a higher likelihood of purchasing loans. I therefore recommend that **targeting educated customers** with loan offers might result in better conversion rates.

Given that certain customer demographics (like those with higher education) are more likely to take loans, it may be valuable for AllLife Bank to run more **targeted marketing campaigns** for these groups.
