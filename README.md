# Dynamic doubling-time and R0 for deaths due to COVID-19 acorss different countries and US States

The data is downloaded from [COVID-19 Data Hub on Tableau](https://www.tableau.com/covid-19-coronavirus-data-resources) which uses data compiled by JHU CSSE to report daily time series of cases and deaths. 

The methodology used by [CMMID](https://cmmid.github.io/topics/covid19/) for estimating time-varying transmission rate, doubling time, R0 using number of cases was replicated in the time-series data for deaths and calculated accordingly. Interpretation is listed below:

- *Doubling time*: The time taken by a country or state to double its cumulative death count due to COVID-19. (Ideally, we want it to increase to infinity in the long run, the more the better)

- *R0 fo death*: How many deaths are happening for a single occurrence of death? (Ideally, we want to decrease this to < 1). Death data is more reliable than cases data and this can sort of give an intuition on the current spread of disease in different countries/states.

You can view the analysis at [this link](https://ddey07.github.io/covid_live_doublingtime_deaths/)
