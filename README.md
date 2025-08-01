#Wildfire Analysis in an Environmental Protection Area

1. Project Overview

This repository contains the geospatial analysis of a wildfire that occurred in an Environmental Protection Area (EPA) on August 19, 2024. The main objective was to delineate the extent of the burned area, identify heat hotspots, and analyze the initial ignition points to provide accurate data for disaster management and environmental recovery planning.

The final product is a detailed technical map saved in GeoPDF format, which allows for viewing layers and attributes in compatible PDF readers.

2. Key Features and Analysis

The map was created using remote sensing techniques and vector data analysis to include the following critical attributes:

    Burn Scar (NBR Index): The exact fire area was calculated and delineated using the Normalized Burn Ratio (NBR), a robust index for identifying burned areas from satellite imagery.

    Burned Area Metrics:

        Total Area: 369.22 hectares.

        Perimeter: 70.62 kilometers.

    Heat Hotspot Mapping: All heat hotspots detected by satellite during the fire period were identified and plotted, offering a complete view of the fire's progression.

    Ignition Analysis:

        3 initial heat hotspots were highlighted, considered the likely points of origin for the fire.

        A 190-meter circular buffer was applied to each of these points to analyze the immediate impact area.

3. Map Technical Specifications

    Geodetic Datum: SIRGAS 2000 / UTM Zone 23S

    Date of Fire: August 19, 2024

    Map Creation Date: April 11, 2025

    File Format: GeoPDF

4. Tools Used

    QGIS 3.40.5: For all data analysis, image processing, and map layout.

    Satellite Data: Sentinel-2 for the NBR calculation.

    Heat Hotspot Data: INPE - National Institute for Space Research.


    Open the file in a modern PDF reader (Adobe Acrobat Reader is recommended).

    Access the layers panel to toggle the visibility of the different map features (burn scar, hotspots, buffers, etc.)
