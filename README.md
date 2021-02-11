# COVID-County-Severity-CA
COVID19 County Severity Dashboard - California

R Markdown script to create a flexdashboard with geographic data as well as charts tracking totals and per population rates for both cases and deaths, aggregated by county.

Three tabs for 1). 14-day case rate with map indicating severity by county, 2). total/rate cases, and 3). total/rate deaths.

Script combines 3 separate data sources:
  COVID Data: NYT - "https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-counties.csv"
  CA Shape Files for map: CA Open Data - "https://data.ca.gov/dataset/ca-geographic-boundaries/resource/b0007416-a325-4777-9295-368ea6b710e6"
  County Populations: Census and saved onto GitHub for public access = "https://raw.githubusercontent.com/ardomingo/COVID-County-Severity-CA/main/CA%20County%20Population.csv"
  
 Knits document into dashboard; can be distributed and opened in browser.
