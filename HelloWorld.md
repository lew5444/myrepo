---
title: "Hello World"
author: "Laurel Wellman"
date: "2024-01-31"
output: 
  html_document: 
    keep_md: true
---


```r
plot(cars$speed ~ cars$dist)
```

![](HelloWorld_files/figure-html/unnamed-chunk-1-1.png)<!-- -->

```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

