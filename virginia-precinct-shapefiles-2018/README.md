# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2018 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2018 Virginia June Primary and November General Elections. Maps created in QGIS.
* Encoding: EPSG 4269
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2018](#precinct-changes-for-2018)  
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
In 2018, Virginia had 22 precincts split by Congressional district boundaries. These maps are the same as the voting precinct shapefiles, but split precincts are shown as separate features so that election results can be mapped by both precinct and Congressional district.
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.
## Precinct Changes for 2018
### 3 Albemarle County
- 3/14/2018  
	- Belfield (204) precinct merged with Jack Jouett (201) precinct.  
	- Biscuit Run (407) precinct created from split of Cale (405) precinct.  
	- Pantops (507) precinct created from split of Free Bridge (504) precinct.  
	- Mechums River (606) precinct created from split of Crozet (401) and Brownsville (604) precincts.  
### 19 Bedford County
- 3/12/2018 - Forest Fire Station #2 (306) precinct created from split of New London Academy (301) precinct.
### 107 Loudoun County
- 5/24/2018  
	- Goshen Post (126) precinct created from split of Arcola (119) precinct.  
	- Buffalo Trail (322) precinct created from split of Pinebrook (313) precinct.  
	- J. L. Simpson (419) precinct renamed to Sycolin Creek (422) and gained voters from Evergreen (408) precinct in boundary adjustment.  
	- Boundary adjustment transferred some voters from Weller (623) to Ashbrook (627) precinct.  
### 165 Rockingham County
- 8/8/2018 - West Bridgewater (401) and East Bridgewater (406) precincts created from split of Bridgewater (401) precinct.
### 185 Tazewell County
- 7/28/2018..
	- Paint Lick (303) precinct created from merger of Pounding Mill (305) and Wardell (303) precincts.  
	- Mundy Town (103) precinct created from merger of Adria (110) and Gap Store (111) precincts.  
	- Indian Valley (101) precinct created from merger of Abbs Valley (101) and Boissevain (103) precincts.  
### 760 Richmond City
- 4/23/2018 - Precinct 115 created from split of Precincts 101 and 102.
### 770 Roanoke City
- 12/18/2017..
	- Virginia Heights-Norwich (18) precinct dissolved and voters distributed to Old Southwest (10), Raleigh Court (11), Lee-Hi (17), Summit Hills (18), Forest Park (19), and Eureka Park (20).  
	- Summit Hills (19), Forest Park (20), and Eureka Park (21) precincts renumbered to Summit Hills (18), Forest Park (19), and Eureka Park (20).  
### 810 Virginia Beach City
3/20/2018..
	- Salem Woods (99) precinct created from split of Rosemont Forest (64) precinct.
	- Sandbridge (100) precinct created from split of Sigma (31) precinct.
## Sources
Albemarle Board of Supervisors. Ordinance No. 18-2(2), 2 § (2018). Charlottesville, Virginia: Albemarle County Code. Retrieved from https://library.municode.com/va/albemarle_county/ordinances/code_of_ordinances?nodeId=978605..
Bedford County Board of Supervisors. (2018, March 12). Meeting minutes, motion to approve Ordinance #O 031218-03. Retrieved from https://www.bedfordcountyva.gov/Home/ShowDocument?id=6387..
Boothe, C. (2018, June 25). Tazewell advancing plan to consolidate several voting precincts. Retrieved from https://www.bdtonline.com/news/local_news/tazewell-advancing-plan-to-consolidate-several-voting-precincts/article_fc26a606-168b-5d5c-a475-1b61f35a538b.html..
Chittum, M. (2017, December 18). Roanoke City Council votes to eliminate Virginia Heights-Norwich voting precinct. Retrieved from https://www.roanoke.com/news/local/roanoke-city-council-votes-to-eliminate-virginia-heights-norwich-voting/article_a2bd900d-4709-5090-9db4-169578dfa225.html..
Loudoun County Board of Supervisors. (2018, March 22). Proposed Amendments to Chapter 209 of the Codified Ordinances of Loudoun County/Voting Precincts and Polling Places. Retrieved from http://loudoun.granicus.com/MetaViewer.php?view_id=74&clip_id=5402&meta_id=139847..
Proposed Roanoke Voting Precinct Changes. (2017, December 17). Retrieved from https://www.roanoke.com/proposed-roanoke-voting-precinct-changes/pdf_12c57448-4e25-50ee-8725-ca626cb75880.html..
Richmond City Council. Precinct 115, 9-67.1 § (2018). Richmond, Virginia: Code of the City of Richmond. Retrieved from https://library.municode.com/va/richmond/codes/code_of_ordinances?nodeId=PTIICICO_CH9EL_ARTIIIPR_S9-67.1PR115..
Rockingham County Board of Supervisors. Ordinance No. PCO 18-10, 6A-6–7 § (2018). Harrisonburg, Virginia: Rockingham County Code. Retrieved from https://library.municode.com/va/rockingham_county/ordinances/code_of_ordinances?nodeId=909700..
Skelton, A. (2018, March 22). Two new polling places being added in Virginia Beach to deal with more voters. Retrieved from https://www.pilotonline.com/government/local/article_f065a0f0-2bad-11e8-a027-37eee602651f.html..
Wrabel, A. (2018, March 14). Albemarle supervisors OK changes to some voting precincts. Retrieved from https://www.dailyprogress.com/news/local/albemarle-supervisors-ok-changes-to-some-voting-precincts/article_49186dc8-27f2-11e8-a426-9fcb0dc095f6.html..