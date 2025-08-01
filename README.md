# NASA Data Explorer

An interactive web application that uses NASA APIs to visualize astronomy media, near-Earth objects, and exoplanet data.

## Overview

This project allows users to explore and interact with real-time data from NASA through a simple web interface. It includes the following modules:

1. **Astronomy Picture of the Day (APOD)**  
   Displays NASA’s daily featured image or video with its title and explanation.

2. **Near-Earth Object (Asteroids) Feed**  
   Allows users to input a date and view asteroid data based on proximity to Earth.

3. **Exoplanet Archive**  
   Presents a searchable, sortable table of exoplanetary systems, including details such as discovery method, orbital period, and host star.

## Features

- Real-time data fetched from NASA APIs
- Interactive user interface with API-triggered buttons
- Responsive tables powered by DataTables
- Dynamic rendering of media (image/video) and formatted scientific data
- Clickable links to NASA’s external resources

## Technologies Used

- HTML, CSS, JavaScript
- [jQuery](https://jquery.com/)
- [DataTables](https://datatables.net/)
- NASA APIs:
  - [APOD (Astronomy Picture of the Day)](https://api.nasa.gov/)
  - [NEO (Near Earth Object Web Service)](https://api.nasa.gov/)
  - [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/)

## API Acknowledgment
"This research has made use of the NASA Exoplanet Archive, which is operated by the California Institute of Technology, under contract with the National Aeronautics and Space Administration under the Exoplanet Exploration Program."
