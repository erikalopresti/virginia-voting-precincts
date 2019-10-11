# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2016 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2016 Virginia November General Elections.

All maps were created using [QGIS](https://www.qgis.org/en/site/).  
Encoding: EPSG 4326. 
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2016](#precinct-changes-for-2016)  
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
## Split Precinct Maps
In 2016, Virginia had 23 precincts split by Congressional district boundaries. This means voters at the same location could be voting in two different US House of Representatives races.
The 2016 set of precinct shapefiles includes:
- Map of precincts including Congressional district (CD) splits. This shapefile can be used to map the results of the US House of Representatives race and also the statewide races for President and Vice President, and United States Senate, which are reported by Congressional district.

These maps are the same as the voting precinct shapefiles, but where district boundaries split a precinct, that precinct is two separate features in the shapefile. This way, election results can be mapped by both precinct and Congressional District. This is useful if one wants to compare, for example, the two-party vote share in a given  election with census demographic data such as income, race, and education rates.  
### Split precinct map attributes
**distSplits** - District splits within the precinct.  
**cdPrecinct** - PrecinctID prefixed by Congressional district number.  
## Precinct Changes for 2016
### 1 Accomack County [1](#accomack-county)
-5/18/2016 Two precincts merged and one renamed.
	- Oak Hall (301) renamed to New Church (301)
	- Onancock and Onley merged to form Nandua
### 41 Chesterfield County [1](#chesterfield-county)
- 4/13/2016 - Two new precincts created.
	- North Bird (215) precinct created from split of Bird (203) precinct.
	- West Beach (318) precinct created from split of Beach (305) precinct.
### 59 Fairfax County [2](#fairfax-county)
- 7/12/2016 - One new precinct created and one precinct renamed.
	- Terraset (225) precinct renamed to Hughes (225) precinct.
	- Rotonda (735) precinct created from split of Tysons (731) precinct.
### 87 Henrico County
- 8/9/2016 One new precinct and one renamed precinct.
	- Byrd (401) renamed to Quioccasin (401)
	- Essex Village (224) precinct created from split of Highland Gardens (211).
### 95 James City County [3](#james-city-county)
- 4/12/2016 - Berkeley D (104) precinct created from split of Berkeley A (101) precinct.
### 153 Prince William County [4](#prince-william-county)
- 5/17/2016 - Haymarket (409) precinct renamed to Tyler (409).
- 6/26/2016 - Godwin (603) precinct renamed to Hampton (603) precinct.
### 193 Westmoreland County [5](#westmoreland-county)
- 8/8/2016 - Two new precincts created 
	- Precinct 2-2 (202) created from split of Precinct 2-1 (201).
	- Precinct 3-2 (302) created from split of Precinct 3-1 (301).
## Sources
### Accomack County
Accomack County Board of Supervisors. (2016, May 18). "An ordinance to amend chapter 34, elections,
article III, precincts, sec. 34-67, polling places of the Accomack County Code" [Rregular meeting agenda]. Retrieved from https://go.boarddocs.com/va/coa/Board.nsf/files/A9EUBB6965AC/$file/Polling%20Place%20Onancock%20and%20Onley%202016.pdf

Some on Eastern Shore have new polling places. (2016, October 17). Retrieved from https://www.13newsnow.com/article/news/local/virginia/eastern-shore/some-on-eastern-shore-have-new-polling-places/336917741
### Chesterfield County
Precinct boundaries and polling places. Chesterfield County Code § 7–3 (Ord. of 4-13-16 §1). Retrieved from https://library.municode.com/va/chesterfield_county/codes/code_of_ordinances?nodeId=PTIITHCO_CH7EL_S7-3PRBOPOPL
### Fairfax County
Fairfax County Office of Elections. (2016, July 12). 2016 Precinct boundary and polling place changes. Retrieved from https://www.fairfaxcounty.gov/elections/sites/elections/files/assets/precincts/summary_jul2016_approved.pdf
### Henrico County
Robinson, Elliott. (2016, August 9). Henrico supervisors approve precinct changes, firehouse proposal. Retrieved from https://www.richmond.com/news/local/henrico-supervisors-approve-precinct-changes-firehouse-proposal/article_e24e4616-b25e-5975-86ef-d57ca0246ab3.html
### James City County
Magisterial Districts, Election Districts and Election Precincts. James City Code art. II § 2-4–5 (Ord. 55A-53, 4-12-16). Retrieved from https://library.municode.com/va/james_city_county/ordinances/code_of_ordinances?nodeId=766617
### Prince William County
Prince William Board of County Supervisors. (2016, July 12). Res. No. 16 Rename Godwin Precinct to Hampton Precinct - Neabsco Magesterial District. Retrieved from https://eservice.pwcgov.org/documents/bocs/agendas/2016/0712/8-A.pdf
### 193 Westmoreland County 
Voters’ guide to Election Day in Westmoreland County. (2016, November 2). Retrieved from http://www.westmorelandnews.net/voters-guide-to-election-day-in-westmoreland-county/
