# Perform-multiple-linear-regression
In this project, we analysed a small business's historical marketing promotion data. Each row corresponded to an independent marketing promotion where the business used TV, social media, radio, and influencer promotions to increase sales.  To expand this analysis to include other variables that could help them target their marketing efforts.



**When TV and Radio are used to predict Sales, the model coefficients are:**

- 𝛽0=218.5261
 
- 𝛽𝑇𝑉𝐿𝑜𝑤=−154.2971
 
- 𝛽𝑇𝑉𝑀𝑒𝑑𝑖𝑢𝑚=−75.3120
 
- 𝛽𝑅𝑎𝑑𝑖𝑜=2.9669
 

Question: What is your intepretation of the coefficient estimates? Are the coefficients statistically significant?

The default TV category for the model is High since there are coefficients for the other two TV categories, Medium and Low. Because the coefficients for the Medium and Low TV categories are negative, that means the average of sales is lower for Medium or Low TV categories compared to the High TV category when Radio is at the same level.

For example, the model predicts that a Low TV promotion is 154.2971 lower on average compared to a high TV promotion given the same Radio promotion.

The coefficient for Radio is positive, confirming the positive linear relationship shown earlier during the exploratory data analysis.

The p-value for all coefficients is 0.000
, meaning all coefficients are statistically significant at 𝑝=0.05
. The 95% confidence intervals for each coefficient should be reported when presenting results to stakeholders.

For example, there is a 95%
 chance that the interval [−163.979,−144.616]
 contains the true parameter of the slope of 𝛽𝑇𝑉𝐿𝑜𝑤


 ### Findings

According to the model, high TV promotional budgets result in significantly more sales than medium and low TV promotional budgets. For example, the model predicts that a Low TV promotion is 154.2971 lower on average than a high TV promotion given the same Radio promotion.

The coefficient for radio is positive, confirming the positive linear relationship shown earlier during the exploratory data analysis.

- The p-value for all coefficients is 0.000
 meaning all coefficients are statistically significant at 𝑝=0.05
. The 95% confidence intervals for each coefficient should be reported when presenting results to stakeholders.

For example, there is a 95%
 chance the interval [−163.979,−144.616]
 contains the true parameter of the slope of 𝛽𝑇𝑉𝐿𝑜𝑤
, which is the estimated difference in promotion sales when a low TV promotional budget is chosen instead of a high TV promotion budget.

 ### Findings to stakeholders

- High TV promotional budgets have a substantial positive influence on sales. The model estimates that switching from a high to medium TV promotional budget reduces sales by $75.3120
 million (95% CI [−82.431,−68.193])
- and switching from a high to low TV promotional budget reduces sales by $154.297
 million (95% CI [−163.979,−144.616])
 - The model also estimates that an increase of $1
 million in the radio promotional budget will yield a $2.9669
 million increase in sales (95% CI [2.551,3.383]
).

Thus, it is recommended that the business allot a high promotional budget to TV when possible and invest in radio promotions to increase sales.
