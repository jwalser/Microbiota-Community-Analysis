## Setup

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
