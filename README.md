## Urban Pulse: Real-Time Traffic & Transit Desert Analysis

# Problem Statement
Mobility is essential for economic opportunity, health, and sustainability, but in many cities, access to public transit is undermined by "time poverty"—the reality that scheduled arrival times often don’t match what commuters actually experience. A bus stop might appear conveniently close on a map, yet unpredictable delays due to traffic congestion can make reliable travel impossible.

This project aims to move beyond static representations of transit networks by using Python-based data analysis to create a real-time picture of urban mobility. The goal is to demonstrate that transit access depends not just on infrastructure, but on how the system performs minute-to-minute

---

# Project Overview

This project delivers a high-performance data dashboard that identifies "Transit Deserts"—areas with dense populations but inadequate public transportation access—while also tracking real-time traffic congestion. By combining static infrastructure data with live traffic feeds, the dashboard reveals how traffic bottlenecks can turn otherwise accessible neighborhoods into “hidden” transit deserts, where public transit becomes impractical due to delays.

---

## Tools & Technologies Used
# NumPy & Pandas — Data Processing Engine
* Data Cleaning: Addressed missing GPS data and harmonized multiple datasets for consistent analysis.
* Efficient Computation: Employed NumPy’s vectorized operations to quickly compute distances between over 10,000 locations and transit hubs.
* Time Series Analysis: Leveraged Pandas to examine rush hour trends and forecast periods of decreased transit reliability.

# GeoPandas — Spatial Analysis & Mapping
* Spatial Joins: Mapped population density within 500-meter walkable buffers around transit stops to highlight areas of concern.
* Coordinate Reference Systems (CRS): Standardized map projections to ensure accurate metric-based measurements across all spatial data.
* Spatial Overlays: Integrated live traffic congestion data with transit infrastructure to identify zones where delays render transit inaccessible.

# Matplotlib & Seaborn — Visualization & Insights
* Heatmaps: Illustrated real-time congestion “danger zones,” spotlighting areas of critical traffic buildup.
* Comparative Subplots: Enabled side-by-side visualization of transit reliability during different times of day, such as morning and evening rush hours, to reveal temporal patterns and bottlenecks.

---

## Project Workflow

1. Static Mapping: Loading city boundaries and transit stop coordinates 
2. Desert Analysis: Identifying high-population areas with zero transit access 
3. Live Ingestion: Pulling real-time traffic speeds via API 
4. Reliability Scoring: Calculating the "Transit Reliability Index" (Scheduled vs. Actual)

## Key Features

* Live Transit Desert Map: Updates to show which areas are currently "cut off."
* Real-Time Congestion Tracker: Overlays live traffic speeds onto the transit grid.
* The Reliability Index: A score for every neighborhood based on actual commute times.
* Bottleneck Heatmaps: Identifies the exact intersections causing city-wide delays.

---

## Data Sources

This project integrates high-quality datasets to model both static transit accessibility and real-time traffic conditions.

# Real-Time Traffic
* HERE Technologies – Real-time traffic flow, congestion levels, and incident data used to dynamically adjust travel times.
  
# Public Transport
* Digital Matatus Project – Primary dataset for Nairobi matatu routes and stops (GTFS-like structure), enabling accurate transit mapping in the absence of official feeds.
  
# Population Density
* WorldPop – High-resolution population grids used to identify high-density underserved areas.

# Road Network
* OpenStreetMap – Road networks and geographic features, accessed via OSMnx for spatial analysis.

---

## Key Insights 



Author
Nigel Mirambo
Python Data Analysis Capstone
