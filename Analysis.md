# Final-Report
Report for Final for 310D

After looping through the million or so rows of code, and sorting based on race (White or African American) and finding how many of them died from cardiovascular disease, we decided to try a chi-square test.

The p-value is the measure of a probability of reaching the observed results and alpha level is the probability of making a wrong decision, if the difference in p-values is less than the set alpha values the alternate hypothesis is correct (in this case, the alternate hypothesis is that African American people are at higher risk to die of cardiovascular disease than White people). If the difference in p-values is more than the set alpha value than the alternate hypothesis is rejected and the null hypothesis is correct (in this case, the null hypothesis is that there is no difference between the risk of African American people dying from cardiovascular disease and White people dying from cardiovascular disease. We got the p-value from each the categories (White and died from cardiovascualar disease and African American and died from cardiovascular disease). We then set the alpha-level to .05% as is the standard. 

The second comparison we made is between a "chi-squared statistic" and a "chi-square critical". The chi-s qaure statisitic is the difference between actual and predicted results represented as standard error. The chi-square critical is the cutoff between retaining or rejected the null hypothesis. If the chi-squared critical is greater than the chi-squared statisitic the null hupothesis could not be disproved which would mean that our results are not statistically signifiant. If the opposite is true, we reject the null hypothesis, which would meant that the alternate hypothesis is correct which would show that our result are statistically significant. 

Our results since almost all of the quantitites in the data are around equal was:
Chi Square Statistic: .66110342
Degrees of Freedom: 7
Chi Squared Critical Value: 14.06714045
P-Value: 0.998617077
Alpha Level: .05

Since our p-value is greater than our aplha lavel and our chi swaured critical value is greater than chi-squared statistic, we fail to reject our null hypothesis and cannot conclude that African Americans are more likely to die from cardiovascular disease than white people while using this Dataset. 

Limitations:

We realized to late that the data was pretty similar between the two groups, I think that the dataset that we used tried to have an equal amount of cases from both populations and cause of death, so it would be terrible indicator of the actual population. In addition, it is notable to mention that the number of cases listed for both was around the same, while African Americans represent around only 13.3% of the U.S. Population while White Americans are the majority at 76.3%. 

This test only takes into account this dataset, so we couldn't be sure for all cases across the U.S. 


