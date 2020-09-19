# TODO
1. Settle on final project vision (DONE)
    - data viz of factors affecting covid cases worldwide
2. Plan out frontend
    - Map out the world
    - Map viz + accompanying graphs
    - Input screen and data viz dashboard UI
3. Plan out backend
4. Decide on presentation logic
    - Probably run everything on localhost to avoid deployment?
5. Create the Website

# Consider
  - What APIs can we use?
  - Fit to specific sponsor challenges (Arrow Street)

# Description
  - Data viz of factors affecting covid cases worldwide

# Technologies

*Visualization technologies*
~~D3, pure JavaScript, Google Maps API?, plot.ly,~~ Tableau

*Backend*
Python (?)

# Inspiration
 - https://devpost.com/software/openfires & https://github.com/qypeng12/USfires

# Data Sets
covid data
 - https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker
 - https://www.kaggle.com/paultimothymooney/oxford-covid19-government-response-tracker
 - https://ourworldindata.org/coronavirus
 
 stringency index
 - https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md
 
 unemployment data
 - https://data.oecd.org/emp/employment-rate.htm
 
 education data
 - https://en.unesco.org/covid19/educationresponse
 - https://www.worldbank.org/en/data/interactive/2020/03/24/world-bank-education-and-covid-19
 
 # Viz
 *over time*
 - cases vs. stringency
 - cases vs. government response 
 - cases vs. education shutdown
 - cases vs. unumployment/economic support
 *more graphs*
 - government response index, stringency, containment/health, economic (compare all the factors against each other)
 - dynamically sizing bar charts (?)
 
 # Explanation
 - Use PCA to vizualize the stringency indices based on the features
