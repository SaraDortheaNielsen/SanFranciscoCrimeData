# SanFranciscoCrimeData

The san Fransisco Crime Dataset contains data on Crimes in the city of San Fransisco during the years 2013-2018.
Data are stored in *semi-colon separated* format in two files as described below.


*** sf_data.csv ***
Data on each crime reported, along with various metadata, stored under the following columns:
- id: A number which uniquely identifies each crime report
- category: A Somewhat fine-grained description, such as 'assault, 'vandalism', etc.
- description: A more fine-grained description.
- weekday: Which day of the week the crime was registered.
- date: Which date (mm/dd/yyy) the crime was reported
- time: Which time (hh:mm) the cime was reported
- resolution: The outcome of the report
- longitude: The longitude (degrees east of Greenwich) at which crime was reported
- latitude: The latitude (degrees north of equator) at which crime was reported
- label: A more general category assigned to crime types




*** sf_districts.csv ***
Some districts of interest are defined by rectangular bounding boxes in terms of latitude-longitude.
This file contains information on which crimes occurred within which such district.
Data are stored in the following columns:
- id: A number which uniquely identifies each crime report. Corresponds to the id's in sf_data.csv.
- district: The name of the district in which the crime was reported.

*** Case_sanfran.ipynb ***
Exploratory data analysis and a model.
