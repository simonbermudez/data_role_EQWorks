# data_role_EQWorks

Solution to the Work Sample Problems - Data Role technical interview

## How to use:

This script is designed to run with Python 3, please make sure that you have the following libraries installed:

- pandas
- numpy
- scipy
- folium
- webbrowser
- matplotlib
- networkx
- pprint

To run the solution script simply run `python solution.py` or `python3 solution.py` if your default version of python is not python 3.

After running the script 3 files will be created in the output folder:

- basemap.html (It is a HTML map with all the data)
- DataSample.csv (It is a CSV with all the new columns added POI and Distance)
- POIList.csv (It is a CSV of the Points of Interest with all the data added: Average, MaximumDistance, StandardDeviation, Density, Count and Popularity) 

To run the pipeline_dependency script simply run `python pipeline_dependency.py` or `python3 pipeline_dependency.py` if your default version of python is not python 3.

This script will display the Directed Acyclic Graph and the output in the terminal will display the answer to question.txt
