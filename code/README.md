This set of Python scripts is designed for automated downloading, processing, and analysis of spatial basketball shooting data. 
The scripts implement spatial metrics proposed by B.H. Pintor, enabling comprehensive spatial analysis of shooting patterns. 
Note that these tools do not include data visualization capabilities but provide outputs ready for visualization and further exploration in GIS software or other platforms.

**Required Python Libraries:**

geopandas, numpy, os, pandas, pathlib, re, requests, scipy, shapely

**Script Execution Order and Functions:**

**1. *data_collection***

Downloads and aggregates basketball shot data from FIBA LiveStats, saving it as CSV and SHP files with coordinate transformations.

**2. *empirical_bayes***

Processes the shot data and spatial grid to smooth shooting efficiency metric (Points per Attempt) using Empirical Bayes methodology.

**3. *local_metrics***

Computes local shooting efficiency metrics per player based on the Empirical Bayes output.

**4. *global_metrics***

Aggregates local metrics into global player and team performance metrics saved in Excel files.

**5. *statbook***

Combines multiple global metrics Excel files into a consolidated summary workbook.



