# Guide on Where to Fly Your Drone

## 1\. Intro

This website is intended to consolidate, into one location, all the information that someone need to operate their UAS legally and safely. In recent years, there had been a lot of confusion on what procedures the average person must follow to legally operate their UAS. With the increasing popularity of the consumer UAS's available, it was clear that the FAA needed to develop a new set of regulations to establish how the public would be allowed to operate their aircraft in proceeding forward in the future. 

This increasing popularity has also caused an increase in public concern over safety and privacy. FAA data shows that the largest concentration of registered UAS hobbyist live in urban environments. In such settings, it is very likely that there could be an incident of concern.

For both of these reasons, the FAA released their new policy on UAS operations referred to as Part 107. This website discusses these policies, provides tools to help someone find a place to fly, local clubs, and external resources to allow them to research the topic further if they so desire.  

## 2\. Data Sources

1. The template for the web design is in the Bootstrap Format and this particular template was derived from a template from [StartBootstrap.com](). While the overall flow of the website is similar to there design, the website sections and visual appearance are intended to convey a theme of UAS flying and aerial photography.

2. The data for the FAA Part 107 policies is from [FAA.gov]() and [KnowBeforeYouFly.org](). Additionally, a spreadsheet from the FAA was collected which showed how many registered recreational UAS pilots were registered in each zip code in the United States. That file was then joined with a shapefile from the Oregon Explorer Library that contained each zip code in Oregon using QGIS. The join was used in order to create a map that showed the distribution of recreational registered pilot in a respective zip code. The intent was to illustrate how the use of drones likely increases in populated areas. Once this was completed, the shapefile was then converted into a GEOJSON in order to overlay onto a basemap layer.

3. The AirMap was integrated by inserting their designated URL which contained the baselayer and additional functionality, such as the location tool and the popup data window. Next the additional coding was added to provide a link to the appropriate location if the user decides they would like to download their mobile based app.

4. The AMA map was integrated by using the code that had been previously used by [KnowBeforeYouFly.org](). Which was simply the same process as the AirMap, format the appropriate coding to pull the map and its features from the appropriate URL location.

5. Finally, the jpegs were located online at [Skypixel.com]().


## 3\. Website Functionality 

1. There is a drop-down menu thatallows the user to jump to various sections of   the page. Also, there is a chevronicon at the bottom of the window that allows the user to jump back to the top of the page.
2. On the choropleth map, the user is limited to zoom and pan functions only. 
3. The AirMap can find the user's location and will show the advisories in the area of that location. Additionally, the user can click a location and the map will show the advisories and the contact information for the area of potential conflict with the pilot. Finally, the user also can use a search function to find any particular location. 
4. The AMA club map can also hasthe ability to find the users location. This time it will show them the nearestAMA charter club to their location and will provide them with the contactinformation for that club. Additionally, the map baselayer has some airspacerestricted areas, but just not to the extent of the AirMap.
5. Finally, the website has built in hyperlink functions to external references that the user may want to investigate further. At the very bottom is the contact information.

## 4\. Problems

1. Currently, the only significantproblem with the website is the functionality of the social media sharingfunction. As of right now, the Facebook icon is sharing the wrong website andthe Twitter icon does allow you to share as well, but it does not currently automaticallyprovide a link back to map website. Both issues will be fixed shortly.
2. Layout of the text can be missaligned (margins) depending on screen size and settings. 

## 5. Other things to be Aware Of

1. The HTML file contains sections and divisions that are either copies of existing sections or are unique to themselves, but are however turn off. They are left in the code with the intention of being able to change the web site design or layout more rapidly if desired.
