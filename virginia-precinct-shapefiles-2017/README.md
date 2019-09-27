# virginia-voting-precincts
## Virginia voting precinct maps 2017
The 2017 maps reflect the voting precinct boundaries for the 2017 Virginia November General Elections.
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
* actVoters - Number of active registered voters in the precinct (or split precinct portion) at the time of the election.
* preUid - PrecinctUid given in the .csv files of Individual Election Results from the Virginia Department of Elections.
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
## Precinct Changes for 2017
### 59 Fairfax County
7/11/2017 - Lorton Center (625) precinct consolidated into Belvoir (619) precinct.

7/11/2017 - Army (630) precinct created from split of Belvoir (619) precinct.

7/11/2017 - Gallows East (723) precinct created from split of Merrifield (721) precinct.

7/11/2017 - Boundary adjustment transferred some voters from Tysons (731) to Rotonda (735) precinct.

7/11/2017 - Newgate North (849) and Newgate South (854) precincts consolidated and renamed Newgate (849) precinct.
### 107 Loudoun County
6/1/2017 - Legacy (314) precinct split to create Stone Hill (320) precinct.

6/1/2017 - Creighton's Corner (316) precinct split to create Brambleton Middle (321) precinct.

7/3/2017 - Pinebrook (313) precinct split to create John Champe (319) precinct.
### 760 Richmond City
7/24/2017 - Precinct 206 split to form Precinct 214 and lost some voters to Precinct 208.

7/24/2017 - Precinct 208 split and lost voters to Precinct 206.

7/24/2017 - Precinct 214 created from split of Precinct 206.
## Sources
Fairfax County Office of Elections. (2017, July 11). July 2017 summary of precinct and polling place changes. Retrieved from https://www.fairfaxcounty.gov/elections/sites/elections/files/assets/precincts/summary_july2017_approved.pdf

Loudoun County Administrator. (2017, October 17). Loudoun election officials notify residents of precinct changes. Retrieved from https://www.loudoun.gov/Archive/ViewFile/Item/7145

Richmond City Council. Precinct 214, 9-73.1 § (2017). Richmond, Virginia: Code of the City of Richmond. Retrieved from https://library.municode.com/va/richmond/codes/code_of_ordinances/308539?nodeId=PTIICICO_CH9EL_ARTIIIPR_S9-73.1PR214