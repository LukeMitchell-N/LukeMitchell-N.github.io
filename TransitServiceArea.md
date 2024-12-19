# Portland Transit Service Area Tool

QGIS tool and script to generate a service area layer using public transportation   

# About

This is a QGIS tool that allows for the user to select a point within an hour's walk of Trimet's bus and rail network and it will return the area that is reachable within a set time limit from that location using the optimal combination of walking and public transit. 
<br>
The tool was written in Python and returns three layers representing the sections of the street network that can be reached, the transit network that can be reached, and the polygon that contains the city blocks that can be reached within the set time constraint.
<br>
# Script Details
To create the script I used publicly available GIS data from trimet that included their routes and stop locations. 
I obtained and cleaned a spreadsheet contaiing departure times for each route from each stop to create average velocities and time between departures for each line. This information is used to generate a service area.
<br>
<img src="images/TransitServiceAreaFlowchart.png"/>


## [Repository](https://github.com/LukeMitchell-N/PortlandTransitIsochrone)

## Image Gallery
<img src="images/Skatepark Accessibility.png"/>
