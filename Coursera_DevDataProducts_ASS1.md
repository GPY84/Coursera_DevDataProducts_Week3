Coursera_DevDataProducts_ASS1
========================================================
author: Thomas Goeppert
date: June 18th 2020
autosize: true

Task
========================================================

Create a web page presentation using R Markdown that features a plot created with Plotly. Host your webpage on either GitHub Pages, RPubs, or NeoCities. Your webpage must contain the date that you created the document, and it must contain a plot created with Plotly. We would love to see you show off your creativity!

Code
========================================================


```r
library(plotly)
plot <- plot_ly(x = mtcars$wt, y = mtcars$mpg,color = mtcars$qsec, mode = "markers")
```

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-2](Coursera_DevDataProducts_ASS1-figure/unnamed-chunk-2-1.png)

