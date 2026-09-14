# Flood Extent Map: Mororo and Garissa Town (April 29, 2024)

###  [ Click Here to View the Interactive Map ](https://github.io)

## Project Overview
This repository hosts an interactive web map documenting the severe flood extent in Mororo and Garissa Town observed on April 29, 2024. Generated using QGIS from Sentinel-2 satellite imagery and hosted via GitHub Pages.

During this period, heavy rainfall triggered catastrophic flooding along the Tana River basin, deeply impacting infrastructure, displacing residents, and submerging communities across Garissa and neighboring Mororo. This map serves as an open-access resource for spatial analysis, historical documentation, and flood risk assessment.

## Data Source & Methodology
- Satellite Data: Copernicus Sentinel-2 (Optical Imagery).
- Acquisition Date: April 29, 2024, 07:26 UTC.
- Methodology: The flood extent boundaries were extracted by calculating water indices (NDWI) and applying threshold classifications in QGIS to isolate open water surfaces from vegetation and urban areas.

## Technical Stack
- GIS Desktop Software: QGIS
- Web Export Engine: qgis2web plugin (Leaflet framework)
- Hosting: GitHub Pages (Static Web Hosting)

## Map Features & Interactivity
- Pan & Zoom: Seamlessly explore the affected geographical areas of Garissa and Mororo.
- Layer Control: Use the interactive menu to toggle the flood extent layer on and off over the basemap.
- Data Attributes: Click on flood zones to view specific attribute information embedded from the QGIS layers.

## Repository Structure
- 'index.html': The core webpage layout for the web map.
- '/layers/': Contains the exported spatial vector shapes of the flood boundary.
- '/css/' & '/js/': Styling and scripting assets generated automatically by 'qgis2web'.

## License & Usage
This data is made available for informational, educational, and disaster response analysis purposes. Sentinel-2 data is provided courtesy of the European Space Agency (ESA).
