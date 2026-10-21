# Florida Uninsured Rates: Time Series Analysis (2008–2022)

## Project Overview

This project analyzes annual uninsured percentages in Miami-Dade and Bradford counties, Florida, from 2008 to 2022. The goal is to explore historical trends, assess stationarity, apply ARIMA time series models, and forecast uninsured percentages over the following five years.

## Tools and Methods

- **R and RStudio** for statistical analysis
- **ARIMA modeling** for time series forecasting
- **Stationarity testing** to assess time series properties
- **Cross-correlation analysis** to explore relationships between counties
- **Data visualization** to present historical trends and forecasts

## Key Findings

- Both counties experienced substantial declines in uninsured percentages over the study period, although their year-to-year patterns differed.
- The portfolio analysis selected ARIMA(0,1,0) for Miami-Dade and ARIMA(0,1,1) for Bradford.
- Five-year forecasts were generated for 2023–2027.
- Cross-correlation was explored, but it does not establish a causal relationship between the counties.

## Data Source

U.S. Census Bureau Small Area Health Insurance Estimates (SAHIE), covering 2008–2022.

The portfolio dataset combines cleaned observations for 2008–2021 with 2022 values transcribed from the original project report appendix.

## Project Files

- `sahie_analysis.Rmd` — R Markdown source code and explanations
- `sahie_analysis.html` — completed analysis report with charts and results
- `Clean_df_sahie.xlsx` — cleaned Excel dataset
- `data/florida_uninsured_2008_2022.csv` — CSV dataset used by the R Markdown analysis

## Limitations

The analysis uses only 15 annual observations per county, so forecasts should be interpreted cautiously. Forecasts are estimates rather than observed uninsured rates.

## Skills Demonstrated

Data preparation, exploratory data analysis, time series modeling, statistical interpretation, forecasting, and reproducible reporting in R.
