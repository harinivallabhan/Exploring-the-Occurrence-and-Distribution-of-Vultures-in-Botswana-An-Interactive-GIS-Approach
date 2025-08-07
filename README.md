
# Exploring the Occurrence and Distribution of Vultures in Botswana: An Interactive GIS Approach

## Project Overview
This project analyzes the spatial distribution and species richness of vulture populations in Botswana using biodiversity dataset from the Global Biodiversity Information Facility (GBIF). It focuses on three vulture species observed in Botswana and visualizes their occurrence pattern through an interactive 
grid-based map. The goal is to provide the biodiversity hotspots and support conservation efforts using open data. 

## Data Source 
Dataset - GBIF occurrence records for vulture species in Botswana
Format - Core Archive
Species covered - White-backed vulture (Gyps africanus), Hooded vulture (Necrosyrtes monachus) and White-headed vulture (Trigonoceps occipitalis)
Geographic scope - Botswana

## Data Licensing and Citation
License - This project uses species occurrence data from GBIF.org under the following licenses:
 - Creative Commons Attribution (CC BY) 4.0
 - Creative Commons Zero (CC0) 1.0
 - Creative Commons Attribution-NonCommercial (CC BY-NC) 4.0
The dataset includes records under multiple open data licenses as specified by individual data publishers. Please consult the license column in the dataset for specific license attribution.
Citation - GBIF.org (07 August 2025) GBIF Occurrence Download https://doi.org/10.15468/dl.dfvx4j

## Methods
 - Data filtering and cleaning to retain valid georeferenced vulture records
 - Conversion of occurrence points to spatial features (using sf in R)
 - Creation of a 0.5° × 0.5° grid over the study area
 - Calculation of species richness (number of unique vulture species) per grid cell
 - Visualization using tmap for interactive exploration of species richness and spatial distribution
 
## Tools Used
 - R Studio (with packages: sf, tmap, dplyr, readr)
 - GIS concepts and spatial analysis
 - GBIF data portal for biodiversity data

## How to Use
1. Open the interactive map (species_richness_map.html) in a modern web browser
2. Hover over grid cells to view the list of vulture species observed in that area
3. Explore species richness hotspots and spatial patterns

## Potential Applications
 - Identifying key conservation areas for vultures in Botswana
 - Supporting ecological research on species distribution and habitat use
 - Informing wildlife management and policy decisions
 
## Repository Contents
1. species_richness_map.hmtl
2. R Script
3. Dataset - occurrence.txt
4. Documentation - README.md
5. License details - Licensing_information.txt

## Author
Harini Vallabhan

