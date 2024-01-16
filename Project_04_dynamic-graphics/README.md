# dynamic graphics in R

## Overview
This project introduces the R Shiny package, which allows us to create dynamic graphics. This project builds on the previous project, but we will now add the drop-down menu similar to the original [NYT version](https://archive.nytimes.com/www.nytimes.com/interactive/2013/03/29/sports/baseball/Strikeouts-Are-Still-Soaring.html?_r=0&ref=baseball), and highlight season statistics from that team (the yellow line). 


## Files
- `dynamic-graphics.Rmd`: The R Markdown source file with the analysis code and narrative.

[Please click here to view the project without running the code](http://rdk7kk-m0ge-ko0ar.shinyapps.io/dynamic-graphics): This is created using R Shiny package.

## How to Run
1. Clone this repository to your local machine.
2. Open `dynamic-graphics.Rmd` in RStudio.
3. Install any required packages using:
   `install.packages("dplyr")`
   `install.packages("pander")`
   `install.packages("Lahman")`
   `install.packages("shiny")`
   `install.packages("flexdashboard")`
4. Please ensure that you load these packages in your R session before executing the code by using:
   `library( dplyr )`
   `library( pander )` 
   `library( Lahman )` 
   `library( shiny )` 
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


