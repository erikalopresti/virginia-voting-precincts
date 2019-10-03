# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2009-2020 shapefiles 
The shapefiles in this project reflect voting precinct boundaries for Virginia primary and general elections from 2009-2020.
![image](https://user-images.githubusercontent.com/20375915/65860203-cc314c00-e337-11e9-98bb-1743428e6cc8.png)
Precinct changes prior to each election were obtained from precinct and district-level voter registration statistics, individual locality sources such as GIS data and Codes of Ordinances, and newspaper notices of precinct and polling place changes. The information was confirmed with election result and turnout data from the Virginia Department of Elections.  
- All maps were created in QGIS
- Encoding: EPSG 4269
### Attributes
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
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* hdPrecinct - For maps showing precincts split by House of Delegates district boundaries. Unique identifyer (House of Delegates district number concatenated with precinctID) for each precinct or precinct split portion.
* sdPrecinct - For maps showing precincts split by State Senate district boundaries. Unique identifyer (State Senate district number concatenated with precinctID) for each precinct or precinct split portion.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.
