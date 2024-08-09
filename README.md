# Data Science Projects Portfolio

This repository contains a collection of data science projects that showcase various techniques and analyses in the field of data science. The projects include work on retail analysis, healthcare cost analysis, and more, using data from real-world sources.

## Project Structure
- `Walmart retail analysis/`: Contains analysis of Walmart sales data.
- `Hospital cost analysis/`: Includes a project analyzing healthcare costs.
- `README.md`: This file, providing an overview of the repository.

### Walmart Retail Analysis

This project involves analyzing historical sales data from Walmart stores to understand trends and predict future sales. The following questions were addressed:

1. **Which store has the maximum sales?**
2. **Which store has the maximum standard deviation, indicating high variability in sales?**
3. **Which stores show good quarterly growth in Q3 2012?**
4. **Which holidays have higher sales than the mean sales in a non-holiday season?**
5. **What are the monthly and semester sales trends?**

For Store 1, the following statistical models were built:
- **Linear Regression:** To predict sales using variables like date, CPI, unemployment, and fuel price.
- **Time Series Forecasting:** To predict future sales using the ARIMA model and analyze seasonality and trends.

### Healthcare Cost Analysis

This project involves analyzing hospital costs using a dataset from the US Agency for Healthcare, focusing on inpatient samples from the city of Wisconsin for patients aged 0-17 years.

**Objectives:**
1. Identify the age category of patients who frequent the hospital and have the maximum expenditure.
2. Determine the diagnosis-related group with the maximum hospitalization and expenditure.
3. Analyze whether the race of the patient is related to hospitalization costs.
4. Analyze hospital costs by age and gender for proper resource allocation.
5. Predict the length of stay based on age, gender, and race.
6. Identify the variable that primarily affects hospital costs.

## Installation
To run the projects locally, you'll need to have R and the necessary packages installed. You can install the required packages by running:
```r
install.packages(c("readr", "readxl", "data.table", "scales", "tseries", "dplyr", "ggplot2", "forecast", "tidyverse", "lubridate"))
```

## Usage
To run the analysis for the Walmart retail and Healthcare cost projects:
1. Open the `Walmart retail analysis` or Healthcare cost folder.
2. Open the `walmart retail analysis.Rmd` or `healthcare cost analysis.Rmd` file in RStudio.
3. Run the RMarkdown file to generate the analysis report.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions for improvements.

## Contact
Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/cyril-nkuna-986b25193/) or [nkunace8@gmail.com].

