# About the dataset
This dataset is provided by the California Department of Forestry and Fire Protection (CAL FIRE) in collaboration with the National Interagency Fire Center (NIFC) and the Fire Integrated Real-Time Intelligence System (FIRIS).
https://www.kaggle.com/datasets/vijayveersingh/the-california-wildfire-data/data?select=b8aeb030-140d-43d2-aa29-1a80862e3d62.csv

# Disclaimer
This analyse is for my practicing and use the existing data on Kaggle.

# Citation:
CAL FIRE, "California Wildfire Perimeter Data: Real-Time Insights from FIRIS & NIFC," California Open Data Portal. Available at: https://gis.data.cnra.ca.gov/datasets/CALFIRE-Forestry::ca-perimeters-nifc-firis-public-view

# Column Descriptions

- OBJECTID: A unique identifier for each record in the dataset.
- DAMAGE: Indicates the level of fire damage to the structure (e.g., "No Damage", "Affected (1-9%)").
- STREETNUMBER: The street number of the impacted structure.
- STREETNAME: The name of the street where the impacted structure is located.
- STREETTYPE: The type of street (e.g., "Road", "Lane").
- STREETSUFFIX: Additional address information, such as apartment or building numbers (if applicable).
- CITY: The city where the impacted structure is located.
- STATE: The state abbreviation (e.g., "CA" for California).
- ZIPCODE: The postal code of the impacted structure.
- CALFIREUNIT: The CAL FIRE unit responsible for the area.
- COUNTY: The county where the impacted structure is located.
- COMMUNITY: The community or neighborhood of the structure.
- INCIDENTNAME: The name of the fire incident that impacted the structure.
- APN: The Assessor’s Parcel Number (APN) of the property.
- ASSESSEDIMPROVEDVALUE: The assessed value of the improved property (e.g., structures, not just land).
- YEARBUILT: The year the structure was built.
- SITEADDRESS: The full address of the property, including city, state, and ZIP code.
- GLOBALID: A globally unique identifier for each record.
- Latitude: The latitude coordinate of the structure’s location.
- Longitude: The longitude coordinate of the structure’s location.
- UTILITYMISCSTRUCTUREDISTANCE: The distance between the main structure and any utility or miscellaneous structures (if recorded).
- FIRENAME: An alternative or secondary name for the fire incident.
- geometry: A geospatial representation of the location in a point format (e.g., "POINT (-13585927.697 4646740.750)").

## Additional Notes:

Some columns, such as UTILITYMISCSTRUCTUREDISTANCE, may have missing values when the information could not be determined.
geometry column provides geospatial data that can be used in mapping applications for visualization.
This dataset contains a mix of categorical, numerical, and geospatial data suitable for analysis and visualization of fire-affected structures.
