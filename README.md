# Forest Cover Change Detection using NDVI Differencing

## Overview

This project analyzes forest cover changes between 2000 and 2023 using satellite imagery and the Normalized Difference Vegetation Index (NDVI). The study identifies vegetation gain, vegetation loss, and unchanged forest areas through NDVI differencing and GIS-based analysis.

## Objectives

- Detect forest cover changes over time
- Generate NDVI maps from satellite imagery
- Identify vegetation gain and loss
- Visualize forest changes using GIS

## Tools Used

- QGIS
- Landsat Satellite Imagery
- NDVI Analysis
- GIS Mapping

## Technologies

- Remote Sensing
- GIS
- NDVI Differencing
- Landsat 5 TM
- Landsat 8 OLI

## Methodology

1. Satellite image acquisition
2. Image preprocessing
3. NDVI calculation
4. NDVI differencing
5. Classification of forest gain and loss
6. Visualization of results

## Results

### NDVI Map (2000)

![NDVI 2000](images/NDVI_2000.png)

### NDVI Map (2023)

![NDVI 2023](images/NDVI_2023.png)

### NDVI Difference

![NDVI Difference](images/NDVI_Difference.png)

### Forest Cover Change Map

![Forest Cover Change](images/Forest_Change_Map.png)

## Project Structure

```text
Forest-Cover-Change-Detection/
│
├── README.md
├── LICENSE
├── images/
└── Forest_Cover_Change_Report.pdf

## Data Source

- USGS Earth Explorer
- Landsat Satellite Imagery

## Future Scope

- Automate the analysis workflow using Python and GDAL.
- Apply machine learning techniques for improved land-cover classification.
- Extend the analysis using Sentinel-2 and higher-resolution satellite imagery.

## License

This project is licensed under the MIT License.
