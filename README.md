# airqualityinla
Analysis of air quality trends in Los Angeles County (1987–2023) using EPA API and AQI reports.

## Project Objectives
- Examine long-term ozone pollution trends
- Compare seasonal and geographic air quality variation
- Provide easily interpretable AQI summaries
- Ensure transparent and reproducible data collection using R

## Key Features

- **Dual Data Collection**
  - Primary: EPA AQS API (ozone measurements)
  - Secondary: AQI web portal through RSelenium
  
- **Data Processing**:
  - Grouped and summarized by year, season, and city
  - Categorized AQI levels using standard thresholds
  - Wide-format transformations for multivariate comparison

- **Visual Outputs**:
  - **Figure 1**: Yearly Ozone Concentration 
  - **Figure 2**: AQI status trends over time
  - **Figure 3**: Seasonal pollutant boxplots
  - **Figure 4**: City-level comparisons 
  - **Figure 5**: Percentage of "Good" AQI Days Over Time

(*See PNG files in the data/outputs folder*)

## Technologies Used

- **Language**: R
- **Libraries**: 'httr', 'jsonlite', 'RSelenium', 'rvest', 'ggplot2', 'dplyr', 'lubridate', 'tidyr'
- **Data Source**
  - [EPA AQS API](https://aqs.epa.gov/aqsweb/documents/data_api.html#county)
  - [EPA AQI Report](https://www.epa.gov/outdoor-air-quality-data/air-quality-index-report)

## Run Instructions

- Install the required R packages
- Register for an EPA API key and input your credentials
- Configure scraping toggles and folders
- Run the script top to bottom in R or RStudio
** Full step-by-step instructions are included at the top of the R mar
