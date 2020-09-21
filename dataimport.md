Data Import
================

``` r
library(tidyverse)
```

    ## -- Attaching packages --------------------------------- tidyverse 1.3.0 --

    ## v ggplot2 3.3.2     v purrr   0.3.4
    ## v tibble  3.0.3     v dplyr   1.0.2
    ## v tidyr   1.1.2     v stringr 1.4.0
    ## v readr   1.3.1     v forcats 0.5.0

    ## -- Conflicts ------------------------------------ tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

## Read in some data

Read in the litters dataset.

``` r
litters.df = read.csv("/Users/danie/Documents/Columbia Semester 1 Files/Data Science  R Code/Data Wrangling/data_wrangling_1/data/FAS_litters.csv")
litters.df = janitor::clean_names(litters.df)
```

## Take a look at data
