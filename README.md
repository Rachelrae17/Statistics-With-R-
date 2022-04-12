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

![total_summary](https://user-images.githubusercontent.com/95897182/163050744-c53f8c99-3e60-446d-a3c7-56821d678c44.png)
This Data shows the whole Total Dataset. 



This Is the Statistics From Manufacturing Lot. 






