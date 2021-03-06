# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2013 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2013 Virginia November General Elections.

All maps were created using [QGIS](https://www.qgis.org/en/site/).  
Encoding: EPSG 4326. 
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2013](#precinct-changes-for-2013)  
[Sources](#sources)
<a name="attributes"/>
## Attributes
### Shapefile attributes
`precinctID` - Corresponds to the VTDID for VTDs in US Census Bureau files.  
`precinctCo` - Precinct code. Corresponds to the VTDST in US Census Bureau files.  
`precinct` - Precinct name.  
`localityCo` - Locality code. Corresponds to the COUNTYFP in US Census Bureau files.  
`locality` - Name of the locality (county or independent city).  
`congDist` - Congressional district current for the map year.  
`senateDist` - Senate of Virginia district current for the map year.  
`hodDist` - House of Delegates district current for the map year.  
`actVoters` - Number of active registered voters in the precinct and district.  
`precUid` - PrecinctUid given in the .csv files of Election Results from the VA Dept. of Elections.  
`localUid` - LocalityUid given in the .csv files of Election Results from the VA Dept. of Elections.  
`changeDate` - Date of last known change to the precinct boundaries, name or number.  
`lastChange` - Last known change to the precinct boundaries, name or number.  
## Split Precinct Maps
In 2013, Virginia had 23 precincts split by Congressional district boundaries, and 130 precincts split by House of Delegates district boundaries.  This means voters at the same location could be voting in two or three different House of Delegates races.
The 2013 set of precinct shapefiles includes:

`va_precincts_2013_split_by_CD` - Map of precincts including Congressional district (CD) splits. This shapefile can be used to map the results of the statewide races for Governor, Lieutenant Governor, and Attorney General, which are reported by Congressional district.  
`va_precincts_2013_split_by_HD` - Map of precincts including House of Delegates district (HD) splits. This shapefile can be used to map the results for the 2013 House of Delegates election.

These maps are the same as the voting precinct shapefiles, but where district boundaries split a precinct, that precinct is two separate features in the shapefile. This way, election results can be mapped by both precinct and Congressional or House of Delegates district. This is useful if one wants to compare, for example, the two-party vote share in a given  election with census demographic data such as income, race, and education rates.  
### Split precinct map attributes
`distSplits` - District splits within the precinct.  
`cdPrecinct` - PrecinctID prefixed by Congressional district number.  
`hdPrecinct` - PrecinctID prefixed by House of Delegates district number.
## Precinct Changes for 2013
### 19 Bedford County [1](#bedford-county)
- 8/26/2013 County-wide precinct reorganization after Bedford City ended its independent city status and became part of Bedford County.
### 41 Chesterfield County [2](#chesterfield-county)
- 5/22/2013 Midlothian North (518) created from split of Midlothian (503).
### 51 Dickenson County [3](#dickenson-county)
- 3/26/2013 Consolidation of six precincts into three
	- Longs Fork (304) precinct merged with Ridge (303).
	- Colley (401) and Haysi (402) consolidated precincts and named Haysi-Colley (401).
	- Artrip (502) precinct merged with North Clintwood (503).
### 59 Fairfax County [4](#fairfax-county)
- 7/9/2013 One precinct created, one precinct renamed, boundary adjustment
	- Plaza (509) precinct created from split of Skyline (520).
	- Boundary adjustment transferred some voters from Saratoga (626) precinct to Alban (623).
	- Dulles (904) precinct renamed to Stonecroft (904).
### 75 Goochland County [5](#goochland-county)
- 4/26/2013 Shallow Well (401) precinct created from split of Centerville (402).
### 105 Lee County [6](#lee-county)
- 3/19/2013 Consolidation of six precincts into three
	- North Jonesville (203) and South Jonesville (204) precincts consolidated and named Jonesville (203).
	- West Pennington (302) precinct merged with Ben Hur (301).
	- Stone Creek (502) precinct merged with St. Charles (501).
	- East Pennington (503) precinct renamed to to Pennington Gap (502).
### 107 Loudoun County [7](#loudoun-county)
- 4/17/2013 Two precincts created and one eliminated.
	- Rehau (418) precinct merged with Harper Park (407).
	- Moorefiled Station (624) precinct created from split of Mill Run (618).
	- Lansdowne (821) precinct created from split of Belmont Ridge (815).
### 109 Louisa County [8](#louisa-county)
- 7/1/2013 Elk Creek (503) precinct created from split of Fredericks Hall (501).
### 153 Prince William County [9](#prince-william-county)
- 5/7/2013
	- Lodge (207) precinct renamed to Spriggs (207).
	- Pace West (409) precinct renamed to Haymarket (409).
### 515 Bedford City [10](#bedford-county)
- 8/26/2013 Ward One and Ward Two eliminated in consolidation of Bedford City and Bedford County.
### 710 Norfolk City [11](#norfolk-city)
- 2/26/2013 United Way (415) precinct renamed to Lake Taylor High School (415).
### 760 Richmond City [12](#richmond-city)
- 7/8/2013 Boundary adjusted between precincts Five Hundred Three (503) and Five Hundred Five (505).
### 830 Williamsburg City [13](#williamsburg-city)
- 3/14/2013 Berkeley (2) precinct precinct renamed to Matoaka (2).
## Sources
### Bedford County
Bedford County Code § 2 (Ord. No. O082613-10, adopted 8-26-2013). Retrieved from https://librarystage.municode.com/va/bedford_county/codes/code_of_ordinances?nodeId=COCO_CH6EL
#### Chesterfield County
Chesterfield County Code § 7-3 (Ord. of 5-22-13). Retrieved from https://librarystage.municode.com/va/chesterfield_county/codes/code_of_ordinances?nodeId=PTIITHCO_CH7EL_S7-3PRBOPOPL

Chesterfield County Board of Supervisors. (2013, May 22). Board of Supervisors Minutes. Retrieved from http://chesterfieldva.granicus.com/DocumentViewer.php?file=chesterfieldva_fdfbb31e30eaeca434785b768fd0de6d.pdf&view=1
#### Dickenson County
Dickenson County Board of Supervisors. (2013, February 23). Meeting Minutes. Retrieved from https://www.dickensonva.org/DocumentCenter/View/1655/BoS-Minutes---2013---0226

Dickenson County Code § 2-3 (Ord. Book No. 2, 8-23-2011). Retrieved from https://dickensonva.org/DocumentCenter/View/17/Ordinance-Book-2 
#### Fairfax County
Fairfax County Board of Supervisors. (2013, May 23). 2013 Precinct boundary and polling place changes. Retrieved from https://www.fairfaxcounty.gov/elections/sites/elections/files/assets/precincts/2013summary_of_changes.pdf
#### Goochland County
Description of precincts. Goochland County Code § 2–64 (Ord. No. 3028 § 1, 1-2-19). Retrieved from https://library.municode.com/va/goochland_county/codes/code_of_ordinances?nodeId=COOR_CH2AD_ARTIIBOSUSCBOEL_DIV3PRPOPL_S2-64DEPR

Goochland County Virginia Official Electoral Map. (2013). Retrieved from https://www.goochlandva.us/DocumentCenter/View/477/Goochland-County-Voting-Districts-PDF  
#### Lee County
Lee County Board of Supervisors. (2013, March 19). Meeting Minutes. Retrieved from http://www.leecova.org/Minutes/2013/Minutes%203-19-13%20Regular%20Meeting.pdf
#### Loudoun County
Loudoun County Board of Supervisors. (2013, April 17). Proposed Amendments to Chapter 209 of the Codified Ordinances of Loudoun County/Voting Precincts, Polling Places and Absentee Voting Location. Retrieved from https://www.loudoun.gov/DocumentCenter/View/86568/Item-15e---Amendments-to-Chapter-209-Voting
#### Louisa County
Louisa County Board of Supervisors. (2013, July 1). Resolution 2013-113 Amendment to the Louisa County Code of Ordinances, Section 2-4 Election Precincts. Retrieved from http://louisacountyva.iqm2.com/Citizens/Detail_LegiFile.aspx?Frame=&MeetingID=1089&MediaPosition=&ID=2405&CssClass=
#### Prince William County
Prince William Board of County Supervisors (2013, May 7). Regular meeting agenda [resolution to change precinct polling places and names]. Retrieved from https://eservice.pwcgov.org/documents/bocs/agendas/2013/0507/8-A.pdf
#### Nofolk City
Norfolk City Code § 14.1-62 (Ord. No. 45,013, § 1, 2-26-13). Retrieved from https://library.municode.com/va/norfolk/codes/code_of_ordinances/194244?nodeId=COCI_CH14.1EL_ARTIIIPRBO_DIV4WA4_S14.1-62LATAHISCPR
#### Richmond City
New Richmond Voter Districts for Richmond Virginia, as of March 9, 2012. (2012, March 9). Retrieved from http://www.richmondgov.com/content/CouncilRedistricting/documents/NewRichmondVoterDistricts3.9.2012.pdf

Richmond City Code § 30-78–149 (Ord. No. 2011-215-2012-4, 1-9-2012). Retrieved from ftp://ftp.ci.richmond.va.us/Redistricting2011/ExhibitB/Certified%20Ordinance%20No%20%202011-215-2012-4.pdf
#### Williamsburg City
Williamsburg City Code § 2-201 (Ord. No. 13-03, 3-14-13). Retrieved from https://library.municode.com/va/williamsburg/codes/code_of_ordinances?nodeId=PTIITHCO_CH2AD_ARTVEL_S2-201VOPR
