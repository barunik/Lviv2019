# Applied Econometrics (Finance and Macro)

## Lviv Data Science Summer School

by Jozef Barunik and Lubos Hanus

July 2019


First, we need to install packages


```r
install.packages(c("ggplot2","igraph","tseries", "forecast","vars","mAr","MASS","lmtest",
                   "lmtest","devtools","data.table","BigVAR","fastVAR"),dependencies=TRUE)
library(devtools)
install.packages("FinTS", repos="http://R-Forge.R-project.org")
install_github("tomaskrehlik/frequencyConnectedness", tag = "0.1.6") 
install_github("jeffwong/fastVAR")
```
