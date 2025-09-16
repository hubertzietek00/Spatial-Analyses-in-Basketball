**Script *statbook***

The script groups CSV files generated in the *global_metrics.py* script into a single XLSX file, 
with calculated shooting efficiency metrics for all players. 
This makes it possible, for example, to sort players according to their performance in a given statistic, e.g., to identify the player with the highest PRLA or SScE value.

**Input parameters for the program**

For the program to work correctly, the appropriate input parameters must be entered in the following order:

- path to the output folder from the previous *global_metrics.py* script (e.g., *C:/Users/Desktop/output/global_metrics*),

- path to the output file in XLSX format, which will be saved in the same folder (e.g., *C:/Users/Desktop/output/global_metrics/statbook.xlsx*).
  
**Example script call**

*“C:/Users/Desktop/output/global_metrics”, “C:/Users/Desktop/output/global_metrics/statbook.xlsx”*

**Program output**

XLSX file with calculated values of global shooting efficiency metrics for each player in the output folder from script No. 4 (*global_metrics.py*)
