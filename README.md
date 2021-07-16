# UBC_MSc_thesis
__masters research data analysis__

This is Hannah McSorley's thesis repository for UBC MSc in Geological Sciences (hydrology) 2018-2020.

This repo contains files for data analysis and interpretation in R.
All R project files were pushed to github. 

Folder description:

- R-inputs contains files that are brought into R for processing. 
  - Each dataset has it's own directory (e.g. odyssey water level loggers, shimadzu TOC analyzer, Scan Spectrolyser spectrophotometer, Hobo TidbiT temperature sensors, or shared data from the CRD)
- R-outputs contains ONLY files that were generated through processing in R (e.g. results csv, images and plots)
- The .Rmd files are organized sequentially as chapters which are knit into a book through the bookdown package in RStudio. 
  - Filenames that begin with "_" are not stitched into the book. The index.Rmd file contains the document metadata and forwards. The _output.yml and _bookdown.yml files contain bookdown yaml commands. 
