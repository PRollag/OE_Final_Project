# OE_Final_Project
Repository containing my final project for Introduction to Ocean Engineering & Science

Project Summary:

For this project, the following question was explored with respect to the local marine environment of Moreton Bay Research Station: Over the past decade, has there been any apparent increase in physical properties (Salinity, Temperature, Turbidity) of the local ocean, and if so, do either temperature or salinity influence turbidity as their values change, i.e. are they proportionally related?

Through the use of Jupyter Notebook, data found on the Australia Open Data Network (AODN) was gathered, analyzed, and plotted (See Plots PDF). A total of 5 plots were made, average Tempurature/Salinity/Turbidity vs. Time & average Turbidity vs. Temperature/Salinity. There was no apparent correlation for temperature vs. time, although some slight upward trend is noticable if examined closely. This may be due to the change in seasons causing the temperature to fluctuate wildly over the scale and it is likely that if the seasons were separated, there could be some amount of correlation. For salinity over time, there is some correlation with a distinct upward trend and with turbidity, there is also some amount of correlation, however the upward trend has less strength. When examining the final two plots (Turb. vs. Temp. & Salinity) there is no apparent trend that indicates any proportional relationship.

To download the data used here, directly download it from the repository or use AODN (linked below) and the following steps:
-Click "Get Ocean Data Now".
-In the "Keyword" search criteria type CTD followed by the enter key.
-Find "IMOS - Australian National Mooring Network (ANMN) - CTD Profiles" and click "Select".
-Create a subset of the data by using the bounding box function and selecting point near Moreton Bay which is the most eastern point that is shown. 
-Click "Next" to go to step 3.
-Click "Download as..." and select "CSV".
-Agree to Licence and Use Limitations and the download should automatically start.
-Use the same overall process to choose other data present in the database.

To use the code, place Final_Project.ipynb & "IMOS_-_Australian_National_Mooring_Network_(ANMN)_-_CTD_Profiles.csv" into the same folder. Open Final_Project.ipynb in Jupyter Notebook and click run, it should then automatically populate the 5 plots.

Links:
AODN: https://portal.aodn.org.au/
File Location on AODN: https://portal.aodn.org.au/search?uuid=7b901002-b1dc-46c3-89f2-b4951cedca48

