# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2018 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2018 Virginia June Primary and November General Elections.

All maps were created using [QGIS](https://www.qgis.org/en/site/).  
Encoding: EPSG 4326. 
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2018](#precinct-changes-for-2018)  
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
In 2018, Virginia had 22 precincts split by Congressional district boundaries. This means voters at the same location could be voting in two or three different House of Delegates races.
The 2018 set of precinct shapefiles includes:

`va_precincts_2018_split_by_CD` - Map of precincts including Congressional district (CD) splits. This shapefile can be used to map the results of the US House of Representatives race and also the statewide races for President and Vice President, and United States Senate, which are reported by Congressional district.

These maps are the same as the voting precinct shapefiles, but where district boundaries split a precinct, that precinct is two separate features in the shapefile. This way, election results can be mapped by both precinct and Congressional District. This is useful if one wants to compare, for example, the two-party vote share in a given election with census demographic data such as income, race, and education rates. 
### Split precinct map attributes
`distSplits` - District splits within the precinct.  
`cdPrecinct` - PrecinctID prefixed by Congressional district number.  
## Precinct Changes for 2018
### 3 Albemarle County [1](#albemarle-county)
- 3/14/2018  
	- Belfield (204) precinct merged with Jack Jouett (201) precinct.  
	- Biscuit Run (407) precinct created from split of Cale (405) precinct.  
	- Pantops (507) precinct created from split of Free Bridge (504) precinct.  
	- Mechums River (606) precinct created from split of Crozet (401) and Brownsville (604) precincts.
- 8/1/2018
	- Name of University Hall (202) changed to University (202).
### 19 Bedford County [2](#bedford-county)
- 3/12/2018
	- Forest Fire Station #2 (306) precinct created from split of New London Academy (301) precinct.
	- Forest Youth Athletic Association (304) renamed to The Well Church (304).
### 35 Carroll County [3](#carroll-county)
-10/16/2017 Oakland D (403) and Oakland A (405) merged to form Oakland (401) precinct.
### 87 Henrico County [4](#henrico-county)
- 2/27/2018 Glenside (104) precinct eliminated and merged with Johnson (110).
### 107 Loudoun County [5](#loudoun-county)
- 5/24/2018  
	- Goshen Post (126) precinct created from split of Arcola (119) precinct.  
	- Buffalo Trail (322) precinct created from split of Pinebrook (313) precinct.  
	- J. L. Simpson (419) precinct renamed to Sycolin Creek (422) and gained voters from Evergreen (408) precinct in boundary adjustment.  
	- Boundary adjustment transferred some voters from Weller (623) to Ashbrook (627) precinct.
### 141 Patrick County [6](#patrick-county)
- 3/7/2018 Name of Stuart Administration (402) changed to Stuart Fairgrounds (402).
### 165 Rockingham County [7](#rockingham-county)
- 8/8/2018 - West Bridgewater (401) and East Bridgewater (406) precincts created from split of Bridgewater (401) precinct.
### 185 Tazewell County [8](#tazewell-county)
- 7/28/2018  
	- Mundy Town (103) precinct created from merger of Adria (110) and Gap Store (111) precincts.  
	- Indian Valley (101) precinct created from merger of Abbs Valley (101) and Boissevain (103) precincts.
	- Paint Lick (303) precinct created from merger of Pounding Mill (305) and Wardell (303) precincts.	
	- Raven (404) precint eliminated and merged with Richlands (401) precinct.
### 710 Norfolk CIty [9](#norfolk-city)
- 7-24-2018 Boundaries of Superwards changed
	- Boundaries of Granby (101), Titustown (104), Chesterfield (405), and Ruffner Academy (411) precincts changed.
	- Brambleton (403) precinct eliminated.
### 740 Portsmouth City [10](#portsmouth-city)
- 1/23/2018 Name and polling location changed for Precinct Fourteen (14) from Emily N. Spong Preschool to Brighton Elementary School (14).
- 6/26/2018 Name and polling location changed for River Shore Baptist Church (39) to Churchland Primary and Intermediate School (39).
- 7/24/2018 The Forward Church (22) to St Mark Deliverance Center (22).
- 12/11/2018 Name and polling location changed for Willett Hall (24) to The Senior Station (24) .
### 760 Richmond City [11](#richmond-city)
- 4/23/2018 - Precinct 115 created from split of Precincts 101 and 102.
### 770 Roanoke City [12](roanoke-city)
- 12/18/2017..
	- Virginia Heights-Norwich (18) precinct dissolved and voters distributed to Old Southwest (10), Raleigh Court (11), Lee-Hi (17), Summit Hills (18), Forest Park (19), and Eureka Park (20).  
	- Summit Hills (19), Forest Park (20), and Eureka Park (21) precincts renumbered to Summit Hills (18), Forest Park (19), and Eureka Park (20).  
### 810 Virginia Beach City [13](#virginia-beach-city)
3/20/2018..
	- Salem Woods (99) precinct created from split of Rosemont Forest (64) precinct.
	- Sandbridge (100) precinct created from split of Sigma (31) precinct.
## Sources
### Albemarle County
Albemarle County Code § 2-101–107 (Ord. No. 18-2 § 2, 4-11-2018). Retrieved from https://library.municode.com/va/albemarle_county/ordinances/code_of_ordinances?nodeId=978605

Wrabel, A. (2018, March 14). Albemarle supervisors OK changes to some voting precincts. Retrieved from https://www.dailyprogress.com/news/local/albemarle-supervisors-ok-changes-to-some-voting-precincts/article_49186dc8-27f2-11e8-a426-9fcb0dc095f6.html
### Bedford County
Bedford County Board of Supervisors. (2018, March 12). Meeting minutes, motion to approve Ordinance #O 031218-03. Retrieved from https://www.bedfordcountyva.gov/Home/ShowDocument?id=6387
### Carroll County
Carroll County Board of Supervisors. (2017, October 16). Meeting minutes. Retrieved from http://www.carrollcountyva.gov/document_center/Board%20Packets/2017/October/02_BOS_October-16-2017-Minutes.pdf
### Henrico County
Henrico County Code § 9-2 (Ord. No. 1240, § 1, 2-27-2018). Retrieved from https://library.municode.com/va/henrico_county/codes/code_of_ordinances?nodeId=CD_ORD_CH9EL_S9-2PRPOPL
### Loudoun County
Loudoun County Board of Supervisors. (2018, March 22). Proposed Amendments to Chapter 209 of the Codified Ordinances of Loudoun County/Voting Precincts and Polling Places. Retrieved from http://loudoun.granicus.com/MetaViewer.php?view_id=74&clip_id=5402&meta_id=139847
### Patrick County
Patrick County Electoral Board. (2018, March 7). Electoral Board Meeting Minutes. Retrieved from https://www.co.patrick.va.us/registrar
### Rockingham County
Rockingham County Code § 6A-6–7 (Ord. No. PCO 18-10, 8-8-2018).Retrieved from https://library.municode.com/va/rockingham_county/ordinances/code_of_ordinances?nodeId=909700
### Tazewell County
Boothe, C. (2018, June 25). Tazewell advancing plan to consolidate several voting precincts. Retrieved from https://www.bdtonline.com/news/local_news/tazewell-advancing-plan-to-consolidate-several-voting-precincts/article_fc26a606-168b-5d5c-a475-1b61f35a538b.html
### Norfolk City
Norfolk City Code § 14.1-49–62 (Ord. No. 47,294, § 5, 7-24-18). Retrieved from https://library.municode.com/va/norfolk/ordinances/code_of_ordinances?nodeId=904546
### Portsmouth City
Portsmouth City Code § 10-99 (Ord. No. 2018-08 , § 1, 1-23-2018). Retrieved from https://library.municode.com/va/portsmouth/codes/code_of_ordinances?nodeId=PTIICO_CH10EL_ARTIIIVOPL_S10-99PRNO14

Portsmouth City Code § 10-122 (Ord. No. 2018-48 , § 1, 6-26-2018). Retrieved from https://library.municode.com/va/portsmouth/codes/code_of_ordinances?nodeId=PTIICO_CH10EL_ARTIIIVOPL_S10-122PRNO39

Portsmouth City Code § 10-105 (Ord. No. 2018-62 , § 1, 7-24-2018). Retrieved from https://library.municode.com/va/portsmouth/codes/code_of_ordinances?nodeId=PTIICO_CH10EL_ARTIIIVOPL_S10-105PRNO22

Portsmouth City Code § 10-107 (Ord. No. 2018-116 , § 1, 12-11-2018). Retrieved from https://library.municode.com/va/portsmouth/codes/code_of_ordinances?nodeId=PTIICO_CH10EL_ARTIIIVOPL_S10-107PRNO24
### Roanoke City
Chittum, M. (2017, December 18). Roanoke City Council votes to eliminate Virginia Heights-Norwich voting precinct. Retrieved from https://www.roanoke.com/news/local/roanoke-city-council-votes-to-eliminate-virginia-heights-norwich-voting/article_a2bd900d-4709-5090-9db4-169578dfa225.html

Proposed Roanoke Voting Precinct Changes. (2017, December 17). Retrieved from https://www.roanoke.com/proposed-roanoke-voting-precinct-changes/pdf_12c57448-4e25-50ee-8725-ca626cb75880.html
### Richmond City
Precinct 115. Richmond City Code § 9-67.1 (Ord. No. 2018-116, § 2, 4-23-2018). Richmond, Virginia: Code of the City of Richmond. Retrieved from https://library.municode.com/va/richmond/codes/code_of_ordinances?nodeId=PTIICICO_CH9EL_ARTIIIPR_S9-67.1PR115
### Virginia Beach City
Skelton, A. (2018, March 22). Two new polling places being added in Virginia Beach to deal with more voters. Retrieved from https://www.pilotonline.com/government/local/article_f065a0f0-2bad-11e8-a027-37eee602651f.html

