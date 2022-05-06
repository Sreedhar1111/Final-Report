# Final-Report
Report for Final for 310D

After looping through the million or so rows of code, and sorting based on race (White or African American) and finding how many of them died from cardiovascular disease, we decided to try a chi-square test.

The p-value is the measure of a probability of reaching the observed results and alpha level is the probability of making a wrong decision, if the difference in p-values is less than the set alpha values the alternate hypothesis is correct (in this case, the alternate hypothesis is that African American people are at higher risk to die of cardiovascular disease than White people). If the difference in p-values is more than the set alpha value than the alternate hypothesis is rejected and the null hypothesis is correct (in this case, the null hypothesis is that there is no difference between the risk of African American people dying from cardiovascular disease and White people dying from cardiovascular disease. We got the p-value from each the categories (White and died from cardiovascualar disease and African American and died from cardiovascular disease). We then set the alpha-level to .05% as is the standard. 

The second comparison we made is between a "chi-squared statistic" and a "chi-square critical". The chi-s qaure statisitic is the difference between actual and predicted results represented as standard error. The chi-square critical is the cutoff between retaining or rejected the null hypothesis. If the chi-squared critical is greater than the chi-squared statisitic the null hupothesis could not be disproved which would mean that our results are not statistically signifiant. If the opposite is true, we reject the null hypothesis, which would meant that the alternate hypothesis is correct which would show that our result are statistically significant. 

```mermaid

graph
 Observed Counts
 Race/Ethnicity
 NEWLINE
 Outcome
 Black, non-Hispanic
 White, non-Hispanic
 NEWLINE
 Hospitalization for acute myocardial infarction
 954
 954
 NEWLINE
 Hospitalization for heart failure among Medicare-eligible persons aged >= 65 years
 1560
 1560
 NEWLINE
 Hospitalization for stroke
 954
 954
 NEWLINE
 Mortality from cerebrovascular disease (stroke)
 1530
 1530
 NEWLINE
 Mortality from coronary heart disease
 1530
 1530
 NEWLINE
 Mortality from diseases of the heart
 1530
 1530
 NEWLINE
 Mortality from heart failure
 1482
 1530
 NEWLINE
 Mortality from total cardiovascular diseases
 1530
 1530
```
