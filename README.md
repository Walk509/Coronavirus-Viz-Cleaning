# Coronavirus-Viz-Cleaning
Jupyter Notebooks to tidy data for analysis in Tableau.


## Coronavirus by County Dashboard


My Coronavirus project has data from the following sources:


USA FACTS - https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/
    
    Confirmed Cases - updated on a daily basis
    
    Deaths - updated on a daily basis
    
    County Population - 2019 Census will not be update
  
Kaiser Health News - https://khn.org/news/as-coronavirus-spreads-widely-millions-of-older-americans-live-in-counties-with-no-icu-beds/
    
    ICU Beds per County - Updated last on March 30th


As two of our files are updated on a regular basis I have created the USA Facts Jupyter notebook to tidy the data and save the files.
This allows me to update my dashboard in Tableau with minimum clicks.

## Top 10 Deaths by State Dashboard

The top 10 Deaths by State Dashboard uses the following sources:


USA FACTS - https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/

    Deaths - updated on a daily basis

Health Data - https://healthdata.gov/dataset/nchs-leading-causes-death-united-states

    Top 10 Deaths by state - Last update for 2017
    
As our dashboard only needs monthly data we will not update our data any more frequently. We will prep the Health Data datasource by removing unnecessary columns and adding a monthly average deaths column. We will then sum the monthly COVID-19 deaths from the USA Facts data. This will sum each months deaths by state. We will then combine the two datasets and save as a csv file.
