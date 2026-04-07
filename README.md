## Urban Pulse: Real-Time Traffic & Transit Desert Analysis

# Problem Statement
Mobility is essential for economic opportunity, health, and sustainability, but in many cities, access to public transit is undermined by "time poverty"—the reality that scheduled arrival times often don’t match what commuters actually experience. A bus stop might appear conveniently close on a map, yet unpredictable delays due to traffic congestion can make reliable travel impossible.

This project aims to move beyond static representations of transit networks by using Python-based data analysis to create a real-time picture of urban mobility. The goal is to demonstrate that transit access depends not just on infrastructure, but on how the system performs minute-to-minute

---

# Project Overview

This project delivers a high-performance data dashboard that identifies "Transit Deserts"—areas with dense populations but inadequate public transportation access—while also tracking real-time traffic congestion. By combining static infrastructure data with live traffic feeds, the dashboard reveals how traffic bottlenecks can turn otherwise accessible neighborhoods into “hidden” transit deserts, where public transit becomes impractical due to delays.

---

## Tools & Technologies Used
# NumPy & Pandas (The Engine)
* Data Cleaning: Handled missing GPS signals and aligned disparate datasets
* Vectorized Math: Used NumPy broadcasting to calculate distances between 10,000+ points and transit hubs instantly 
* Time Series: Analyzed "Rush Hour" patterns to predict when reliability will drop
  
# GeoPandas (The Map)
* Spatial Joins: Layered population density over 500m "walking-radius" buffers (3.4).
* CRS Management: Ensured all maps were scaled accurately for mmetric measurements (3.3).
* Spatial Overlays: Combined live traffic "clog" zones with transit stop locations (3.4).

# Matplotlib & Seaborn (The Insights)
* Heatmaps: Visualized real-time "Danger Zones" where traffic is highest (3.2).
* Subplots: Compared morning vs. evening transit reliability side-by-side (3.1).
