### Install
```r
install.packages("devtools")
library("devtools")
```

### Generate Documentation using roxygen2
```r
install.packages("roxygen2")
library(roxygen2)

roxygen2::roxygenize()
```

### Build and Install
```r
# create tar.gz file
devtools::build()

# install the package
devtools::install()
```
### Usage
```r
library(arithmetic)

c_mean(c(1,2,3,4,5))
```