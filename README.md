# cdj_crime
1. The purpose of the project: This project analyzes the relationship between drug laws and drug-related crime across counties in New York State. Using a combination of geographic, arrest, and policy data, we explore how enforcement strategies and legislation have impacted different regions over time.
2. Installation instructions for necessary packages and libraries: To run the notebooks, make sure the following Python libraries are installed.
    import pandas as pd
    import seaborn as sns
    import duckdb
    import matplotlib.pyplot as plt
    import numpy as np
    import geopandas as gpd
    import mapclassify

    import folium
    from folium.plugins import HeatMap
    from IPython.display import IFrame
    import matplotlib.patches as mpatches

To install any missing packages, use the %pip install command in your Jupyter Notebook or terminal.

3. A step-by-step guide to reproducing the results (e.g., “First run data_cleaning.py, then model_analysis.R”): There is no strict order for running the files. Simply open and run both of the following Jupyter notebooks to reproduce the full analysis.
    data.ipynb
    opioid_info.ipynb