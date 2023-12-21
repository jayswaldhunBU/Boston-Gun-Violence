README.md



Project Overview

Welcome to the Boston Gun Violence Analysis Team-5 repository! This project aims to investigate the factors contributing to gun violence in Boston's District 4 and compare them with the rest of the city. Our team has been working diligently to analyze various aspects such as police presence, poverty, population movements, and existing programs to inform policies that can improve District 4 and reduce gun violence, especially among young individuals. This README file serves as a guide to help you navigate the repository and understand the structure of the project.

Team Members

Yuhe Bian
Peiying Ye
Hitanshi Jain
Sai Surya Varshith Nukala

Analysis Summary:

The team contributed the following work:

Yuhe Bian - Data processing, plot, and analysis for the number of incidents by Date, Year, and hour. Number of shootings per Month and Number of incidents by District and Shooting Type. Additionally, Yuhe worked on data processing, plot, and coding analysis for the relationship between attendance rate, number of absences, average number of chronically absent students, and Gun Violence rate by the district.

Peiying Ye - Data processing of separating District 4 and plotting that geographically. The analysis includes comparing District 4 with the rest of Boston in terms of shooting incidents sum, date, month, year, and period of time. Peiying also applied analysis on streetlights, to see the density of streetlights for each district, and calculated the streetlight number within 10 meters of each incident location.

Hitanshi Jain - Data processing of crime reports dataset to find Top offense codes in District 4 and plotting year-wise graphs. The analysis also includes focusing only on Gun violence offenses in District 4 and comparing the results with the rest of the city of Boston.

Sai Surya Varshith Nukala - Sai conducted an exploratory analysis of crime reports datasets to identify patterns of violence in District 4 compared to the rest of Boston, with a specific focus on gun violence. Additionally, Sai extended the analysis by creating a bar graph that displays the number of gun violence incidents within a one-mile radius of public places such as liquor stores, bus stops, open spaces (like parks, malls, etc.), T-stops, etc. Sai also integrated school dropout datasets from 2007-2022 to compare the dropout rates in District 4 with the rest of Boston and analyze the correlation between the yearly dropout rate and the number of crime reports incidents in District 4.

Repository Structure:

This repository is organized as follows:

ds-councilor-worrell-gun-violence/spring23-team-5/deliverables/deliverable 4/

Folders
crime_reports/: Contains crime reports datasets from 2015 to 2023 for the analysis of crime in District 4 and the rest of Boston.
dropout/: Holds student dropouts datasets from 2007 to 2022 for the analysis of school dropout rates and their relation to gun violence in Massachusetts.
locationscsv/: Stores various location-related CSV files used in the analysis.
locationsshapefiles/: Contains shapefiles for geospatial analysis of locations.
zipcodes_nt/: Includes zip codes shapefiles used in the analysis.

Notebooks
Further Analysis.ipynb: Analysis on Gun Violence incidents around public places.
GunViolence-Q2.ipynb: Analyzes the rate of gun violence in District 4 and compares it to the rest of the city.
GunViolence-Q3.ipynb: Examines patterns of violence in terms of location in District 4 and compares them to the rest of the city.
Streetlight Analysis.ipynb: Analyzes streetlight distribution and gun violence.
extension_analysis.ipynb: Contains the analysis of the relationship between school attendance and crime rates in different districts.
school_analysis.ipynb: Examines the relationship between school dropouts, gun violence, and offenses rate.


Usage:

Before running the code, make sure you have installed the following Python libraries:

geopandas
matplotlib
turfpy
geojson
pandas
numpy
folium
shapely
utm
pyproj
seaborn
You can install the required libraries using the following command:

pip install geopandas matplotlib turfpy geojson pandas numpy folium shapely utm pyproj seaborn

please follow these steps:

Clone the repository to your local machine:

git clone spring23-team-5/ds-councilor-worrell-gun-violence

Change to the project directory:

cd ds-councilor-worrell-gun-violence/spring23-team-5/deliverables/deliverable_4/

Open the desired Jupyter Notebook (.ipynb file) in a Jupyter environment or an IDE that supports .ipynb files (e.g., Visual Studio Code, PyCharm, etc.).
Run each cell in the notebook sequentially, making sure to execute any necessary imports or library installations. Ensure that all data files are present in the appropriate folders as described in the Repository Structure section.

