## Setup

Before we can start analysing our data we have to setup the R environment. This might take some time and it might cause some mild headache but together we can do it! So, hang in there and work your way though the setup steps. 

### Installation

Go to the R website and download the precompiled binary distributions you need: https://cran.r-project.org

Once installed, it is not always the best idea to get the latest and newest R version. Some of the packages you need might not yet be available and you would have to wait or compile it yourself. I would recommend not to change a running system too frequently and never in between a data analysis project.

The basic R installation comes with a simple console. You can also start R usning the terminal by simply typing R. If you prefer to us the console or terminal you might consider a text editor for code tranfer. I would recommend TextWrangler for Mac-Users (http://www.barebones.com/products/textwrangler/) and Notepad++ for Windows-Users (https://notepad-plus-plus.org). There are, however, alternatives.    

If you look for a easy to use frontend solution to the R programming language you might have a look at RStudio (https://www.rstudio.com). Don't forget, in order to run RStudio you have to install R first.


### Update



### Install Packages in R and Biodoncutor

Get an overview of what you have 
```R
version
library()   # see all packages installed 
search()    # see packages currently loaded
```
Install R packages
```R
install.packages("name_of_package") # install a package in R 
library(name_of_package)
```
Install Bioconductor packages
```R
source("https://bioconductor.org/biocLite.R")
biocLite("name_of_package")
```
Libraires needed for the analyis:
```R
library(phyloseq); packageVersion("phyloseq")
library(ggplot2); packageVersion("ggplot2")
library(reshape2); packageVersion("reshape2")
```
Setup working directory 
```R
list.files() # list files in working directory
setwd("/your/path/") # change working directory
getwd() # check if it is set correclty 
```
