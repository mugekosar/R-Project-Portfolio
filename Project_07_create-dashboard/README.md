# create dashboad in R

## Overview
This projects aims to create a dashboard using Tempe's traffic accidents dataset to provide insights through six interactive tabs. The dashboard will feature accident exploration by time and driver characteristics, a color-coded leaflet map of accidents, detail pop-ups, and input widgets for user-defined queries. It will display key statistics like crash numbers, injury rates, and fatalities.

## Files
- `create-dashboard.Rmd`: The R Markdown source file with the analysis code and narrative.

[Please click here to view the project without running the code](http://rdk7kk-m0ge-ko0ar.shinyapps.io/Project)

## How to Run
1. Clone this repository to your local machine.
2. Open `create-dashboard.Rmd` in RStudio.
3. Install any required packages using:
   `install.packages("DT")`
   `install.packages("pander")`
   `install.packages("ggmap")`
   `install.packages("shiny")`
   `install.packages("knitr")`
   `install.packages("leaflet")`
   `install.packages("viridis")`
   `install.packages("rsconnect")`
   `install.packages("tidyverse")`
   `install.packages("flexdashboard")`
4. Please ensure that you load these packages in your R session before executing the code by using:
   `library( DT )`
   `library( pander )` 
   `library( ggmap )` 
   `library( shiny )` 
   `library( knitr )` 
   `library( leaflet )` 
   `library( viridis )` 
   `library( rsconnect )` 
   `library( tidyverse )` 
   `library( flexdashboard )` 


5. Run the Rmd file to reproduce the analysis and generate the HTML report.

## Requirements
- R
- RStudio
- Listed R packages on the above.


## Author
- [Muge Kosar](https://github.com/mugekosar)

## Acknowledgments
- This project was completed as part of the Introductory Data Science course in R, taught at the Andrew Young School of Policy Studies, Georgia State University.


