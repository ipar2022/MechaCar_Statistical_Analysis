# MechaCar_Statistical_Analysis

- Overview of Analysis

- This analysis was performed to investigate AutosRUs newest prototype the MechaCar. Which is suffering from delayed production. This data will be supplied to leadership with insights that will help.

## Linear Regression to Predict MPG
- ![summary_LR](https://user-images.githubusercontent.com/113808332/221390272-f33e1f3f-178b-40a7-812c-e858d5147911.png)






- 1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The spoiler angle, vehicle length, and AWD all contributed to non-random variances. The noteworthy variables are ground clearance and vehicle length.

- 2. Is the slope of the linear model considered to be zero? Why or why not?
The slope of the line is not zero as shown by the p-value of 5.35⁻11

- 3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear regression is somewhat efficient at predicting the mpg. When considering R-2 value of 0.71 of the mpg variations are attributed to vehicle length, spoiler angle, vehicle weight to name a few. 


## Summary Statistics on Suspension Coils


- Total summary statistics for all manufacturing lots


-![s_c](https://user-images.githubusercontent.com/113808332/221390630-50cd25fb-e906-4675-8d27-cd41c2869930.png)




- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The summary statistics variance of the suspension coils overall is 62.29 psi. Lot 1 has a variance of 0.97 psi, Lot 2 has a variance of 7.46 psi, and Lot 3 has a variance of 170.28 psi. Lot 1 and Lot 2 are within there limits. Lot 3 has a strongly skewed variance which is outside of the design specifications.


- Each manufacturing lot summary statistics


-![M_L lot summary](https://user-images.githubusercontent.com/113808332/221390766-a31a2530-02f4-4c57-8558-6692d9074cb3.png)



## T-Tests on Suspension Coils

-![onet-test](https://user-images.githubusercontent.com/113808332/221391095-2830ec84-2077-410f-ac4f-cf24c84d1f53.png)




- ![Lots 1-3](https://user-images.githubusercontent.com/113808332/221391305-a6792df5-2ac0-46c1-b7f7-418a470f63e5.png)





## Study Design: MechaCar vs. Competition

- 1. What metric or metrics are you going to test?

- 2. What is the null hypothesis or alternative hypothesis?

- 3. What statistical test would you use to test the hypothesis? And why?

- 4. What data is needed to run the statistical test?

