# Essential R
* Variable
* Data types
* Data structures
* Control flow
* Function
## Calculation
```r
1+1
2*2
3/5
10-20
5%%2

log(20)
exp(3)
sqrt(625)
abs(-100)
```
## Variables
``` r
my_name <- "Ampere"
my_age <- 21
#remove variables
rm(my_name)
rm(my_age)
```

## Data Types
|Type|Example|
|----|------:|
|Numeric| 100,200,3.5,5.9|
|Character| "Hello"|
|Logical| TRUE,FALSE|
|Factor|Categorical data in statistics e.g. gender (M/F), animals (dog,cat)|

## Logical#1
```r
# c() is a function to create vector
friends <- c ("Rin","Fha","Klinton","Ploy")
# check data types
class(friends)