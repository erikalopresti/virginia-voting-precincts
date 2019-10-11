# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2019-2020 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2019 Virginia June Primary, 2019 November General, 2020 March Presidential Primary, 2020 June Primary and 2020 November General elections.

All maps were created using [QGIS](https://www.qgis.org/en/site/).  
Encoding: EPSG 4326. 
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2019](#precinct-changes-for-2019)  
[Sources](#sources)
<a name="attributes"/>
## Attributes
* precinctID - Eight digit number consisting of the county FIPS code from the US Census Bureau concatenated with the precinct code. This is a unique number for every precinct within a given election.
* precinctCo - Precinct code. Corresponds to the VTD number in US Census Bureau files.
* precinct - Precinct name.
* localityCo - Locality code.
* locality - Name of the locality (county or independent city)
* congDist - Congressional district current for the map year.
* senateDist - Senate of Virginia district current for the map year.
* hodDist - House of Delegates district current for the map year.
* actVoters - Number of active registered voters in the precinct (or split precinct portion) at the time of the election.
* preUid - PrecinctUid given in the .csv files of Individual Election Results from the Virginia Department of Elections.
* locUid - LocalityUid given in the .csv files of Individual Election Results from the Virginia Department of Elections.
* changeDate - Date of last known change to the precinct boundaries, name or number.
* lastChange - Last known change to the precinct boundaries, name or number.  
## Split Precinct Maps
In 2019, Virginia has 21 precincts split by Congressional district boundaries, 128 precincts split by State Senate district boundaries, and 136 precincts split by House of Delegates district boundaries. This means voters at the same location could be voting in two or three different House of Delegates races, or two different State Senate or US House of Representatives races.
The 2019 set of precinct shapefiles includes:
- Map of precincts including Congressional district (CD) splits. This shapefile can be used to map the results of the 2020 US House of Representatives races, as well as the 2020 statewide races for President and Vice President, and United States Senate, which are reported by Congressional district.
- Map of precincts including State Senate of district (SD) splits. This shapefile can be used to map the results for the 2019 Senate of Virginia election.
- Map of precincts including House of Delegates district (HD) splits. This shapefile can be used to map the results for the 2019 Virginia House of Delegates election.

These maps are the same as the voting precinct shapefiles, but where district boundaries split a precinct, that precinct is two separate features in the shapefile. This way, election results can be mapped by both precinct and Congressional or House of Delegates district. This is useful if one wants to compare, for example, the two-party vote share in a given  election with census demographic data such as income, race, and education rates.  
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.  
* hdPrecinct - For maps showing precincts split by House of Delegates district boundaries. Unique identifyer (House of Delegates district number concatenated with precinctID) for each precinct or precinct split portion.  
## Precinct Changes for 2019
### 19 Bedford County [1](#bedford-county)
- 5/13/2019 The Well Church (304) renamed to Riverside Church (304).
### 41 Chesterfield County [2](#chesterfield-county)
- 1/23/2019 Five new precincts created
	- Iron Bridge North (113) created from split of Iron Bridge (111).
	- Ridgedale (216) created from split of Southside (213).
	- Longhouse (314) created from split of Winfrees Store (304).
	- Magnolia (319) created from split of Skinquarter (309).
	- Clover Hill (412) created from split of Genito (402).
### 75 Goochland County [3](#goochland-county)
- 1/2/2019 Boundary adjustment transferred some voters from Centerville (402) to Shallow Well (401) precinct.
### 87 Henrico County [4](#henrico-county)
- 12/11/2018 Colonial Trail (316) created from split of Short Pump (311) precinct, all east and south of Twin Hickory Lake Dr, Liesfield Farm Dr, and North Gayton Rd.
- 1/30/2019 Part of Rolfe (514) precinct north of Northbury Ave and Old Oakland Rd split to join Sullivans (516) precinct.
### 133 Northumberland County [5](#northumberland-county)
- 12/13/2018 Precincts 3A (301) and 3B (302) merged into 3A (301).
### 153 Prince William County [6](#prince-william-county)
- 1/8/2019
	- Piney Branch (109) precinct renamed to Chris Yung (109).
	- Piney Branch (114) precinct created from split of Bristow Run (111).
	- Williams (315) precinct created from split of Potomac (302).
### 161 Roanoke County [7](#roanoke-county)
- 1/22/2019
	- Voters residing between West Main Street and I-81 moved from Green Hill (106) to Glenvar (103) precinct.
	- Lindenwood precinct (405) split into North Lindenwood (405) and South Lindenwood (401).
### 510 Alexandria City [8](#alexandria-city)
- 1/31/2019 Two new precincts and several boundary adjustments
	- Boundary adjustment moved some voters from Lyles Crouch School (103) to Lee Center (105).
	- AlexRenew (112) precinct created from split of Lee Center (105) precinct.
	- Olympus Condo (309) created from split of Charles E. Beatley Library (303) and Tucker School (304) precincts.
	- Boundary adjustment moved some voters from Cameron Station (308) to Charles E. Beatley Library (303).
### 550 Chesapeake City [9](#chesapeake-city)
- 1/22/2019 City-wide precinct reorganization
	- Waterway II (65) created from split of Waterway (49). Boundaries of Waterway (49) changed.
	- Boundaries changed for Camelot (3) and St. Julians (25).
	- Boundaries changed for Greenbrier (7), Hickory Middle School (34), Great Bridge Baptist Church (36), Bridgetown (37), Pleasant Crossing (43), and Centerville (61).
	- Green Sea (47) Precinct eliminated.
	- Boundaries changed for Bells Mill (9), Grassfield (14), Lake Drummond (39), and Shipyard Road (52).
	- River Birch (40) Precinct eliminated.
	- Boundaries changed for B. M. Williams (15), Parkways (42), Fairways (53), Green Tree (56), and Cypress (57).
	- Deep Creek II (64) created from split of Deep Creek (6). Boundaries of Deep Creek (6) changed.
	- Boundaries changed for Churchland (4), E. W. Chittum (20), Silverwood (27), and Bailey Creek (38). 
### 750 Radford City [10](#radford-city)
- 11/26/2018 New River Precinct created from split of East Precinct (001).
### 760 Richmond City [11](#richmond-city)
- 1/28/2019 Two new precincts
	- Precinct 215 created from split of Precinct 203.
	- Precinct 415 created from split of Precinct 409.
## Sources
### Bedford County
Bedford County Code art. III, § 6-42–45 (Ord. No. O051319-01, 5-13-2019). Retrieved from https://library.municode.com/va/bedford_county/codes/code_of_ordinances?nodeId=COCO_CH6EL_ARTIIIPRPOPL_DIV2PRBO
### Chesterfield County
Voting Precinct Boundaries in Chesterfield County, VA. (2019, September 18). Retrieved from http://opengeospace.chesterfield.gov/datasets/349dce35948843289e85e1a18ade455e_1
### Goochland County
Description of precincts. Goochland County Code § 2–64 (Ord. No. 3028 § 1, 1-2-19). Retrieved from https://library.municode.com/va/goochland_county/codes/code_of_ordinances?nodeId=COOR_CH2AD_ARTIIBOSUSCBOEL_DIV3PRPOPL_S2-64DEPR
### Henrico County
Henrico County GIS Office. (2019, August 26). Voting Precincts. Retrieved from https://data-henrico.opendata.arcgis.com/datasets/voting-precincts
### Northumberland County
Polling places by precinct. Northumberland County Code § 9-5 (amend. 12-13-2018). Retrieved from https://ecode360.com/7758607
### Prince William County
Prince William County GIS Office. (2019, February 13). Voting Precincts. Retrieved from https://gisdata-pwcgov.opendata.arcgis.com/datasets/voting-precincts
### Roanoke County
Roanoke County Open Data. (2019, September 20). Voting Precincts. Retrieved from https://data.roanokecountyva.gov/datasets/voting-precincts
### Alexandria City
Open Data Group for the City of Alexandria Virginia. (2019, July 25). City of Alexandria, Virginia voting precincts. Retrieved from https://cityofalexandria-alexgis.opendata.arcgis.com/datasets/voting-precincts
### Chesapeake City
City of Chesapeake. (2019). Chesapeake Precinct Changes. Retrieved from http://www.cityofchesapeake.net/government/city-departments/departments/Voter-Registrar/precincts/Chesapeake-Precinct-Changes.htm
### Radford City
Ordinance Establishing New Precinct and Polling Place (New River Precinct). (2018). Retrieved from https://www.radfordva.gov/DocumentCenter/View/3062/Ordinance-Establishing-New-Precinct-and-Polling-Place-New-River-Precinct-1707
### Richmond City
Precinct 215. Richmond City Code § 9-73.2 (Ord. No. 2019-009, § 2, 1-28-2019). Retrieved from https://library.municode.com/va/richmond/codes/code_of_ordinances?nodeId=PTIICICO_CH9EL_ARTIIIPR_S9-73.2PR215

Precinct 415. Richmond City Code § 9-90.1 (Ord. No. 2019-009, § 2, 1-28-2019). Retrieved from https://library.municode.com/va/richmond/codes/code_of_ordinances?nodeId=PTIICICO_CH9EL_ARTIIIPR_S9-90.1PR415





