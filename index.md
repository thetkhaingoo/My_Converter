---
title       : Temperature Unit Converter 
subtitle    : From Fahrenheit to Celsius or Vise Versa.
author      : Thet K. Oo    
job         : Data Product Developer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Why Temperature Unit Converter?

1. Very user friendly
2. You don't have to remember the complicated formula to convert Fahrenheit to Celsius or vise versa
3. You don't have to Google with complicated question like "0 C in F" or worse still "40 F in C"; very awful, awful experience.
4. Pretty cool because the app is created with Shiny

--- .class #id 

## Who should use it?

1. Everyone and their brother-in-law
2. Whoever with intense interest for weather.
3. When you don't know what to wear

---

## How does it work?

1. First it accept user input, either in F or C
2. Using the respective formula, it calculates and prints out the answer.
3. For e.g., if you want to convert 40F to C, you just need to type in 40 at the Fahrenheit box.
4. The app will use the R programming to convert it 


```r
inF = 40
C = (inF - 32) * 5/9
C
```

```
## [1] 4.444444
```

---

## Thank you! ##






