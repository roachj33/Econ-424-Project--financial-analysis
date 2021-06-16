# Econ-424-Project--financial-analysis
This repository contains analysis of the financial performance of 6 mutual funds (those being vfinx, veurx, veiex, vbltx, vbisx and vpacx)
over the time period from October 2014 to October 2019. An overview of the contents of the analysis can be located within the "Table of Contents"
section of the Project report PDF file, on page 1 of that document. The repository contains the Rmd file which conducted the analysis as well as a pdf
of the formal report of my findings, which was a result of knitting the contents of the Rmd file.

To perform this analysis, it is expected that the user has the following R libraries are installed (Note that if a user wants to install a `package` in R,
they need only run the command 'install.packages(`package`)'):
* IntroCompFinR
* PerformanceAnalytics
* tseries
* zoo
* boot
* corrplot
* knitr

The analysis for this project pulls the data within the Rmd itself, so it is not necessary for the user to have pre-downloaded any data to run this script.
