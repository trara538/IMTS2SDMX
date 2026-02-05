
# Transforming IMTS tables into SDMX tables

The goal of IMTS2SDMX package is to allow users to be able to generate International Merchandise Trade (IMTS) SDMX files out from published IMTS excel files. 

## Excel file preparations

Before using the IMTS2SDMX R package, you will need to reorganize your IMTS published tables as follows:

1. Create an excel file
2. Add the following worksheet in the excel file
    i.   bot        - Balance of trade table
    ii.  imports    - imports table
    iii. exports    - domestic exports table
    iv.  reexports  - reexports table
    v.   bot_cty    - Balance of trade by partner countries table
    vi.  trade_reg  - Trade be region table
    vii. mode_trspt - Trade by mode of transport table
    
Refer to this sample excel file [Download sample IMTS file](inst/extdata/sample_IMTS.xlsx)


## Installation

You can install the imtsShiny like so:

``` r
# **************** How to install the package from R console ******************** #

>install.packages("remotes")
>library(remotes)
>remotes::install_github("https://github.com/trara538/IMTS2SDMX")

# **************** How to run the imtshiny app from R console ******************** #
>library(IMTS2SDMX)
>IMTS2SDMX::run_app()

```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(imtsShiny)
## basic example code
```
