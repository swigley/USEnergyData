##US Energy Data##
After searching data.gov for a while looking for something interesting to include in my project, I finalaly found a dataset on energy production by state at the US Energy Information Administration site.  It had the kind of data I was looking for, and since it had yearly data by state, I thought it would be well suited to use a map and animate the visualization over time.

After spending some time with the data, it became clear that looking at only energy production for each state didn't give a lot of perspective.  One issue is larger states, like California completely overshadowed smaller states because the imbalance between their energy production is so great.  It was clear there needed to be some ratio to make the comparisons between states make sense.  

I found a dataset showing US population by state for the same time period, 1990 - 2014, on the US Census website.  I also found a dataset on the US Dept. of Commerce Bureau of Economic Analysis website that showed GDP by state for the same time period.  I decided to join both of these datasets by state and year to the energy dataset to compare energy production by state per capita, or energy by state per dollar GDP.


##Feedback##

Elizabeth C. 
"I think it would be better to show both factors in the ratio in separate charts when viewing the state chart to make it more clear which one causes the value to going up or down."

Enhancement:  
	I changed the chart that is displayed when clicking an individual state to show three charts instead of one.  The main chart still shows the ratio between energy source and the selected units for the state (Population, GDP, Percent of total), and for the whole US, but also shows two charts below to show the two factors that make up the ratio in separate charts.

Aaron W.
"Looking at these ratios is a little unclear.  I'd like to better be able to understand the units I'm looking at here."

Enhancement:
	When I demonstrated the visualization for Aaron, the chart named the ratio selections 'Numerator' and 'Denominator', and didn't preset the values as specific units, but just a relative number which was calculated by literally dividing the value selected as 'Numerator' by the value selected as 'Denominator' and displaying the states relative to each other, without really defining what the values mean.
	
	I changed the labels for the numerator and denominator to 'Source' and 'Units' and defined what those units actually mean in terms of Megawatthours produced per person or dollar.  For the percent of US Total option, I covert the ratio value, which is between 0 and 1 to a percentage so that it is easier to conceptualize.

Kevin P.
"I think the story should be something along the lines of how is my state doing in terms of reducing energy sources that contribute to environmental impact."



##Data Sources##
* https://www.eia.gov/electricity/data/state/
* https://www.census.gov/popest/data/historical/index.html
* http://www.bea.gov/regional/downloadzip.cfm

##References##
* http://stackoverflow.com/questions/10784018/how-can-i-remove-or-replace-svg-content
* http://jsfiddle.net/farrukhsubhani/S6FLv/7/
* http://stackoverflow.com/questions/20905429/update-dimple-js-chart-when-select-a-new-option
* http://dimplejs.org/
* http://stackoverflow.com/questions/22988109/dimple-js-measure-axis-values
* http://dimplejs.org/advanced_examples_viewer.html?id=advanced_custom_styling
* http://stackoverflow.com/questions/23291200/dimple-js-how-can-i-change-the-labels-of-a-chart-axis-without-changing-the-data
* http://bl.ocks.org/timelyportfolio/db285de282e9a47f5bed
* http://stackoverflow.com/questions/24369718/change-categoryaxis-to-measureaxis-with-dimple
* http://napitupulu-jon.appspot.com/posts/dimple-ud507.html
* http://stackoverflow.com/questions/14742538/running-d3-timer-on-intervals
* https://github.com/d3/d3-timer
* http://bl.ocks.org/cloudshapes/5662234
* http://www.pdiniz.com/using-d3s-timer-method/
* https://github.com/d3/d3/wiki/time-intervals
* http://grokbase.com/t/gg/d3-js/143bcmmmxd/populate-and-handle-dropdown-list-within-d3-js-html-foreignobject
* http://bl.ocks.org/jfreels/6734245
* https://codedump.io/share/Kw3ED6wbDFi/1/how-to-set-default-option-d3js
* http://stackoverflow.com/questions/18883675/d3-js-get-value-of-selected-option
* http://www.d3noob.org/2013/02/update-d3js-data-dynamically-button.html
* http://www.jeromecukier.net/blog/2011/08/11/d3-scales-and-color/
* http://alignedleft.com/tutorials/d3/using-your-data
* http://www.stator-afm.com/tutorial/d3-js-mouse-events/
* http://bl.ocks.org/Caged/6476579
* http://bl.ocks.org/d3noob/a22c42db65eb00d4e369
* http://bl.ocks.org/mapsam/6195407
* http://bl.ocks.org/mpmckenna8/b152a067884caacd02b4
* http://eyeseast.github.io/visible-data/2013/08/27/responsive-legends-with-d3/
* http://www.w3schools.com/jsref/prop_win_innerheight.asp
