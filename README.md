# R Basics workshop material

This is an R package that will be used to collect workshop material for teaching basic R at Aarhus University.

## Basic usage
If you don't have the `devtools` package, please install this first by running `install.packages('devtools')`. 

To install the `rbeginner` and `learnr` packages, which contain the tutorial, please run: 

```r
devtools::install_github('rstudio/learnr')
devtools::install_github('emiltb/rbeginner')
```

The basic tutorial can then be started by running: 

```r
learnr::run_tutorial("basics", package = "rbeginner")
```

