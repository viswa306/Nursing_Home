
## Nursing Home Quality Analysis

## Summary:
* Goal of our project is to study Nursing Homes across United States and  focus on one of the top ten states.
* Number of Nursing homes across US
* COVID-19 deaths in Nursing Homes across US
* Display top 10 states by number of Nursing home.
* Chose Pennsylvania to do detailed analysis.

## Data Source:
* https://data.medicare.gov/data/nursing-home-compare?sort=alpha&tag=star%20ratings
* https://data.medicare.gov/data/nursing-home-compare?sort=alpha&tag=star%20ratings
* https://data.medicare.gov/data/nursing-home-compare?sort=alpha&tag=star%20ratings
* https://www.prb.org/which-us-states-are-the-oldest/

## Bash Installations required
* Python Version 3.6
* pip install gmaps
* pip install import_ipynb
 
## Requirements to run the program
* Download all the files into the local directory
* Unzip the datafiles into the Resources folder 
* Plug in Google API Key to the config.py file in the prjSource directory    
    
## Directory Structure
* Empty folder 'Output' in the root to save the output charts
* All the data files in the folder 'Resources' in the root
* All the source files in the directory prjSource
 
## Jupyter Notebooks
* The main notebook to run is 'nursing_home_main.ipynb'
* Next, run the notebook 'covid19deathanalysis.ipynb'
* Other notebooks
* Statewise - Has the functions that read and anslyse the nursing homes  across US
* pennstateanalysis  -  Has the functions that read and anslyse the nursing homes in PA
* populationanalysis -  Population anaysis Modules
* pastaffcountvsquality - Qualtiy Analysis Modules
    
## Predictions & Conclusion
As we age, daily activities tend to become more challenging, especially if chronic health conditions like diabetes,arthritis are also present.
* Based on Medicaid & Medicare services report, in US
    * 33.8% of residents in Nursing Homes were 85 to 94 Years old, 26.4% were 75 to 84 Years old and 16.5 % were 65 to 74 Years old.

* Ratio of Women vs Men living in Nursing Home is 7:3
* From our Analysis, we stronly believe that nursing homes in some states with greater populations are crowded.
* If the nursing home needs increases by 5% then the already crowded Nursing Homes are not equipped to provide the care our seniors require.
Not to mention if another pandemic like the one we are facing now strikes again.
* In the current situation we see that the nursing homes with more people show more deaths due to COVID than the ones with fewer residents.
* In Nursin Homes across US, an average of 80% Beds are Occupied leaving shortage of Beds if Needed(also if there is a Wave 2)


    



   

