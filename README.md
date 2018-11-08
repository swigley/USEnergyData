## US Energy Data  
After searching data.gov for a while looking for something interesting to include in my project, I finalaly found a dataset on energy production by state at the US Energy Information Administration site.  It had the kind of data I was looking for, and since it had yearly data by state, I thought it would be well suited to use a map and animate the visualization over time.

After spending some time with the data, it became clear that looking at only energy production for each state didn't give a lot of perspective.  One issue is larger states, like California completely overshadowed smaller states because the imbalance between their energy production is so great.  It was clear there needed to be some ratio to make the comparisons between states make sense.  

I found a dataset showing US population by state for the same time period, 1990 - 2014, on the US Census website.  I also found a dataset on the US Dept. of Commerce Bureau of Economic Analysis website that showed GDP by state for the same time period.  I decided to join both of these datasets by state and year to the energy dataset to compare energy production by state per capita, or energy by state per dollar GDP.


## Data Sources
* https://www.eia.gov/electricity/data/state/
* https://www.census.gov/popest/data/historical/index.html
* http://www.bea.gov/regional/downloadzip.cfm


