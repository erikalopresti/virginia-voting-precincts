# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2017 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2017 Virginia November General Elections.
* Maps created in QGIS.
* Encoding: EPSG 4269
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2017](#precinct-changes-for-2017)  
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
In 2017, Virginia had 23 precincts split by Congressional district boundaries, and 138 precincts split by House of Delegates district boundaries.  This means voters at the same location could be voting in two or three different House of Delegates races.
The 2017 set of precinct shapefiles includes:
- Map of precincts including Congressional district (CD) splits. This shapefile can be used to map the results of the statewide races for Governor, Lieutenant Governor, and Attorney General, which are reported by Congressional district.
- Map of precincts including House of Delegates district (HD) splits. This shapefile can be used to map the results for the 2017 House of Delegates election.

These maps are the same as the voting precinct shapefiles, but where district boundaries split a precinct, that precinct is two separate features in the shapefile. This way, election results can be mapped by both precinct and Congressional or House of Delegates district. This is useful if one wants to compare, for example, the two-party vote share in a given  election with census demographic data such as income, race, and education rates.  
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.  
* hdPrecinct - For maps showing precincts split by House of Delegates district boundaries. Unique identifyer (House of Delegates district number concatenated with precinctID) for each precinct or precinct split portion.  
## Precinct Changes for 2017
### 13 Arlington County [1](#arlington-county)
- 12/13/2016 Consolidation of six precincts into three
	- Voters in Fillmore (26) east of Washington Boulevard moved to Arlington View (38).
	- Woodbury (41) renamed to Navy Leauge (41).
	- Arlington Mill (43) renamed to Campbell (43).
	- Courtlands (48) renamed to AUSA (48).
	- Met Park (53) created from split of Virginia Highlands (21).
	- Garfield Park (54) created from split of Lyon Park (15).
### 59 Fairfax County [2](#fairfax-county)
- 7/11/2017 - Four precincts consolidated to two, two split, one boundary adjustment.
	- Lorton Center (625) precinct consolidated into Belvoir (619) precinct.
	- Army (630) precinct created from split of Belvoir (619) precinct.
	- Gallows East (723) precinct created from split of Merrifield (721) precinct.
	- Boundary adjustment transferred some voters from Tysons (731) to Rotonda (735) precinct.
	- Newgate North (849) and Newgate South (854) precincts consolidated and renamed Newgate (849) precinct.
### 107 Loudoun County [3](#loudoun-county)
- 6/1/2017 - Two precincts split
	- Legacy (314) precinct split to create Stone Hill (320) precinct.
	- Creighton's Corner (316) precinct split to create Brambleton Middle (321) precinct.
- 7/3/2017 - Pinebrook (313) precinct split to create John Champe (319) precinct.
### 760 Richmond City [4](#richmond-city)
- 7/24/2017 - Precinct 214 created from split of Precinct 2016. Some voters from 206 transferred to 208.
## Sources
### Arlington County
Arlington County Government. Arlington County Board approves polling place, precinct changes. (December 14, 2016). Retrieved from https://newsroom.arlingtonva.us/release/arlington-county-board-approves-polling-place-precinct-changes/
### Fairfax County
Fairfax County Office of Elections. (2017, July 11). July 2017 summary of precinct and polling place changes. Retrieved from https://www.fairfaxcounty.gov/elections/sites/elections/files/assets/precincts/summary_july2017_approved.pdf
### Loudoun County
Loudoun County Administrator. (2017, October 17). Loudoun election officials notify residents of precinct changes. Retrieved from https://www.loudoun.gov/Archive/ViewFile/Item/7145
### Richmond City
Precinct 214. Richmond City Code § 9-73.1 (Ord. No. 2017-145, § 2, 9-5-2017). Retrieved from https://library.municode.com/va/richmond/codes/code_of_ordinances?nodeId=PTIICICO_CH9EL_ARTIIIPR_S9-73.1PR214
