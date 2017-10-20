

========================================================
author: Iram Bakhtiar
date: 10-18-2017
autosize: true

Beer Market Analysis
========================================================

Intro and Scope of the Analysis
========================================================

Our Client, Best Beer Breweries wants to explore the market for new opportunities especially the market for Beer with high ABV & IBU.

Our company was tasked to see the market opportunity in different states for Beer with high ABV and IBU. We have been tracking this new trend since last year.


Breweries By State
========================================================

The analysis was designed to look at the breweries by State. The study was planned to explore the beer market in an effort to see trending and market cap changes by state. 

Colorado had the highest number of Breweries and Beer Brands in all the states, accounting for 8% of Beer brands and 11% of breweries. California was the next big market in terms of breweries operating and the beer brands in the state. Please also see the charts for a full listing of all states.

Data Provided
========================================================

The client Best Beer Breweries provided data on beers and breweries by state.

<small># Read in data for Breweries  </small>

<small>Breweries <- read.csv(file="C:/Users/DataScience/Documents/Git/BeerAndBreweriesAnalysis/DataFiles/Breweries.csv", header = T)  </small>


Data Provided Contd.
========================================================
<small># Read in data for Beer  </small>
<small>Beers <- read.csv(file="C:/Users/DataScience/Documents/Git/BeerAndBreweriesAnalysis/DataFiles/Beers.csv", header = T)   </small>

<small>#Merge Beers and Breweries df
BeersAndBreweries<-merge(Beers, Breweries,union("Brewery_id","Brewery_id"),all = TRUE) </small>

The data files were merged to have one comprehensive data pool for analysis

Data Provided Contd.
========================================================
<small>Our data teams checked the data for accuracy after merging the two datasets by extracting the first and last six rows as well as the number of N/A in each column</small>

<small>#The first 6 rows of merged df: head(BeersAndBreweries,6)</small>  
<small>#The last 6 rows of merged df: tail(BeersAndBreweries, 6)</small>  
<small>#To count number of N/A in all columns: sum(is.na(BeersAndBreweries))</small>  
Data Provided Contd.
Median ABV and IBU Content by State
========================================================
The main focus of the analysis was to find the effect of ABV and IBU content in Beers by state markets.  

<small>#Median ABV per State:
aggregate(.~State, data=MedianABVSorted, median)  </small>  

<small>#Median IBU per State
aggregate(.~State, data=MedianIBU, median)</small>  

Max ABV and IBU by State
========================================================
After looking at the data the state with the max ABV is Colorado  
<small>#Max ABV per State: aggregate(.~State, data=MedianABVSorted, max)</small>

The data showed that Oregon was the state with the maximun IBU  
<small>#Max IBU per State: aggregate(.~State, data=MedianIBU, max)</small>

Summary Statistics
========================================================
The client was also provided with Summary Statistics for ABV, in case their data scientists want more data backed findings  

<small>Summary(MedianABVSummary)</small>

Relationship Between Bitterness of Beer and Its Alcoholic Content
========================================================

The analysis shed some light on the relationship of the bitterness of beer and its alcoholic content.

Recommendations
========================================================
After conducting an in-depth analysis of the data provided by the client on the beers and breweries in all the states, we strongly recommend that the client Best Beer Breweries add two SKUs of bitter beer with higher ABV to their portfolio. Our analysis has shown that the client will be able to penetrate further the Colorado and California markets, where they already have a strong share, resulting in incremental sales.
