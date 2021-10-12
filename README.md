# MPG_CaseStudy
this notebook is for educational purpose . in this notebook i will go through some statistical concept , try to get some statistical insight ,, clean the data ,EDA , and apply ML model


## Introduction

### Dataset Description 

> i will go through auto-mpg : this dataset is a slightly modified version of the dataset provided in the StatLib library. In line with the use by Ross Quinlan (1993) `in predicting the attribute "mpg"`, 8 of the original instances were removed because they had unknown values for the "mpg" attribute. 
>- "The data concerns city-cycle `fuel consumption` in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 continuous attributes." (Quinlan, 1993) 
 >   - Mpg: Miles per Gallon. 
  >      - " note :if the miles per gallon increase the fuel consumption will decrease" 
 >   - cylinders: No. of Cylinders.
 >   - displacement: Engine size "engine capacity ".
 >   - horsepower: Engine power.
 >   - Weight: Car weight.
 >   - acceleration: how fast can accelerate in seconds
 >   - model_year: Car year model.
 >   - Origin: Car country of manufacture.
 >      - 1 is for usa , 2 for europ and 3 for japan 
 >    - car_name: Car model.
    

- and i will go through some statistical analysis
### Questions i will use for Analysis
> - what is the car that has less fuel consumption
> - the relation between cylinders and mpg 
>  - the relation between displacement and mpg 
>  - the relation between horsepower and mpg 
>  - the relation between weight and mpg 
 > - the relation between acceleration and mpg
 > - the relation between model year and mpg
 > - the relation between origin and mpg
 
 ### Conclusions about the data

>- The most frequency cylinder is 4
>- The cars with 4 cylinders has the highest MPG
>- The car from japan are the most effencient cars has the highest mpg with mpg average = 32 " less fuel consumption" and the car from usa are the least efficient ones with mpg average= 18
>- As long as the engine size is small and we use a less number of cylinder like 4 there will be less fuel consumption
>- The more increasing of cylinders and the engin size the the less efficient the car is, as It burns more fuel and drives less mileage per gallon.
>- Using such big engin size like USA does make it has higher fuel consumption
>- We have USA with the largest mean of Engine size with value = 250
>- Car with 8 cylinders has the largest engine power which means more fuel burn and less MPG
>- In MPG vs year There are some ups and downs, But average miles per gallon has increased over time, with high standard deviation number.
>- Mileage per gallon in cars with the USA country origin has increased over time, Specially since the beginning of 1975. But japan and europe cantry origin is randomly distributed (ups and downs of mpg over time) 
>- Although USA is the only country that has a stabel increase in mpg , it still the less efficient , and even when japan and europ have some downs it still higher than USA in the same year
>- As the weight of the car increase the car will burn more fuel to move
>- When the number of cylinder increase the car will accelate faster but it will burn more fuel
