# Mapping Earthquakes

## Project Overview

The object of this project is to gather earthquake GeoJSON data from the USGS API, then create and explore interactive maps of earthquakes around the world.
The earthquake data is represented on the maps in relation to the tectonic plates' location on the earth, and according to each event's magnitude.

## Resources:
-Data Source: Earthquake above 4.5 Magnitude GeoJSON, Tectonic Plate GeoJSON
-Software: HTML/CSS, JavaScript, Visual Studio Code, Leaflet, D3.js

## Results

### Create a Mapbox Account

In order to interact with the maps API the user has to visit www.mapbox.com, create an account and retrieve the access token. The access token will be added to a config.js file which will then be called thru index.html.

Example of config.js below:

![configex](https://user-images.githubusercontent.com/88256967/141647433-3292367d-61f0-4175-ab88-230533e667be.png)

Line of code for calling config.js within index.html

![configjs](https://user-images.githubusercontent.com/88256967/141647436-175eb190-9452-4aa6-9e86-987ec2423161.PNG)


## Interactive Map

Streets View:

![Complete Map](https://user-images.githubusercontent.com/88256967/141647455-8dbb812d-2a19-454f-b337-d59cd2c0a87e.png)

Satellite View:

![MapSateliteViewpng](https://user-images.githubusercontent.com/88256967/141647526-6cb7b32d-9be1-40e3-b931-fc00292a57e9.png)

Dark View:

![MapDarkView](https://user-images.githubusercontent.com/88256967/141647536-6cb77c57-f5f0-4c9e-8ced-d01d7a32c7bf.png)



