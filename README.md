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
