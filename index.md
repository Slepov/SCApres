---
title       : "Stock Chart App"
subtitle    : 
author      : "Dmitri Slepov"
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## About

This is simple app that plot stock charts.
#### You can: 
- choose a company symbol, e.g. MSFT, GOOG, FB
- choose a date range
- choose a chart type
- add a moving average 

--- 

## Quantmod

This app uses the quantmod package.

```r
library(quantmod)
getSymbols("FB", from="2014-06-01")
```

```
## Warning: downloaded length 3943 != reported length 200
```

```
## [1] "FB"
```

```r
last(FB)
```

```
##            FB.Open FB.High FB.Low FB.Close FB.Volume FB.Adjusted
## 2014-09-19    77.4    78.3  76.44    77.91  76638600       77.91
```

---
## Example



---
## Links

- Try it on shinyapps.io ([stockchart] (http://slepov.shinyapps.io/stockchart/))
- Source code is available on  the [GitHub] (https://github.com/Slepov/courseproject_DDP)


