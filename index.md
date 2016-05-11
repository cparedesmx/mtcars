---
title       : Interactive Regression Model
subtitle    : Slidify presentation for Developing Data Products
author      : Cutberto Paredes
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
ext_widgets : {rCharts: [libraries/nvd3]}
---

## Introduction

- This shiny app let's the user build a regression model for mpg usin the mtcars
dataset.

- You only have to select which regressors you wanna use and the app will return
the coefficients, $r^2$ values and a standardized residuals QQ plot.

---
## Pairs plot

This plot may help you select regressors.

<img src="assets/fig/ggpairs-1.png" title="plot of chunk ggpairs" alt="plot of chunk ggpairs" style="display: block; margin: auto;" />

---
## The app itself

- The app is available here: https://cparedes.shinyapps.io/shiny/

- This is how it looks:

<center><img src=figure/shinny.jpg></center>

---
## Interactive Plot

This rCharts plot shows the relationship between $mpg$ and $hp$, a regressor I 
suggest to include.

<iframe src=' assets/fig/plot-1.html ' scrolling='no' frameBorder='0' seamless class='rChart polycharts ' id=iframe- chart1ff0787d4e98 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>
