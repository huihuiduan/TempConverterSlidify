---
title       : Temp Converter
subtitle    : Temperature Conversion
author      : Huihui Duan
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Convert Fahrenheit & Celsius

Input 1: Degree Quantity

```r
(dq = 0)
```

```
## [1] 0
```
Input 2: From Fahrenheit or Celsius

```r
(cf = "Celsius")
```

```
## [1] "Celsius"
```

--- .class #id 

## Copied

Copied from the input: 

Result: 

You entered: 

```r
paste(dq, cf)
```

```
## [1] "0 Celsius"
```

---
## Temp Converter to Fahrenheit

was converted to:

```r
paste(format(round(dq * 9 / 5 + 32, 2), nsmall = 2), "Fahrenheit")
```

```
## [1] "32.00 Fahrenheit"
```

---
## From Fahrenheit to Celsius
Input 1: Degree Quantity

```
## [1] 0
```
Input 2: From Fahrenheit or Celsius

```
## [1] "Fahrenheit"
```

You entered: 

```
## [1] "0 Fahrenheit"
```

was converted to:

```
## [1] "-17.78 Celsius"
```


