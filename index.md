---
title       : Presentation
subtitle    : Simple Calculation
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Summary

My shiny application executes simple caluclation. It sums and calculates the mean of the two input values. Sum and mean are displayed.

--- 

## Code 


```r
n1<-"10"
n2<-"20"
s<-sum(as.numeric(n1)+as.numeric(n2))
s
```

```
## [1] 30
```

```r
m<-mean(c(as.numeric(n1),as.numeric(n2)))
m
```

```
## [1] 15
```

---

## Where to find?

<a href="https://vkriszta.shinyapps.io/shiny/">https://vkriszta.shinyapps.io/shiny/</a>

---

## Thank you for you attention!
