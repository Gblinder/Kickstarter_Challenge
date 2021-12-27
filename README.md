In general, the percentage of successful Kickstarter campaigns accompanied with plays subcategory for the goal amount range less than 35000 and greater than 45000 has suffered a downward behavior, while with similar range, the percentage of the failed Kickstarter campaigns has experienced an upward growth. In other words, the successful and failed campaigns interact with each other in the recent ranges. 
In addition, in the goal amount range 35000-44999, there is no noticeable change in the rate of progress or regression of the successful and failed Kickstarter campaigns.
It is noteworthy that percentage of the successful Kickstarter campaigns in the goal amount range 45000-49999 is zero and we have 100% failure experience.


 Furthermore, we only compare the "Percentage Failed" and "Percentage Successful" because of zero "Percentage Canceled" and they are complimentary of each other to reach 100%. In other words, increasing one of them is accompanied by decreasing the other and no other factor will affect these results.  


It is noteworthy that percentage of the successful Kickstarter campaigns in the
* To populate the “Number successful”, “Number Failed” and “Number Canceled”, columns and using the “countifs”, I got confused and thought that I should filter the columns of Kickstarter based on successful/Failed/canceled as well as subcategory based on plays but after checking the data set, I realized that it does not matter if it is filtered or not. However, the “countifs” performs this filtering.
* Because in the “Canceled Number” column, all the cells got a value of 0, thus I was not sure if all columns would be zero or not. By filtering the outcomes using “Canceled” along with subcategory using “plays”and checking the data set, I could not find a common point and I made sure that the column D in the outcomes based on goals sheet correctly selected.
* In chart “ Outcomes_ vs_Goals”, the values on the vertical axis did not conclude the percentage symbol ”%”, I could solve this problem by right click on the column and selecting “Format cell/Percentage”. 


