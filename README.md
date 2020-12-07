# COVID-19 in Minority Counties

### Abstract 

For my personal project, I analyze how COVID-19 is affecting different races across all the counties in the United States by answering the following questions. What is the distribution of Covid-19 cases for highly minority populated counties vs. highly non-minority populated counties in the United States? What is the case gap between the worst and best counties when grouped by race? Which counties have seen the biggest improvement (drop in cases) since their biggest recorded day? Which state has the best medical response COVID-19 policies deaths vs cases?  The only question I have an educated hypothesis for is the 1st research question. My hypothesis is that there is an exponential distribution of COVID-19 deaths when sorting by the worst counties grouped by race. The other questions are hard to guage but if I had to guess for the 4th question I would say that California has had the best medical response. I found out that The distribution of COVID-19 cases looks exponential for minority counties while non-minority counties looks linear. The case gaps for minority counties are lower than non-minority counties. Only predominately white counties have seen the big improvement (drop in cases) since their biggest recorded day. No state with a large minority population has had a great medical response to COVID-19 (deaths per case)?


### Data

All data should be located in the same directoy as the jupyter notebook.

Source: [Here](https://www.census.gov/data/datasets/time-series/demo/popest/2010s-counties-detail.html)
Name: cc-est2019-alldata.csv
Description: Annual County Resident Population Estimates by Age, Sex, Race, and Hispanic Origin: April 1, 2010 to July 1, 2019

Source: [Here](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)
Name: covid_confirmed_usafacts.csv
Description: Known COVID-19 cases by county for the United States

Source: [Here](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)
Name: covid_county_population_usafacts.csv
Description: Population by county

After realizing that my data did not contain deaths, which were recorded in a seperate csv file. I downloaded the final dataset
Source: [Here](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)
Name covid_deaths_usafacts.csv
Description: Known COVID-19 deaths by county for the United States

### LICENSE

Any aggregated and properly anonymized data produced as part of the project is under CC0; <br>
All source code is under the MIT License; <br>
Any media files are under Creative Commons Attribution-ShareAlike 3.0. <br>
