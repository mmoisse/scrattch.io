# scrattch.io  
### File format handling for scrattch packages

## Installation

scrattch.io has several dependencies, including one from BioConductor:
```
source("https://bioconductor.org/biocLite.R")
biocLite("rhdf5")

install.packages("dplyr")
install.packages("h5")
install.packages("Matrix")
install.packages("purrr")
```

Once these are in place, scrattch.io can be installed from github:
```
devtools::install_github("AllenInstitute/scrattch.io")
```
## .tome files
A major component of scrattch.io is a set of helpful functions for writing and reading .tome files, which are an HDF5-based format for transcriptomics.  

The [.tome cheatsheets on Google Docs](https://docs.google.com/spreadsheets/d/1tJUgnfEXUv1IuzGAykDCTIUTsgzEWkT-jfl4UcEUl48/edit?usp=sharing) is a helpful reference.

## Contact
Contact Lucas Graybuck (lucasg@alleninstitute.org) or post an Issue on Github if you find a bug or have a feature request.