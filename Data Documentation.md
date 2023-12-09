
## Original Data Sources

1. **Consumer Price Index (CPI) and Unemployment Rate Data:**  
   - [U.S. Bureau of Labor Statistics Data](https://www.bls.gov/data/)
   - [Labor Force Statistics from the Current Population Survey](https://data.bls.gov/cgi-bin/surveymost)
   - [Survey Output Servlet for CPI and Unemployment Data](https://data.bls.gov/pdq/SurveyOutputServlet)

2. **SPD Crime Data:**  
   - [SPD Crime Data: 2008-Present](https://data.seattle.gov/Public-Safety/SPD-Crime-Data-2008-Present/tazs-3rd5)

3. **Income Data:**  
   - [PER CAPITA INCOME and AGGREGATE INCOME](https://data.seattle.gov/dataset/PER-CAPITA-INCOME-and-AGGREGATE-INCOME-IN-THE-PAST/bkdj-yb3f)

4. **Cartographic Boundary Files:**  
   - [U.S. Census Bureau Cartographic Boundary Files](https://www.census.gov/geographies/mapping-files/time-series/geo/cartographic-boundary.html)

## Explanation of Variables

### merged_crime:
- **Date:** Timestamp of data recording for plotting.
- **TotalCases:** The total number of reported crime incidents.
- **CPI:** A measure of the average change over time in the prices paid by urban consumers for a market basket of consumer goods and services.
- **Unemployment Rate:** The percentage of the total labor force that is jobless, actively seeking work, and available to take a job.
- **Year:** Year regarding to the number of cases.
- **Month:** Month regarding to the number of cases.

### Map_data_with_crime:
- **STATEFP:** state code of each census tract(for mapping)
- **COUNTYFP:** county code of each census tract(for mapping)
- **TRACTCE:** tract number of each census tract(for mapping)
- **GEOID.x:** GEOID of each census tract(for mapping)
- **NAMELSAD:** name of each census tract(for mapping)
- **capital_in:** capital income of each census tract
- **geometry:** geopetry factor of each census tract(polygon)

## Basic Summary Statistics

- **CPI Data:** 4 rows and 15 columns.
- **Unemployment Data:** Follows the same format as CPI data.
- **Crime Data:** Contains various columns like report number, offense ID, time duration, offense type, etc., for crimes reported each month from 2019 to 2022. There are 1085394 rows and 17 columns. There are 1082700 invalid data regarding to our project(blurred geometry data is invalid for mapping)  
- **Income Data:** 494 rows and 6 columns.
- **merged_crime:** 48 rowss, 6 total columns
- **Map_data_with_crime:** 308 rows, 17 total columns
