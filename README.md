# Road_Accident_Analysis

SUMMARY
==========================================================================================
This is a small project from the first semester, which was conducted by Lukas Niederhäuser and Daniel Podolecki.

For this analysis a data set is provided by the *"Bundesamt für Strassen ASTRA"* in Switzerland. This data set contains accidents from 2011 to 2020, including for example the severity of the accident, whether a motorcycle, pedestrian or a bicycle was included. The Analysis is done using the Programming Language R.

This analysis is focused on accidents involving bicycles as well as animals. Furthermore the data set is getting extended with the population data from the 26 cantons of Switzerland and the LV03 Coordinates of the Cantons for a geographic map of Switzerland. Lastly, we added a fictitious data set to work with missing values. We assume that AXA gave us an excel file that records the amount of damage per accident event.


DATA
==========================================================================================

Furthermore the data folder contains all the data required for the analysis. It is including
the main csv-file "RoadTrafficAccidentLocations.csv" from the Bundesamt für Strassen
ASTRA. Furthermore the excel-file "PopulationCH.xlsx" containing the population
information for each canton of Switzerland. The excel-file "Axa.xslx" is a fictive 
file containing fictional data. And the the LV03 Coordinates of the Cantons in the txt file
"LV03_Cantons.txt" for a geographic map of Switzerland added by the G1K09.shp in the seperate 
folder file_maps_CH.


USAGE 
==========================================================================================

To run the analysis it is recommended to extract the zip-folder and store all the data in
a place of your choice. In R-Studio you need to refer to the folder "data" where all
the needed data is stored. Therefore setwd () to your folder where you extracted the data 
in the zip file. 
