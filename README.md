MechaCar_Statistical_Analysis 
Overview: 

The Overall project review for this analysis was to observe the MechaCar. By Observing miles per gallon and suspension coils. This Car was made in order to improve the performance. As to be the best car in comparision to the other cars that are on the market. This car main focus on performance with the cost, city and higway fuel, efficiency on horse power, and the up keep maintence cost on the car and the safety ratings. All these key points were considered and eveulated in this analysis. 

The Main Key points for the MechaCar analysis are: 

~ A Linear Regression to predict Miles Per Gallon 

~ Summary Statistics on Suspension Coils

~ T-Test on Suspension Coils 

Linear Regression To Predict MPG 
In order to determine an outcome for the code variables were used in R. A Multiple Linear Regression. This Was the Code that was used: 

lm(mpg ~ vehicle_length + vehicle_weight + spoiler_angle + ground_clearance + AWD, data=base_table)

summary(lm(mpg ~ vehicle_length + vehicle_weight + spoiler_angle + ground_clearance + AWD, data=base_table))

This code was the second code used in order to get all the data that we needed to answer the following questions of a Linear Regression. 

![multiple_linear_regression_model](https://user-images.githubusercontent.com/95897182/163045468-73e1b6c1-dc68-473d-add8-b72e2a12a669.png)


Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The Variables that are significant impact on Miles Per gallon were the Ground_Clearence & the Vehicle_Length. 

Is the slope of the linear model considered to be zero? Why or why not?

No, Not Zero for the slope. The Slope = 0.05

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Yes, I would say that the Linear Model predict Miles per gallon of MechaCar prototypes is effevtive by the model car by approximatley 71.5% impact on the miles per Gallon. 


Statistics on Suspension Coils 


This Data shows the Whole Total Dataset. 

![total_summary](https://user-images.githubusercontent.com/95897182/163050744-c53f8c99-3e60-446d-a3c7-56821d678c44.png)


This Is the Statistics From Manufacturing Lot. 

![lot_summary](https://user-images.githubusercontent.com/95897182/163052152-e2fc4128-d7c8-4d20-ac4b-f9456bad2207.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

It must not exceed 100 PSI. This is Acceptable becuase the total summary of a variance is 62.29 PSI which is lower than 100 PSI. 

T- Test on Suspension Coils 

The T-test were performed both on a individual Manufacturing lots and Random sample.To determine whether the PSI from a population mean of 1,500 PSI. 

![ttest_one_sample](https://user-images.githubusercontent.com/95897182/163056013-744d37db-8fa4-4386-ae93-c378f2a6cf2f.png)

This is the P-vale Random Sample of the population for 0.2247 Where as the Significance level is 0.05. 

![ttest_lot_1](https://user-images.githubusercontent.com/95897182/163055713-f8655407-4321-40b5-a270-e39a9d50fd60.png)

The p-vale of lot 1 is subset of the population. These two populations are very similiar when comparing with this image of the dataset. 

![ttest_lot_2](https://user-images.githubusercontent.com/95897182/163057154-6108c28d-77c1-4bed-b02e-400ca2473717.png)

The P-vale for Lot 3 population was 0.042, which falls way below significance levels of the 0.05. This does not match the null of the hypothesis. 















