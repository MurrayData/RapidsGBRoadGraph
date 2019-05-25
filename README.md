# RapidsGBRoadGraph
Example cuGraph Python Notebook for RAPIDS AI with Road Graph of Great Britain

We will be using the Ordnance Survey Open Roads dataset which has been converted into a graph.  
A sample is shown below:

![Road_Graph](./img/road_graph.png)

This is a weighted graph, using the edge distance in metres.  
__Note__: The Open Roads dataset starts with vertex ID 1 which the cuGraph analytics assume a zero-based starting ID.  
*Contains OS data © Crown copyright and database right (2019)*  
Licensed under [Open Government Licence (OGL) V3](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)

Adapted from NVIDIA cuGraph SSSP example notebook licensed under Apache License 2.0

To to run, copy the cloned archive to your Rapids Notebooks folder.

Then download the OS OpenRoads Graph [from here](https://urli.uk/1THFGU) and store the csv file in a subfolder named data.

If you want Coordinates for the nodes, both in OSGB36 Easting & Northing and WGS84 Latitude & Longitude, [download this file](https://urli.uk/C5T6UU).

If you publish any results, please [credit Ordnance Survey](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html).

# Further Reading
* [Ordnance Survey Open Roads Description](https://www.ordnancesurvey.co.uk/business-and-government/products/os-open-roads.html)
* [Ordnance Survey Open Roads Documentation](https://www.ordnancesurvey.co.uk/business-and-government/help-and-support/products/os-open-roads.html)

**_Disclaimer:_** *Not to be used for navigation purposes.*
