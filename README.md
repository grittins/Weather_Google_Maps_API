# World_Weather_Analysis

## Resources
- Software: Jupyter Notebook

- Google Maps API 

## Overview 

A set of random latitutde and longitude combinations is generated with a size of 1500. Out of 1500, 622 coordinates were located as their nearest cities. A Google Maps API request was run for each cities and the following information was fetched and converted into a data frame. 

<img width="743" alt="Screen Shot 2022-11-09 at 1 47 59 AM" src="https://user-images.githubusercontent.com/104872971/200758971-fd7608f8-56bb-432c-906d-f43e68a87f1e.png">

### Plots 

From the information, the following graphs were plotted: 

<img width="406" alt="Screen Shot 2022-11-09 at 1 50 33 AM" src="https://user-images.githubusercontent.com/104872971/200759313-c149eb1f-fef1-4405-8462-75cfcdab4eae.png">

<img width="404" alt="Screen Shot 2022-11-09 at 1 50 51 AM" src="https://user-images.githubusercontent.com/104872971/200759355-66a24b67-bc4e-4733-aa3d-11a6606d60dc.png">

<img width="409" alt="Screen Shot 2022-11-09 at 1 51 07 AM" src="https://user-images.githubusercontent.com/104872971/200759396-297b00cb-2a9c-4f5b-ad03-378b4acdf6b2.png">

<img width="407" alt="Screen Shot 2022-11-09 at 1 51 21 AM" src="https://user-images.githubusercontent.com/104872971/200759442-1aa0a64d-a6fe-49b1-8b22-955c08b2a548.png">

## Linear Regression
Linear regression was used to find the relationship between some variables. All of them can be seen on WeatherPy.ipynb file. Some of them are as follows: 

<img width="920" alt="Screen Shot 2022-11-09 at 2 00 55 AM" src="https://user-images.githubusercontent.com/104872971/200761235-241ee675-7570-4aa4-8f40-1f31632f70b8.png">

<img width="586" alt="Screen Shot 2022-11-09 at 2 01 48 AM" src="https://user-images.githubusercontent.com/104872971/200761343-4b3143f9-735f-4be6-b5f3-bb8f5bd03137.png">

### Vacation Search
From the Weather Database created the user can ask for the desired maximum and minimum temperature. A Google Map is shown to the user with the location, hotel name and current weather conditon. 

<img width="1056" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/104872971/200762316-67db1e5f-702f-4f71-84e9-7e1cf8a033da.png">

### Vacation Itenary

After vacation search is completed, the user chose 4 locations to visit as shown below: 

<img width="1440" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/104872971/200764222-720336f0-d811-4911-89e8-357136a8330b.png">

Again, with the help of Google Maps API, an itenary is created by drawing a direction layer for the locations chosen by the user. 

<img width="1414" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/104872971/200764349-4dc0dc72-9b4a-47b5-8bc8-1edd96f75cfb.png">

