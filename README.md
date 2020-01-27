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
|----|:------:|
|Numeric| 100,200,3.5,5.9|
|Character| "Hello"|
|Logical| TRUE,FALSE|
|Factor|Categorical data in statistics e.g. gender (M/F), animals (dog,cat)|

```r
# c() is a function to create vector
friends <- c ("Rin","Fha","Klinton","Ploy")
# check data types
class(friends)
```

### Logical #1
``` r
# create variable x
x <- 100

# conditions
x == 100
x != 100
is.numeric(x)
is.character(x)
```

### Logical #2
``` r
x <- c(100, 200, 300, 400, 500)
x >= 300
# FALSE FALSE TRUE TRUE TRUE
# TRUE = 1 FALSE = 0
sum(x >= 300) ## 3
mean(x >= 300) ## 0.6
```

### Factor
``` r
gender <- c("Male", "Male", "Male", "Male", "Female")
gender <- factor(gender)

## cehck data types
class(gender) ##Factor
print(gender) ##Levels: Female Male
```
