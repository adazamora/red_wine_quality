# Red Wine Quality

I used RStudio to analyze the chemical properties that influence the quality perception of red wines, using a dataset with 1599 observations composed of 11 chemical properties and a rating.

I did this project as part of the Exploratory Data Analysis course, from the Data Analyst Nanodegree I took at Udacity.

## Requisites

RStudio
R version 3.4.2 

``` 
require(devtools)
install_version("ggplot2", version = "2.2.1", repos = "http://cran.us.r-project.org")
install_version("dplyr", version = "0.7.4", repos = "http://cran.us.r-project.org")
install_version("gridExtra", version = "2.3", repos = "http://cran.us.r-project.org")
install_version("psych", version = "1.7.8", repos = "http://cran.us.r-project.org")
install_version("memisc", version = "0.99.14.5", repos = "http://cran.us.r-project.org")
```

## Data

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
  Modeling wine preferences by data mining from physicochemical properties.
  In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.
  
Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016
                [Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf
                [bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib

To download from Kaggle: https://www.kaggle.com/piyushgoyal443/red-wine-dataset/data
