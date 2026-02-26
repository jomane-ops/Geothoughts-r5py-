# Geothoughts-r5py-
## 🌍 Interactive Map.View the live accessibility map here: https://jomane-ops.github.io/Geothoughts-r5py-/bulawayo_travel_time_map.html
R⁵py is a Python toolkit for performing fast and realistic routing across multimodal transportation networks, including walking, cycling, public transit, and driving. It provides a convenient Python interface to the R⁵ routing engine, enabling efficient multimodal route computation within a streamlined workflow. The library is particularly useful in mobility analysis, logistics planning, and spatial planning, where accurate route modeling and network analysis are essential.
This GIS project applies R⁵py (Rapid Realistic Routing in Python) to model driving-based accessibility from population grid cells to key destinations within the Bulawayo Metropolitan area, Zimbabwe. While healthcare facilities serve as a primary case study, the project situates routing analysis within a broader evaluation of urban mobility systems and spatial structure.
Using a detailed road network dataset integrated into the R⁵ routing engine, the model simulates realistic vehicle routing conditions to estimate the shortest travel time between population grid centroids and service locations. Unlike simple straight-line distance measures, this network-based approach reflects actual road geometry, hierarchy, and connectivity patterns.
Beyond identifying the nearest facility based on minimum travel time, the demo could potentially provide insights into:
(1)Road network density, highlighting areas with sparse versus highly concentrated road infrastructure.
(2)Network connectivity, identifying well-connected neighborhoods versus fragmented or poorly linked zones.
(3)Spatial accessibility patterns, revealing how urban form influences mobility efficiency.
(4)Navigation efficiency, showing how road structure affects route choice and travel distribution.
By integrating routing outputs with spatial indicators, the analysis paints a broader picture of mobility dynamics in Bulawayo. It demonstrates how infrastructure configuration, road connectivity, and settlement distribution collectively shape access to essential services and overall urban functionality. The results support strategic mobility planning, infrastructure investment decisions, and long-term spatial planning aimed at improving equitable access and network resilience across the metropolitan region.
The tools used in for this implemtantion are Docker Desktop, Jupyter Notebook,QGis.
The datasets utilized are the OSM pbf,Population grid,Health facilities,GTFs,and DEM.
Libraries import r5py,geopandas,geopandas as gpd,pandas as pd,datetime,shapely.
The workflow follows this structure <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/15b018da-0496-4682-b193-994fcfef6552" />
Results are an Interactive WebGIS
