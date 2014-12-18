---
title       : Body Mass Index Calculator
subtitle    : Shiny and slidify Project
author      : Ragini
job         : 
framework   : io2012   # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Body Mass Index (BMI) calculator using shiny

This presentation is about BMI calculator shiny application. 

Application takes height and weight as input and computes BMI.

Application also has information in the left side panel to categorize BMI as underweight, overweight, obese, etc.

--- 

## Application input

Application has 2 input parameters

Height in inches

Weight in pounds

Application will also show height converted to meters and weight converted to kilograms 

---

## Application Output

If user has entered valid input and output, application will show bmi with a formula demonstrated in following R code


```r
heightInches=60
weightPounds=125
bmi=weightPounds*703/(heightInches*heightInches)
bmi
```

```
## [1] 24.40972
```


---

## BMI classification

BMI can be interpreted as follows

Underweight = <18.5

Normal weight = 18.5-24.9

Overweight = 25-29.9

Obesity = BMI of 30 or greater

---


