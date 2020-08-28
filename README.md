# Exam project
## How can we use machine learning to predict election results in Denmark?
### Introduction to Social Data Science 2020 Summer School
This repository contains all data downloads and jupyter notebooks needed to recreate results for our exam project. Our code consists of the following notebooks:

* scraping.ipynb contains all code necessary for the scraping of KMD and mapping to municipalities.
* school_data.ipynb fetches data for school location from dingeo API and matches to data from undervisningsstatistik.dk, cleans and saves datasets.
* merge_data.ipynb merges election data, school data and socioeconomic variables together and creates the final datasets.
* plots.ipynb creates plots for the descriptive analyses.
* machine_learning2015_v3.ipynb tests machine learning models, makes predictions and generates plots for the analysis.

The data available in the folders upon downloading this repository, is mainly data,taht we ourselves downloaded from the sources listed in our report. This consists of geodata found in the folder /scrape_geodata, socioeconomic variables found in the folder /socioeconomic_data, and data for school grades found in the folder /school_data/data_download.

Because of the slow scraping process, we have also uploaded our scraped data from KMD, which can be found in the folder /scrape_geodata.  The school location data is also saved in the folder /school_data.These files can also be geenerated from the notebooks.

All plots generated are saved in the folder /plots.
