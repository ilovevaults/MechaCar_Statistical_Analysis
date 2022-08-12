# MechaCar_Statistical_Analysis
## Goal
The goal was to solve production troubles for the company AutosRU and its new prototype vehicle. Some of the ojbectives that were completed included succesfully predicting which variables determined the mpg, collecting statistics on the PSI of suspension coils, and using t-tests to determine if the manufacturing lots were statistically from the mean population.
## Linear Regression to Predict MPG
1.There were two variables that showed a non-random amount of variance in the linear regression. They are both vehicle length
and ground clearance. This is because they both had the smallest p-values.
2. The slope of this linear analysis is not zero because it shows that some of the independent variables had an effect on the dependent variable which was the MPG.
3. The r-squared value which is 0.7149 which means out of 100 instances the MPG will be predicted correctly 71 times. This means that the model is effective.
![MPG Linear Regression](https://user-images.githubusercontent.com/98357581/172233046-d64e5fee-0b22-4f2a-85f5-dcecc80c582a.PNG)
## Summary Statistics on Suspension Coils
![Total_summary](https://user-images.githubusercontent.com/98357581/172239884-07f9a12e-3d59-4484-aef8-8461fe00b1c0.PNG)
![Lot_summary](https://user-images.githubusercontent.com/98357581/172239913-4b04003d-e422-4b4e-acd3-1aa31a5a2eb9.PNG)
Above are two summaries that were created to answer the following question
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
When looking at the total summary the variance is 62.29 PSI which falls below the 100 PSI limit set by the design specifications. 
The lot summary tells a different story because the variance in lot 3 is 170.29 which is well above the 100 PSI limit but both lot 1 and lot 2 both have not exceeded
the same limit with .99 and 2.73 respectively. 
## T-Tests on Suspension Coils
![One_Sample_T-test](https://user-images.githubusercontent.com/98357581/172242528-24d66994-a541-4a5d-abf2-b4bbd815917b.PNG)
![Lot1_T-test](https://user-images.githubusercontent.com/98357581/172242433-72a42285-aae2-42cb-b1ca-3e419d012376.PNG)
![Lot2_T-test](https://user-images.githubusercontent.com/98357581/172242444-4fa81585-e123-4999-9e6b-b0c8559ad49d.PNG)
![Lot3_T-test](https://user-images.githubusercontent.com/98357581/172242459-3f894c3a-1034-45d1-9656-a28189f236fa.PNG)

Based on these three T-tests for each lot only lot 3 which has p-value of .041 is statisically significant while both lot 1 which has a p-value of 1 and lot 2 which has a p-value of .61 are both not statisically significant.
