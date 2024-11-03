Dataset Description 
Overview 
The dataset provided contains historical rental price data for various districts in Singapore, dating back to 2018. It includes variables such as property type, address, median rental price, and other relevant features. Participants are encouraged to use additional data sources, if needed, to improve their forecasting models 
 
train.csv / test.csv 
property_key: unique property key 
The granularity of the property is determined by a combination of factors, including the condo name, district, street, the type of property, the number of bedrooms, and the size of the property in square meters.


contractDate: year and month of contract 
The date of the contract is provided with a time granularity of month, and the day of each month is fixed at 1.


price: transaction price of each property key 
From the raw data, if there were multiple contract prices for the same property key, the median value was calculated and used. However, if there was a unique contract for a given date, the actual contract price was utilised.

 Source: Urban Development Authority (URA)


properties.csv
area: the land/floor area of the transacted unit in square metre
floorRange: the floor range
district: the postal district
typeOfArea: the type of area of the transacted unit
tenure: the tenure of the transacted property
street: the street name that the project is on
project: the name of the project
marketSegment: the market segment that property falls in
property_key: property key

 Source: Urban Development Authority (URA)
 
geo_attributes.csv 
This file contains the latitude and longitude values for each project and a number of important points of interest around the geocode. 
lat: the latitude of a project
lng: the longitude of a project
planning_area: planning area that a project belongs to 
num_schools_1km: the number of schools in 1km radius of a project
num_supermarkets_500m: the number of supermarkets in 500m radius of a project
num_mrt_stations_500m: the number of MRT stations in 500m radius of a project

  Source: OneMap


rentIndex.csv
This file includes the rental index for both landed and non-landed residential properties from Q1 2018 to Q4 2022. The rental price index uses 2019 1Q as the base quarter for comparisons
Source: Urban Development Authority (URA)
 
cpi.csv 
This file includes the Consumer Price Index (CPI) for all item categories, which tracks the average change in prices for groups of goods and services bought by households. It's commonly used to measure consumer price inflation. The CPI uses 2019 as the base year for comparisons in the index.
Source: Singapore Department of Statistics


interest.csv 
This file contains 12-month fixed deposit rate which is complied from all leading finance companies in Singapore. 
Source: Monetary Authority of Singapore


vacant.csv
The file contains the number of available and empty executive condominium units. 
available: Completed units ready for occupation, including both occupied and unoccupied units. Data covers all completed executive condominiums with a temporary occupation permit, or a certificate of statutory completion. 
vacant: Available units that are not currently occupied 

Source: Urban Development Authority (URA)




