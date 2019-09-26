# virginia-voting-precincts
## Virginia voting precinct maps 2011-2020
The 2019-2020 maps reflect the Virginia voting precinct boundaries for the 2019 June Primary, 2019 November General, 2020 March Presidential Primary, 2020 June Primary, and 2020 November General Elections. Shapefiles will be added for all election years from 2011-2020.
![image](https://user-images.githubusercontent.com/20375915/65660713-886bd900-dffd-11e9-9900-0574487f37df.png)
* Encoding: EPSG 4269
### Attributes
* precinctID - Eight digit number consisting of the county FIPS code from the US Census Bureau concatenated with the precinct code. This is a unique number for every precinct within a given election.
* precinctCo - Precinct code. Corresponds to the VTD number in US Census Bureau files.
* precinct - Precinct name.
* localityCo - Locality code.
* locality - Name of the locality (county or independent city)
* congDist - Congressional district current for the map year.
* senateDist - Senate of Virginia district current for the map year.
* hodDist - (For maps older than 2019) House of Delegates district current for the map year.
* hodDist17 - (2019-2020 map only) House of Delegates district prior to the new district maps adopted on 29 Jan 2019.
* hodDist19 - (2019-2020 map only) House of Delegates district according to the Final Remedial plan adopted on 29 Jan 2019.
* actVoters - Number of active registered voters in the precinct (or split precinct portion) at the time of the election.
* preUid - PrecinctUid given in the .csv files of Individual Election Results from the Virginia Department of Elections. These will not be completely updated for the 2019-2020 maps until 2019 November General Election results are released.
* locUid - LocalityUid given in the .csv files of Individual Election Results from the Virginia Department of Elections.
* changeDate - Date of last known change to the precinct boundaries, name or number.
* lastChange - Last known change to the precinct boundaries, name or number.
## Split Precinct Maps
Virginia has many election precincts that are split by Congressional, State Senate, or House of Delegates district boundaries. These maps are the same as the voting precinct shapefiles, but split precincts are shown as separate features so that election results can be mapped by both precinct and district.
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* hdPrecinct - For maps showing precincts split by House of Delegates district boundaries. Unique identifyer (House of Delegates district number concatenated with precinctID) for each precinct or precinct split portion.
* sdPrecinct - For maps showing precincts split by State Senate district boundaries. Unique identifyer (State Senate district number concatenated with precinctID) for each precinct or precinct split portion.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.
