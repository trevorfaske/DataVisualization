# Data Visualizaiton

#### Disclaimer: this a continual work in progress

Data visualization is a key component to any scientific journal or popular science article. Being able to tell a compelling story using just the 
data at hand should be the goal of any figure. 

All of the code generating figures will be done in **R** using the package **ggplot2**. While I hope to incorporate some philosphy of good data 
visualization practices, a majority of these modules will be a *how to* on generating various types of figures within ggplot.

## ggplot2 - Grammar of graphics

[ggplot2 wiki](https://en.wikipedia.org/wiki/Ggplot2#:~:text=ggplot2%20is%20a%20data%20visualization,such%20as%20scales%20and%20layers.)

ggplot2 is one of the most widely used R packages and graphical programs used today. It breaks everything into *scales* and *layers*, 
allowing quick manipulaion of complex figure types. While it is very easy to get simple figures made, customization requires a more in-depth 
understanding of what is happening *under the hood*. Once you understand how to format your data in a manner ggplot works well with, it becomes 
largely intuitive. 

## Resources: 

Below is a all open-source book and course all on data visualization in R
- https://clauswilke.com/dataviz/
- https://wilkelab.org/SDS375/

R basics for those needing a refresher:
- https://rpubs.com/chalsch/intro_to_R

## Install R and RStudio Desktop

Both these programs are free and open-source. R is the actual program while RStudio is a user-friendly GUI (graphical user interface) to run R. 

- https://www.r-project.org/
- https://rstudio.com/products/rstudio/download/

It is possible to set up an R Jupyter Notebooks but it the interface of RStudio is much more user friendly.

## How to use this github repository

In this primer, we are going to be using the package "ggplot2" in R for graphing purposes. This will get use through the basics with a few various 
types of figures and how to cleanly modify them for to look a bit better. Josh Jahner will continue this next week, focusing more on the componenets 
of good figure making practices.

**For this priimer, you will need the *city_df.csv* file**