# **Public Library Service Areas** 
> Do Public libraries serve to increase success in educating girls in the state of Pennsylvania?

## **Abstract**


## **Background/Rationale**
> In 2017, a book called *Drawdown* was published by the Penguin Books.  The book is a collection of 100 actions that we could take right now to stop the accummulation and reduse the amount of greenhouse gases.  One action that can be implemented right now is to Educate Girls.  Educated girls are more likely to have control of their lives, realize higher wages, greater upward mobility as well as lower maternal mortality (as well as their babies).  Education can break the cycle of poverty.  Education can provide resilience both for the individual and the environment.
>
> There are 67 counties in the State of Pennsylvania
> There are 739 public libraries across the state of Pennsylvania according to the Pennsylvania Public Library Data Collection, including bookmobiles.
>
## **Data Sources**
1. [State Outline](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=States+%28and+equivalent%29) 
1. [Pennsylvania Counties](https://www2.census.gov/geo/tiger/TIGER2020PL/STATE/42_PENNSYLVANIA/42/)
1. [Library Locations](https://pa.countingopinions.com/memberlist.php)
1. [Education Attainment](https://data.census.gov/cedsci/table?q=Educational%20Attainment&g=0400000US42.050000&tid=ACSST1Y2019.S1501&hidePreview=true)
>
## **Analysis Steps**
>
1. Gather data (state outline, county outlines, library locations, education attainment of females)
1. Trim data sets as needed
1. Create QGIS project 
1. Add vectors layers for state outline, counties, library locations
1. Use Count Points in Polylines to create a choropleth of library locations using natural breaks for catergorization
1. Create image to show the choropleth and location of libraries
1. Add delimited text layer for census data for education attainment of females per county
1. Add the areas for land and water per county and convert result from square meters to square miles
1. Join county layer with census data education attainment of females
1. Calculate the percent of females 18-24 that have not graduated high school
1. Calculate the percent of females 25 and over that do not have higher than a 9th grade education
>
## **Results and Discussion**
>
There are 739 public libraries in Pennsylvania, with at least one library in each county.

![Map Showing the location of libraries in each county](/Users/anna/Documents/ccac/DAT 241 - GIS/final_project/images/libraries as points.png "Location of Libraries in PA")

The highest concentration of libraries is in Allegheny and Philadelphia counties followed by Westmoreland, Berks, Montgomery and Delaware counties.  There are 30 counties with 6 or fewer public libraries.
>
![Map of Libraries per County](/Users/anna/Documents/ccac/DAT 241 - GIS/final_project/images/Libraries_per_County.png "Map of Libraries per County")
>
>Lancaster and Northumberland Counties have the highest percent of females that did not graduate from High School.  Lawrence, Butler, Armstrong, Cambria, Center and Adams Counties have the lowest percent of females that did not graduate from High School.
>
![Map of education attainment for females 18 to 24 without a high school diploma](/Users/anna/Documents/ccac/DAT 241 - GIS/final_project/images/per_18_24_noHS.png)
>
>Lancaster and Berks Counties have teh highest percent of females that have a 9th grade education or lower.  Allegheny, Butler, Lawrence, Cambria and Monroe counties the lowest percent of females that have a 9th grade eduction or lower.
>
![Map of females with a 9th grade education or less](/Users/anna/Documents/ccac/DAT 241 - GIS/final_project/images/per_25_9grade.png)
>

## **Conclusions**
>
There is at least one public library in every county in Pennsylvania.

## **Limitations**
>
The 2019 Census data for Education Attainment did not include data for all the counties in Pennsylvania so a comprehensive comparison could not be made.

## **Future research**
>
Several additional data that could be incorporated are data sets concerning poverty and teenage pregnancy; both could affect the outcome of education of girls in that they ccould add social environmental conditions that would prohibit girls from completing their high school education and continuing their education in institutes of higher learning.
>
Another analysis could determine if the programs that public libraries offer help 
