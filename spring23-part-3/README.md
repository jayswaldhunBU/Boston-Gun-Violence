## Project Summary
This project aims to The goal of this project is to understand the drivers of gun violence in Boston's District 4 and compare it to the rest of the city. The project aims to determine the rate of gun violence in the district, identify patterns in terms of location and type of violence, and analyze existing programs meant to curb violence. The results of this analysis will inform policies that can be beneficial for improving the district.

The project was completed by team-4 composed of Snigdha Reddy Pulim, Patrick Wright, Tarek Mourad, Vaishnavi Vadlamudi.

### Repository Navigation
Here is the list of files and folders in the repository along with a brief description of what each file or folder contains:
#### deliverables:
##### deliverable 1:
- crime_patterns_per_PD_snigdha.ipynb: This Jupyter notebook provides analysis on the number of crimes in Boston city and per Police district in city council district 4.
- CrimeIncidentReport_Vaishnavi.ipynb: This Jupyter notebook presents analysis on crimes involving shootings in district 4, rest of the districts, and Boston city, along with comparisons.
- ReadingShapeFiles_Vaishnavi.ipynb: This Jupyter notebook showcases different shape files of Boston city and city council districts.
- gun_violence_PatW.ipynb: This Jupyter notebook utilizes the Shootings dashboard, which contains information on shooting incidents where a victim was struck by a bullet, to visualize the proportion of shootings within district 4 compared to the rest of the city.
- Field_Contacts_Data.ipynb: This Jupyter notebook analyzes the Top Zip Codes within Boston City based on the number of field interrogations, using the BPD FIELD INTERROGATION AND OBSERVATION data.

Additionally, for more detailed information on deliverable 1, you can refer to the Deliverable 1.pdf file. This PDF file provides insights, analysis, and visualizations related to the crime patterns, shootings, shape files, gun violence, and field contacts data in Boston city and city council district 4.

##### deliverable 2

code folder, along with a brief description of what each file contains:

- CrimeIncidentReport_AllYears_Vaishnavi.ipynb: This Jupyter notebook continues from "CrimeIncidentReport_Vaishnavi.ipynb" in deliverable 1 and includes analysis on the number of shootings by hour and its trend for the last 10 years.

- Field_Contacts_Data.ipynb: This Jupyter notebook continues from "Field_Contacts_Data.ipynb" in deliverable 1 and provides analysis on the trend in field contacts by months for the last 5 years.

- gun_violence_PatW.ipynb: This Jupyter notebook continues from "gun_violence_PatW.ipynb" in deliverable 1 and identifies patterns based on the days of shootings, race of the victim, and gender of the victim for the last 7 years.

- shooting_crime_patterns.ipynb: This Jupyter notebook presents analysis on the number of crimes containing shootings in Boston city and per Police district in city council district 4, focusing on data from 2019 onwards (last 5 years).

- student_discipline.ipynb: This Jupyter notebook provides analysis on Student Discipline Data for the last decade, with a focus on district 4.

Additionally, for more detailed information on deliverable 2, you can refer to the Deliverable 2.pdf file in the repository. This PDF file contains insights, visualizations, and analysis related to the code files listed above.

In addition to the aforementioned, our project is committed to broadening its scope by incorporating Environmental/Community Factors. We will specifically focus on factors such as Green Space, Tree Canopy, Community Programming, Interactions, and Pedestrian/Mobility data. By incorporating these additional factors, our project aims to provide a more comprehensive analysis of the community's environmental health and well-being, as well as its impact on mobility and access to public transit. This expansion will enhance our project's insights and contribute to urban planning and community development recommendations.

##### deliverable 3

code folder, along with a brief description of what each file contains:

- count_on_borders.ipynb: This Python code imports GeoPandas and Shapely libraries to load a shapefile of police districts and crime data in CSV format, convert the latitude and longitude columns into Shapely Point objects, loop through each police district and crime point to check if the crime point is on the police district border, and count the number of crimes on the police district borders.

- CrimeIncidentReport_AllYears_Vaishnavi.ipynb: This code is a Python script that imports the Pandas and Matplotlib libraries to read and plot data from a CSV file containing crime incident reports. The script filters the data to show the number of shootings and other crimes in different police districts, and creates a bar plot to visualize the results. It also calculates the year-on-year growth rate of reported gun crime for each year from 2015 to 2022, and prints the results to the console. Additionally, the script filters the data for two specific police districts (B2 and B3) and shows the number of shootings and other crimes in each district. Overall, this script provides a basic analysis of gun crime trends and the distribution of crime in different police districts.

- gv2.ipynb: The Python code analyzes two datasets from the city of Boston: the "Shots Fired" dataset and the "Boston Park Assets" dataset. The code aims to find a correlation between the number of parks in an area and the counts of ballistic evidence within that area. The code uses pandas for data filtering and merging, and Matplotlib to create a pie chart showing the distribution of districts with ballistic evidence. The resulting merged dataframe contains information about each park, its location, and the corresponding zip code group.

- parks.ipynb: The file describes an analysis of crime rates in different neighborhoods (police districts) in Boston and their correlation with parks and recreational areas. The analysis includes several code snippets in Python, which explore different aspects of the relationship between parks and crime, such as the number of parks per location, the number of parks per feature in Boston, and the number of shootings inside, near, and outside parks in different police districts. The analysis provides useful insights for city planners and law enforcement agencies to make informed decisions about park management and public safety.

- ReadingShapeFiles.ipynb: The code consists of several Python modules used for data analysis and visualization of crime incidents in the city of Boston. It utilizes various libraries such as geopandas, pandas, matplotlib, and folium to read and manipulate shapefiles, CSV files, and data frames, and to create maps and plots. The data is filtered to show active districts and shootings, and the locations are plotted on a map using a marker cluster. The code also adds additional markers to the map to indicate specific locations of interest. Overall, the code is designed to provide insights into crime patterns and locations in the city of Boston.

- TransportationGV.ipynb: This code snippet imports the necessary libraries such as numpy, matplotlib.pyplot, and pandas. It reads a CSV file named BTDTrafficData.csv into a pandas dataframe and then drops certain rows based on the 'Neighborhood Code' column. It also adds a new column 'Street Count' to the dataframe which counts the number of streets in each cell of the 'Associated Streets' column. It then extracts all unique street names from the 'Associated Streets' column and counts their occurrences in the dataframe, displaying the 10 most common and 10 least common streets in two separate bar graphs. Finally, it counts the occurrences of each study type in the 'Study Type' column and displays the result in a pie chart.