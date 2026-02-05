
# Transforming IMTS tables into SDMX tables

The goal of IMTS2SDMX package is to allow users to be able to generate International Merchandise Trade (IMTS) SDMX files out from published IMTS excel files. 

## Excel file preparations

Before using the IMTS2SDMX R package, you will need to reorganize your IMTS published tables as follows:

1. Create an excel file
2. Add the following worksheets in the excel file:
    
    1. **bot** – Balance of trade table  
    2. **imports** – Imports table  
    3. **exports** – Domestic exports table  
    4. **reexports** – Re-exports table  
    5. **bot_cty** – Balance of trade by partner countries table  
    6. **trade_reg** – Trade by region table  
    7. **mode_trspt** – Trade by mode of transport table

    
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

This is a basic example which shows you how to organise your excel worksheet tables:

[Download sample IMTS file](inst/extdata/sample_IMTS.xlsx)

