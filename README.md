# Flood & Rainfall map
## Introduction
This website has been developed for the 2024 NASA Space Apps Challenge, under the project title **'Landsat Reflectance Data: On the Fly and at Your Fingertips
'** In this project, we create a tool for flood forecasting and prevention, protecting communities and minimizing damages.

The website has four main sections, including an **interactive map**, an **introduction**, an **analysis**, and a **reference** page.

Team Member: 


## Different pages

### 1. Interactive map
This is the main page. The interactive map includes layer design, which are 2 basemaps ( OpenStreetMap & Satellite ), 3 research analysis layers ( NDVI, NDWI & NDMI ), the final 2 band results ( 381-2492 band z score & 700-1400nm z score ) and 2 optional layers ( hotspots & Cape area ).

### 2. Introduction

The introduction page mainly presents the EMIT data used and our main research area - the Cape area.

### 3. Analysis

The analysis page primarily showcases our progression from the initial raw data, through the pre-processing steps, to the methodologies we employ, ultimately culminating in the presentation of our results.

### 4. Reference

Reference materials include data sources, websites and papers.

## Analysis process code
Regarding our analysis process, the relevant programs will be placed in ```/AnalysisProcess```.

* ```emit_tools.py``` is the module provided by NASA for orthophoto processing.

* ```Demo-checkpoint.ipynb``` is the code for our data analysis.
