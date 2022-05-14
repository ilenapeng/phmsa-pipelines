# Pipeline incidents, post 2010

This repository contains the data and analysis used for our article on pipeline incidents in the U.S. that occurred after 2010. This project was created for CJS' Algorithms course.

This article uses data on [incidents](https://www.phmsa.dot.gov/data-and-statistics/pipeline/source-data) and [pipeline mileage](https://www.phmsa.dot.gov/data-and-statistics/pipeline/annual-report-mileage-hazardous-liquid-or-carbon-dioxide-systems) from the Pipeline and Hazardous Materials Safety Administration (PHMSA).

## Repository contents
* Analysis folder
    * 01-clean-phmsa-data.ipynb - Selects only the columns necessary for analysis
    * 02-mileage-over-time.ipynb - Totals the mileage of pipelines for gas transmission & gathering, gas distribution and hazardous liquid
* Data folder:
    * Source folder: Raw data on pipeline incidents occurring after 2010 and pipeline mileage
    * Note: Data on mileage for each type of pipeline was only available for the following years - Gas distribution, 1984-2021; Gas transmission & gathering, 1984-2021; Hazardous liquid, 2004-2020
    * Processed folder: Outputs from Jupyter notebooks, includes clean data with columns for analysis and a dataset that contains raw incident counts by year and as a percentage of total pipeline mileage that year
* Graphics folder: