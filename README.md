# OccupationsNZ1891

R data package for occupation data from the 1891 census.

Exports a `occupations` a data frame with occupation data broken down
by age group and gender.

The occupations are grouped by _Class_, _Sub Class_ (can be undefined), _Order_,
_Sub Order_ and Occupation. The Occupation labels are not unique so the higher level
categories are needed to fully define the data.

## Use from R

```
install.packages('devtools')
devtools::install_github('nzherald/OccupationsNZ1891')
library(OccupationsNZ1891)
```

## Use from anywhere

There is a csv file `data-raw/occupations.csv`
