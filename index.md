---
title       : "Stock Chart App"
subtitle    : 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2


```r
library(quantmod)
getSymbols("FB", from="2014-06-01")
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



