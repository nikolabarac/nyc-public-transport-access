# Geo-Spatial Analysis of Accessibility to Public Transport System in New York

## Introduction

This geospatial analysis examines transportation accessibility in New York City, focusing on how different areas are connected to the public transport system. The study first analyzed accessibility at the neighborhood level and then used a hexagonal grid for a more uniform assessment.

Due to limitations in rendering interactive maps on GitHub, the interactive maps from the analysis are not visible here. However, static images of the results are included, and the code can be executed locally to generate interactive maps.

## Analysis Overview

### 1. **Neighborhood-Level Accessibility**

The analysis starts by assessing accessibility to subway, carshare, e-scooter, and bike-share stations at the neighborhood level. The goal is to understand how well different neighborhoods are connected to the public transport system.

![Neighborhood-Level Accessibility](https://github.com/nikolabarac/nyc-public-transport-access/blob/master/data/data_exploration.PNG)

### 2. **Hexagonal Grid for More Uniform Analysis**

To gain a more granular understanding of accessibility, the neighborhoods were divided into uniform hexagons using the H3 package. This allows for better insight into which specific areas have good access to public transport and which do not.

![Hexagonal Grid Analysis](data/hexagonal_analysis.png)

### 3. **Metrics and Findings**

The final analysis sums the accessibility of all transportation modes within each hexagon and its 500-meter buffer zone. These metrics are then min-max scaled for comparison.

![Hexagonal Score Map](data/hexagonal_scores.png)

### Interactive Maps

For full interactivity, you can run the provided code locally. The analysis includes interactive maps, which will help you explore the results in more detail.
