# Geospatial Analysis of the Uberaba River Basin Wildfire

## 1. Project Overview

This repository contains a detailed geospatial analysis of the wildfire that occurred on **August 19, 2024**, within the **APA Bacia Hidrográfica do Rio Uberaba** (Uberaba River Basin Environmental Protection Area) in Brazil.

The primary objective of this project was to use GIS techniques to map the extent of the fire, identify heat hotspots, and analyze probable ignition points. The final product is a technical map designed to provide critical data for post-disaster assessment and future environmental planning.

---

## 2. Final Map

![Map Preview](images/map-preview.png)

*For a full interactive experience, please download the **GeoPDF** file from the `/final_map/` directory and open it in a compatible PDF reader.*

---

## 3. Key Features & Analysis

The map was produced using remote sensing data and vector analysis in QGIS, incorporating the following key features:

* **Burn Scar Delineation:** The precise boundary of the burned area was mapped, providing a clear visualization of the fire's extent.

* **Quantitative Impact Metrics:**
    * **Total Burned Area:** 369.22 hectares
    * **Burn Scar Perimeter:** 70.62 km

* **Heat Hotspot Mapping:** All heat hotspots detected by satellite on August 19, 2024, are plotted on the map, illustrating the fire's distribution and intensity across the landscape.

* **Ignition Point Analysis:**
    * Several "Probable Initial Hotspots" are highlighted to indicate the likely origins of the fire.
    * These points are analyzed with a circular buffer to show the immediate surrounding area.

---

## 4. Technical Specifications

* **Coordinate Reference System:** SIRGAS 2000
* **Date of Fire Event:** August 19, 2024
* **Map Creation Date:** April 11, 2025
* **Software:** QGIS

---

## 5. Repository Contents

* **/final_map/:** Contains the final high-resolution map in GeoPDF format.
* **/data/:** Contains all the geospatial data (Shapefiles, GeoPackage, etc.) used in the analysis.
* **/images/:** Contains the static preview image of the map.
