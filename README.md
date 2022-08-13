# MechaCar_Statistical_Analysis

## Overview
In this modules we learned R language which is similar to python but is much more focused into statistical analysis. This language mixes an useful set of lybraries such as plting libraries, json importing and anlytical calculations to create a complete analysisi while having the flexibility to perform dataset trasnformation to keep all in one. 

The interface is super useful while having a display for testing formulas, a terminal to see the outputs, an enviroment to track all variables, tables and objects in the file and a help screen that swithces according to the needs of the code called.

For this specific challenge we were asked to make calculations and anlyse the results for a prototype product developed by car company AutosRU's. Their painpoint comes into the production lines and want to understand better whats troubling the manufacturing team progress. 

## Linear Regression to Predict MPG
![Linear_Regression](https://github.com/dpiedra86/MechaCar_Statistical_Analysis/blob/main/Linear_regression_mpg.png)
>Linear Regression
We can see correlation between vehicle lenght to MPG. 
We observe low correlation to MPG and vehicle weight.
Looking at the P-value we can say that the null hypotesis is rejected, the relationship is more than randaom. 
The R-Squared factor of 71% suggest the study  will provide insghts on the excercise.

##Statistic_Suspenssion
![Statistic_Suspenssion](https://github.com/dpiedra86/MechaCar_Statistical_Analysis/blob/main/Statistics_Supenssion_Coil.png)
>Statistics_Suspenssion
Lot 3 seems to be an outlier with a variance of 170 being a red flag to look at. 
This is moving the needle towards a negative side of the vector. 

##Test All Suspenssions
![Suspenssions](https://github.com/dpiedra86/MechaCar_Statistical_Analysis/blob/main/Test_Supenssion_ALL.png)
>Test_All
All lots toether seem to be similar enough, the p-value isn't enough to reject the null hypotesis. 


##Test_1
![Test_1](https://github.com/dpiedra86/MechaCar_Statistical_Analysis/blob/main/Test_Supenssion_Lot1.png)
>Lot_1
Seems to be the healthiest of the three locations. Should be kept as the benchmark.

##Test_2
![Test_2](https://github.com/dpiedra86/MechaCar_Statistical_Analysis/blob/main/Test_Supenssion_Lot2.png)
>Lot_2
Can improve performance, still is not a bad performer. Can make some improvements. 

##Test_3
![Test_3](https://github.com/dpiedra86/MechaCar_Statistical_Analysis/blob/main/Test_Supenssion_Lot3.png)
>Lot_3
Definitely this is where problemas are happening. The company should take a look at the production protocols, teams and machinery to underastand what is happening and make the needed adjustments. 

##MechaCar vs Competition

With the previous analysisi we can move forward to analyse the products vs de compentce. 
There are many points of comparison, but the main should be performance. 
Perfromance under different conditions and measuring the behaviour of the parts, like braking in wet conditions, curves at high speed, hard stop breaking and how much control can be kept at different speeds.

Taking this points in consideration will give us an input in how we can improve our parts, towards competitors performance. 
