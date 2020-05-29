# california-ocean-temps

ETL 
WHAT IS THE MVP -->
get one station loaded one txt file. 
then get the second one loaded. 


EXTRACT DATA: 
data is found on this webpage: https://shorestations.ucsd.edu/shore-stations-data/
9 different stations
path to download data is:
    station page --> 3 tabs...you want the "dowload data tab" --> 2 txt files to find and link to
1. Trinidad: https://shorestations.ucsd.edu/data-trinidad/
    temp txt file
    salinity txt file
2. Farallon Islands:
    temp
    salinity
3. Pacific Grove
4. Granite Canyon
5. Santa Barbara
6. Point Dume
7. Newport Beach / Balboa
8. San Clemente
9. La Jolla / Scripps Pier

add station urls into a list
loop through list to scrape

cost to storing data in a database through AWS - usually a free tier

(efficiency optimization) code fancy, only write new records to the database 