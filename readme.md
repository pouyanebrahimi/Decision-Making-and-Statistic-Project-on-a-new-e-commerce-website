# Analyze A/B test results run by an e-commerce website
## Pouyan Ebrahimi


## Dataset

> This project is about understanding the results of an A/B test run by an e-commerce website. The goal is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.


## Summary of Findings

>
**Part I- A/B Test**
The portion of people who are receiving new page or old page is equal, 50%. Besides, the population of data is good enough.

By knowing this, the comparison between the converted people in old and new page is fair.

Number of converted people from old_page (control group)= 0.1203
Number of converted people from new_page (treatment group)=0.1188
So, we could conclude that the number of converted people from old_page is more than the number new page.


**Part II- A/B Test**
Since the z-score of 1.311 does NOT exceed the critical value of 1.645, we do not have enough evidence to reject the null hypothesis that the old_page is better or equal to nex_page.

Spoken plainly, landin the old page (17489/17264) is statistically better than landing new page (145274/145310). It could be expected that old_page performance os better than the new one which is in agreement with previous results.

**Part III - A regression approach**
the relationship is between new/old page and the converted columns may be affected by other things such as timestamp column, or the age of people who are in this data, or maybe the country that the data is collected from.

The disadvantage of adding new columns may be:

the new columns may be dependent to the columns (multicollinearity). This will bring some issues to the interpretations.
There may exist some ouliers in new factors/columns
