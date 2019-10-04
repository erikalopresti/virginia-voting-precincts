# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2016 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2016 Virginia November General Elections.
* Maps created in QGIS.
* Encoding: EPSG 4269
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2016](#precinct-changes-for-2016)  
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
In 2016, Virginia had 23 precincts split by Congressional district boundaries. This means voters at the same location could be voting in two or three different House of Delegates races.
The 2016 set of precinct shapefiles includes:
- Map of precincts including Congressional district (CD) splits. This shapefile can be used to map the results of the US House of Representatives race and also the statewide races for President and Vice President, and United States Senate, which are reported by Congressional district.

These maps are the same as the voting precinct shapefiles, but where district boundaries split a precinct, that precinct is two separate features in the shapefile. This way, election results can be mapped by both precinct and Congressional or House of Delegates district. This is useful if one wants to compare, for example, the two-party vote share in a given  election with census demographic data such as income, race, and education rates.  
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.  
* hdPrecinct - For maps showing precincts split by House of Delegates district boundaries. Unique identifyer (House of Delegates district number concatenated with precinctID) for each precinct or precinct split portion.  
## Precinct Changes for 2016
### 41 Chesterfield County [1](#chesterfield-county)
- 4/13/2016 - Two new precincts created.
	- North Bird (215) precinct created from split of Bird (203) precinct.
	- West Beach (318) precinct created from split of Beach (305) precinct.
### 59 Fairfax County [2](#fairfax-county)
- 7/12/2016 - One new precinct created and one precinct renamed.
	- Terraset (225) precinct renamed to Hughes (225) precinct.
	- Rotonda (735) precinct created from split of Tysons (731) precinct.
### 95 James City County [3](#james-city-county)
- 4/12/2016 - Berkeley D (104) precinct created from split of Berkeley A (101) precinct.
### 153 Prince William County [4](#prince-william-county)
6/26/2016 - Godwin (603) precinct renamed to Hampton (603) precinct.
### 193 Westmoreland County [5](#westmoreland-county)
8/8/2016 - Two new precincts created 
	- Precinct 2-2 (202) created from split of Precinct 2-1 (201).
	- Precinct 3-2 (302) created from split of Precinct 3-1 (301).
## Sources
### Chesterfield County
Precinct boundaries and polling places. Chesterfield County Code § 7–3 (Ord. of 4-13-16 §1). Retrieved from https://library.municode.com/va/chesterfield_county/codes/code_of_ordinances?nodeId=PTIITHCO_CH7EL_S7-3PRBOPOPL
### Fairfax County
Fairfax County Office of Elections. (2016, July 12). 2016 Precinct boundary and polling place changes. Retrieved from https://www.fairfaxcounty.gov/elections/sites/elections/files/assets/precincts/summary_jul2016_approved.pdf
### James City County
Magisterial Districts, Election Districts and Election Precincts. James City Code art. II § 2-4–5 (Ord. 55A-53, 4-12-16). Retrieved from https://library.municode.com/va/james_city_county/ordinances/code_of_ordinances?nodeId=766617
### Prince William County
Prince William Board of County Supervisors. (2016, July 12). Res. No. 16 Rename Godwin Precinct to Hampton Precinct - Neabsco Magesterial District. Retrieved from https://eservice.pwcgov.org/documents/bocs/agendas/2016/0712/8-A.pdf
### 193 Westmoreland County 
Voters’ guide to Election Day in Westmoreland County. (2016, November 2). Retrieved from http://www.westmorelandnews.net/voters-guide-to-election-day-in-westmoreland-county/
