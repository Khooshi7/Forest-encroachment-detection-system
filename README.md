Forest Encroachment Detection Using Satellite Imagery (Junagadh Region)
Overview
This project focuses on detecting forest encroachment in the Junagadh region using satellite imagery and machine learning. Forest encroachment refers to the unauthorized occupation or conversion of forest land. The objective is to develop an automated, data-driven system that helps identify areas of encroachment over time using multi-temporal satellite data.

Objectives
Detect and visualize encroachment in forest areas based on satellite imagery.

Automate the process of change detection using supervised machine learning.
Focus on the Junagadh forest region for regional environmental analysis.
Use GIS tools for precise data preparation and spatial accuracy.

Tools & Technologies
Python for development and automation
PyTorch / TensorFlow for model training
OpenCV, NumPy, GDAL for image handling
QGIS for dataset generation and spatial data management
ESRI ArcGIS Online for collecting base reference data
Sentinel-2 satellite imagery as the primary input source
Matplotlib, GeoPandas for visualization and analysis

Data Collection & Preparation
Region of Interest: Junagadh forest area, Gujarat, India
Image Source: Multi-temporal Sentinel-2 satellite images

Data Collection:
Forest boundaries and reference data were collected using ESRI ArcGIS Online resources.
Dataset Generation:
QGIS was used to generate labeled datasets, extract region-specific image patches, and assign forest and non-forest labels manually based on visual changes between timeframes.

Preprocessing: Basic spatial alignment, resizing, and patch extraction were performed.

