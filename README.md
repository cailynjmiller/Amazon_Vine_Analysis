# Amazon_Vine_Analysis
## Overview
The purpose of this analysis is to see if there is any positivity bias in reviews of Toys from vine users by comparing the amount of 5 star reviews from vine users and non-vine users.
## Results
The original data for toy reviews has been filtered on records where the total votes count is greater than 20 and the helpful_votes percentage is greater than 50% in order to pick reviews that are more likely to be helpful.<br/>
I created a DataFrame of only vine reviews<br/>
![vine df](https://github.com/cailynjmiller/Amazon_Vine_Analysis/blob/main/photos/vine%20df.png)<br/>
I created a DataFrame of only non vine reviews<br/>
![non vine df](https://github.com/cailynjmiller/Amazon_Vine_Analysis/blob/main/photos/not%20vine%20df.png)<br/><br/>
After applying the filters:
<br/><br/> There are 1,266 from vine users and 66,569 not from vine users.
![number users](https://github.com/cailynjmiller/Amazon_Vine_Analysis/blob/main/photos/total%20reviews.png)
<br/> There are 432 votes that are 5-stars from vine users and 32,489 from non-vine users.
![number 5 stars](https://github.com/cailynjmiller/Amazon_Vine_Analysis/blob/main/photos/total%205%20star.png)
<br/> 34.12% of reviews from vine users are 5-star and 48.81% of reviews from non-vine useres are 5-star.
![percentage](https://github.com/cailynjmiller/Amazon_Vine_Analysis/blob/main/photos/percentage.png)
## Summary
There does not appear to be a positivity bias from the vine reviews because the percentage of 5-star ratings is around 14% lower than that of reivews from non-vine users. Some other things to take into consideration is that there are significantly more non-vine reviews than vine reviews which could introduce some complications to coming up with a reliable comparison. Because of this, I recommend taking an equal sample from the both the vine reviews and non vine reviews dataframes and compare them with the same calculations.
