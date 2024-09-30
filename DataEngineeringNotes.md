Research question: Are there more accidents in areas with more Commercial or Residential building permits

ID variable is going to be Zipcodes
- Real-Time Traffic Incident Reports --> use GeoPy and Pandas (Python) to [calculate the Zipcodes in the traffic incidents dataset by using their Latitude and Longitude](https://gis.stackexchange.com/questions/352961/converting-lat-lon-to-postal-code-using-python)
- Issued Construction Permits --> Original Zip

# Variables of Interest
## Issued Contruction Permits
<li>Permit Class</li>
<li>Permit Type Desc</li>
<li>Issued Date - 2010-2024 (categorize by month; sum total permits per month)</li>
<li>Status Current - filter for rows that are active, or completed (find all unique categorical variables)</li>
<li>Number of Floors - Check how many rows are missing!</li>

## Traffic Incidents
<li>Publish Date</li>
<li>Issue Reported</li>

## Outcome Variable --> Number of traffic indcidents per zipcode
## Numerical Variables:
<li>Number of Traffic Incidents (variable will be created)</li>
<li>Number of Building Permits (variable will be created)</li>
<li>Number of Floors</li>

## Categorical Variable:
<li>Permit Class</li>
<li>Permit Type Desc</li>
<li>Issued Date</li>
<li>Status Current</li>
<li>Publish Date</li>
<li>Issue Reported</li>
