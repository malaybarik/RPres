Temparature Conversion
========================================================
author: ABC 
date: 26th November 2014

Temparature Conversion Shiny App
========================================================

Table of content

- How Temparature conversion works
- Using Shiny App

How Temparature Conversion Works
========================================================

Temparature generally represented using two different scales.

- Centigrade [C]
- Fahrenheit [F]

Above two temparature scale is related C/5 = (F-32)/9

Temparature Conversion Functions
========================================================


```r
C2F <- function (Cent){
  return ((9/5)*Cent + 32)
} 
F2C <- function (Fahr){
  return ((5/9)*(Fahr - 32))
}
```

Example Temparature Conversion 
========================================================


```r
print (C2F(10))
```

```
[1] 50
```

```r
print (F2C(10))
```

```
[1] -12.22
```
