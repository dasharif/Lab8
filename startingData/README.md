The columns I was interested in were hypertension, sex, bmi, age, dose of digoxin, cardiovascular disease, worsening heart failure, digoxin, number of hospitalizations, death, reason for death, chest x ray ct ratio, and ejection percentage. 
Next I counted how many empty cells were in the data frame and dropped those rows. Next I replaced all reasons for death with the phrase "Not Given"
I removed BMI outliers by calculating the 25th and 75th quartiles. Then I calculated the interquartile range. To determine the minimum and maximum I used the 25th and 75th quartile numbers and added or subtracted them by 1.5 * the interquartile range. 
Then I removed the outliers from the data frame and saved the dataframe to the startingData folder. 
