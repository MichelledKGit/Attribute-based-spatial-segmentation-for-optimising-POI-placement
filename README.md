# Attribute-Based Spatial Segmentation for Optimising POI Placement

This repository contains the Python and R implementations supporting the research article:

**de Klerk, M. & Fabris-Rotelli, I. (2025). _Attribute based spatial segmentation for optimising POI placement_. Spatial Statistics, Article 100911.**

Article: https://www.sciencedirect.com/science/article/pii/S2211675325000338

## About the Research

This research proposes an attribute-based spatial segmentation methodology for identifying spatially accessible regions and supporting the optimal placement of Points of Interest (POIs).

The methodology uses an iterative clustering approach to create unique macro-regions based on both structural and attribute-specific characteristics. By combining a probabilistic attribute-based structure with k-means clustering, geographical regions are adaptively segmented while accounting for area-based attributes and topological relationships.

The resulting framework identifies both spatially accessible and spatially disjoint regions and provides a way to investigate the characteristics contributing to these differences. Potentially accessible regions can subsequently be evaluated to determine where additional POIs could be placed to improve accessibility.

The methodology provides a flexible framework for spatial planning and resource allocation by aligning POI placement with the structural and attribute characteristics of individual regions.

## Repository Contents

The computational implementation is provided in three components.

### 1. Attribute-Based Spatial Segmentation

The primary Python implementation for the clustering methodology, creation of macro-regions and attribute-based spatial segmentation is provided in the Jupyter Notebook:

`Python Code for chap 4 attribute segmentation.ipynb`

Supporting pipe-delimited `.txt` and shapefile (`.shp`) data are provided to allow the toy example presented in the research to be reproduced.

### 2. Temperature Estimation Using Ordinary Kriging

The R implementation used to estimate temperature values through Ordinary Kriging is provided in:

`Temperature kriging.R`

The underlying temperature data used in the full application are not publicly available and therefore cannot be included in this repository.

### 3. Spatial Autoregressive Model

The R implementation of the Spatial Autoregressive (SAR) model is provided in:

`SAR Model.R`

The underlying data used for the full application are not publicly available and therefore cannot be included in this repository.

## Data Availability

The data used for the full attribute-based spatial segmentation application for the City of Cape Town are not publicly available and therefore cannot be included in this repository.

The data supplied in this repository relate only to the synthetic toy example and are provided to demonstrate and reproduce the core segmentation methodology.

The underlying methodology and computational framework are not limited to the toy dataset and can be adapted to other geographical regions, spatial networks, attribute structures and POI placement problems where appropriate data are available.

## Methods and Tools

The repository demonstrates the computational application of:

- Attribute-based spatial segmentation
- Iterative clustering
- K-means clustering
- Probabilistic attribute-based structures
- Spatial and topological relationships
- Macro-region identification
- Point of Interest (POI) optimisation
- Ordinary Kriging
- Spatial Autoregressive (SAR) modelling
- Python-based computational analysis
- R-based spatial and statistical modelling

## Reproducibility

The repository provides the code and synthetic supporting data required to reproduce the methodological toy example presented in the associated research.

Due to data-sharing restrictions, the datasets used for the full City of Cape Town application and the associated temperature and SAR modelling cannot be made publicly available.
