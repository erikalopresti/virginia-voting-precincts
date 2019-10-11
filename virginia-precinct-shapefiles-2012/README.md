# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2012 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2012 Virginia November General Elections.

All maps were created using [QGIS](https://www.qgis.org/en/site/).  
Encoding: EPSG 4326
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2012](#precinct-changes-for-2012)  
[Sources](#sources)
<a name="attributes"/>
## Attributes
### Shapefile attributes
**precinctID** - Corresponds to the VTDID for VTDs in US Census Bureau files.  
**precinctCo** - Precinct code. Corresponds to the VTDST in US Census Bureau files.  
**precinct** - Precinct name.  
**localityCo** - Locality code. Corresponds to the COUNTYFP in US Census Bureau files.  
**locality** - Name of the locality (county or independent city).  
**congDist** - Congressional district current for the map year.  
**senateDist** - Senate of Virginia district current for the map year.  
**hodDist** - House of Delegates district current for the map year.  
**actVoters** - Number of active registered voters in the precinct and district.  
**precUid** - PrecinctUid given in the .csv files of Election Results from the VA Dept. of Elections.  
**localUid** - LocalityUid given in the .csv files of Election Results from the VA Dept. of Elections.  
**changeDate** - Date of last known change to the precinct boundaries, name or number.  
**lastChange** - Last known change to the precinct boundaries, name or number.  
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
In 2012, Virginia had 26 precincts split by Congressional district boundaries. This means voters at the same location could be voting in two different House of Representatives races.
The 2012 set of precinct shapefiles includes:
- Map of precincts including Congressional district (CD) splits. This shapefile can be used to map the results of the statewide races for Governor, Lieutenant Governor, and Attorney General, which are reported by Congressional district.

These maps are the same as the voting precinct shapefiles, but where district boundaries split a precinct, that precinct is two separate features in the shapefile. This way, election results can be mapped by both precinct and Congressional district. This is useful if one wants to compare, for example, the two-party vote share in a given  election with census demographic data such as income, race, and education rates.
### Split precinct map attributes
**distSplits** - District splits within the precinct.  
**cdPrecinct** - PrecinctID prefixed by Congressional district number.  
## Precinct Changes for 2012
### 33 Caroline County
- 2012-07-10 
	- Boundary between Bowling Green (101), Sparta (102), Milford (502) precincts adjusted.
	- Boundary between Chilesburg (601) and Lake (602) precincts adjusted.
### 107 Loudoun County
- 1/23/2012 County-wide precinct realignment
	- Dulles South (114) lost voters to Little River (107) precinct in boundary adjustment.
	- Arcola (119) precinct created from split of Mercer (108).
	- Galilee Church (219) created from split of Algonkian (208) and Countryside (213) precincts.
	- Briar Woods (312) gained portion of Pinebrook (313), and split to create Creighton's Corner (316).
	- Firehouse (315) created from split of Philomont (305).
	- Simpson (415) precinct eliminated.
	- Rehau (418) created from split of Harper Park (407) precinct.
	- J.L. Simpson (419) created from split of Evergreen (408).
	- Sterling (710) created from merger of Guilford (704) and Buchanan (706) precincts.
	- Ashburn Farm (818) split to form Broad Run (818) and Heritage Church (819) precincts.
	- Belmont Station (820) created from split of Newton-Lee (814).
	- Boundaries of Pinebrook (313), Clarkes Gap (409), Hamilton (416), Hillside (615), Eagle Ridge (616), Mill Run (618), Sully (701), Park View (702), Forest Grove (705) adjusted.
### 153 Prince William County
- 8/7/2012 Triangle (312) precinct created from split of Quantico (304).
### 680 Lynchburg City

### 710 Norfolk City
- 8/16/2011
	- Mary D. Pretlow (507) created from parts of Ocean View Center (506) and Ocean View School (102) precincts.
	- Eliminated Oceanair Precinct (508).
	- Boundaries of Ocean View Center (506) and Ocean View School precincts (102) changed after creation of Pretlow (507) precinct.
- 2/28/2012 City-wide precinct realignment
	- Titustown Precinct (104) gained voters from former Tucker House (105) precinct.
	- Old Dominion (201) gained voters from former Larchmont Recreation Center (209) precinct.
	- Willard (218) gained voters from former Lafayette Library (205) precinct.
	- Lambert's Point (207) gained voters from former Immanuel (204) precinct.
	- Sherwood (311) formed from merger of Sherwood Recreation Center (311) and Sherwood School (312) precincts.
	- Norview (309) formed from merger of Norview Methodist (308) and Norview Middle School (309) precincts.
	- Bayview School (501) renamed to Bayview (501)
	- Tucker House (105) eliminated and merged with Titustown (104)
	- Larchmont Recreation Center (209) eliminated, voters absorbed into Old Dominion (201) and Larchmont Library  (208)
	- Lafayette Library (205) eliminated and merged with Willard (218).
	- Immanuel (204) eliminated and merged with Lambert's Point (207).
	- Sherwood Recreation Center (311) and Sherwood School (312) merged to form Sherwood (311) precinct
	- Norview Methodist (308) and Norview Middle School (309) merged to form Norview (309) precinct.
### 760 Richmond City
- 3/12/2012 Amended boundaries of 34 precincts with City of Richmond Ordinance 2011-215-2012-4.
### 800 Suffolk City
- 11/16/2011 City-wide precinct realignment.
## Sources
#### Caroline County
Caroline County [Virginia] Election Districts and Precinct Boundaries. (2012, July 10). Retrieved from https://co.caroline.va.us/DocumentCenter/View/506/Election-District-Map-PDF
#### Loudoun County
Loudoun County Office of Mapping and Geographic Information. (2012, February). Election precincts [image album]. Retrieved from https://www.flickr.com/photos/omagi/albums/72157626943909849
#### Prince William County
### Falls Church City
Code of the city of Falls Church, Virginia art. II, § 2-23–25 (Ord. No. 1870, 12-12-11). Retrieved from https://library.municode.com/va/falls_church/codes/code_of_ordinances?nodeId=PTIICOOR_CH2AD_ARTIIEL
### Lynchburg City
Code of the city of Lynchburg, Virginia § 14-32–35 (Ord. No. O-11-120, 10-25-11). Retrieved from https://library.municode.com/va/lynchburg/codes/code_of_ordinances?nodeId=CH14EL_ARTIIIELPR
#### Norfolk City
Code of the city of Norfolk, Virginia §§ 14.1-68, 70–72 (Ord. No. 44,327, 8-16-11). Retrieved from https://library.municode.com/va/norfolk/codes/code_of_ordinances?nodeId=COCI_CH14.1EL_ARTIIIPRBO_DIV5WA5_S14.1-68MAD.PRLIPR
Norfolk City Code §§ § 14.1 (Ord. No. 44,568, 2-28-12). Retrieved from https://library.municode.com/va/norfolk/codes/code_of_ordinances?nodeId=COCI_CH14.1EL_ARTIIIPRBO
#### Richmond City
Code of the city of Richmond, Virginia § 30-78–149 (Code 2004, Ord. No. 2011-215-2012-4, 1-9-2012). Retrieved from ftp://ftp.ci.richmond.va.us/Redistricting2011/ExhibitB/Certified%20Ordinance%20No%20%202011-215-2012-4.pdf
#### Suffolk City
Code of the city of Suffolk, Virginia §26-2 (Ord. No. 11-O-100, § 1, 11-16-2011). Retrieved from https://library.municode.com/va/suffolk/codes/code_of_ordinances?nodeId=PTIICO_CH26EL_S26-2PRBOBO
