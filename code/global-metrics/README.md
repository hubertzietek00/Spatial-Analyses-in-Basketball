**Script *global_metrics***

The script allows you to calculate global versions of spatial metrics from the *local_metrics.py* script, 
which determine the overall shooting efficiency of players based on all their shots. 
The script requires CSV files with calculated local spatial metrics for individual players, created in the *local_metrics.py* script.

**Input parameters for the program**

For the program to work correctly, the following input parameters must be entered in the following order:

- path to the folder with CSV files containing the calculated local metrics for individual players. The path is specified as the output folder when entering input parameters in the previous *local_metrics.py* script (e.g., *C:/Users/Desktop/output/local_metrics*)

- path to the output folder where the calculated global metrics will be located (e.g., *C:/Users/Desktop/output/global_metrics*).

**Example script call**

*“C:/Users/Desktop/output/local_metrics”, “C:/Users/Desktop/output/global_metrics”*

**Program output**

The program will save the output data in a folder with files in CSV format, 
defined when entering the input parameters to the script (e.g., *C:/Users/Desktop/output/global_metrics*). 
For each competitor from the output folder from script No. 3 *local_metrics.py*, the following metrics are calculated:

- EPPA – Expected Points per Attempt

- PPA – Points per Attempt

- SScE – Spatial Scoring Effectiveness

- PRLA – Points Relative to League Average

As well as traditional statistics:

- FG% - Field Goal Percentage

- 2FG% - 2-point Field Goal Percentage

- 3FG% - 3-point Field Goal Percentage

- eFG% - Effective Field Goal Percentage

**The metrics are sourced from the benhur07b's repository available on GitHub (https://github.com/benhur07b/ms-thesis-spatial-analysis-shooting-philippine-basketball).**
