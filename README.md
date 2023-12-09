# Info201_final_ADgroup5
# Crime Trends and Socioeconomic Analysis Project

## Research Methodology

This project involved a detailed variable selection focusing on total crime cases, Consumer Price Index (CPI), and Unemployment Rate for the years 2019-2022. The methodology included standardizing offense start times and merging additional socioeconomic datasets to enrich the analysis.

## Data Processing

Data conversion was performed using `mdy_hms()` for date-time standardization. The analysis involved filtering data for the relevant years and integrating it with CPI and Unemployment Rate indicators, using the `readr` package for data manipulation.

## Geospatial Mapping

To visualize geographic patterns in crime data, the `ggplot2` package and Simple Features (SF) were employed. A 1% random sample of crime data was mapped to maintain clarity and visual appeal.

![Geospatial Mapping](path_to_geospatial_mapping_image)

## Analytical Approach

The project's approach involved geospatial mapping for an enhanced data presentation. The analysis correlated crime data with economic information to unearth geographical patterns and trends.

![Analytical Approach](path_to_analytical_approach_image)

## Findings

Regression lines suggested a weak correlation between income and crime rates, while a stable linear relationship was observed between time and the unemployment rate.

![Findings](path_to_findings_image)

## Conclusion

The integration of spatial analysis with socioeconomic data offers a nuanced understanding of crime influences, providing valuable insights and a foundation for further research.
