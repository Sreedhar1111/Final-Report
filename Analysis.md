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

Since our p-value is greater than our alpha level and our chi squared critical value is greater than chi-squared statistic, we fail to reject our null hypothesis and cannot conclude that African Americans are more likely to die from cardiovascular disease than white people while using this Dataset. 

Limitations:

We realized too late that the data was pretty similar between the two groups, I think that the dataset that we used tried to have an equal amount of cases from both populations and cause of death, so it would be terrible indicator of the actual population. In addition, it is notable to mention that the number of cases listed for both was around the same, while African Americans represent around only 13.3% of the U.S. Population while White Americans are the majority at 76.3%. 

This test only takes into account this dataset, so we couldn't be sure for all cases across the U.S. 

Answering the Questions:
1. Our intital hypothesis was that "African American people are more likely to die from cardiovascular disease than white people". We noticed that the data was very specific because it mentioned race, place that death occured, cause of death, and gender. 
2. We decided to use p-test and chi squared critical test because that is the most effecient way of finding whether two groups are correlated or not. 
3. I had only used a p-test in the past so the chi squared critical test was new to me so I found that interesting, I also learned how easy it is to misrepresent an entire group of people by using an incorrect dataset. We should have found a dataset that took into account all deaths proportionate to race and then used that to calculate if one race is more likely to die from cardiovascular disease than another. We didn't look to hard at the raw data, just because of the sheer amount of it, so we should have noticed way sooner that the cases reported in this data of white and African American's dying from Cardiovascular disease was around the same, so it is important to accurately vet a datset before choosing to use it. 
4. I don't think our findings are generalizable at all, I think it would be really hard to come up with any accurate findings with the way that the dataset we used was set up, although I didn't test it I would wager that all other aspects of the dataset are similar as well (ie: the amount of male to female is probably 50 50, same thing with locations, etc). 


