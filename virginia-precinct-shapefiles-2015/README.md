# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2015 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2015 Virginia November General Elections. Maps created in QGIS.
* Encoding: EPSG 4269
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2015](#precinct-changes-for-2015)  
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
In 2015, Virginia had 127 precincts split by State Senate district boundaries, and 129 precincts split by House of Delegates district boundaries. This means voters at the same location could be voting in two or three different House of Delegates or State Senate races.
The 2015 set of precinct shapefiles includes:
- Map of precincts including Senate of Virginia district (SD) splits. This shapefile can be used to map the results for the 2015 Senate of Virginia election.
- Map of precincts including House of Delegates district (HD) splits. This shapefile can be used to map the results for the 2015 Virginia House of Delegates election.

These maps are the same as the voting precinct shapefiles, but where district boundaries split a precinct, that precinct is two separate features in the shapefile. This way, election results can be mapped by both precinct and State Senate or House of Delegates district. This is useful if one wants to compare, for example, the two-party vote share in a given  election with census demographic data such as income, race, and education rates.
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.  
* hdPrecinct - For maps showing precincts split by House of Delegates district boundaries. Unique identifyer (House of Delegates district number concatenated with precinctID) for each precinct or precinct split portion.  
* sdPrecinct - For maps showing precincts split by State Senate district boundaries. Unique identifyer (State Senate district number concatenated with precinctID) for each precinct or precinct split portion.  
## Precinct Changes for 2015
### Augusta County [1](#augusta-county)
- 2/11/2015 Stuarts Draft Rescue (602) precinct renamed to Ridgeview (602).
### 19 Bedford County [2](#bedford-county)
- 8/10/2015 Three precinct names and polling places changed.
	- Thaxton Elementary School (703) renamed to Thaxton Baptist Church #2 (703).
	- Thaxton Community Center (603) reanamed to Thaxton Baptist Church #1 (603).
	- Body Camp Elementary School (204) to Quaker Baptist Church (204).
### 23 Botetourt County [3](#botetourt-county)
- 2/24/2015 County-wide precinct realignment.  
	- Roaring Run (303), Springwood (304), Courthouse (402), Glen Wilton (404), Oriskany (405), Town Hall (406), and Coyner Springs (501) eliminated.  
	- Amsterdam (101) - Renamed to Daleville (101).  
	- Asbury (102) - Renamed to Greenfield (102).  
	- Buchanan (301) - Gained voters from Roaring Run (303) and Springwood (304) precints.  
	- Mill Creek (302) - Gained voters from Buchanan (301) and Springwood (304) precints.  
	- Eagle Rock (403) - Gained voters from Glen Wilton (404) precinct.  
	- Fincastle (406) - Created from the merger of Courthouse (402), Town Hall (406), and Oriskany (405) precincts.  
	- Troutville (501) - Gained voters from Coyner Springs (501) precinct.  
### 45 Craig County [4](#craig-county)
- 7/2/2015 Three precincts eliminated and merged with surrounding precincts.  
	- North Mountain (202) precinct eliminated in merger with Ammendale (201) precinct.  
	- McGuire's Store (302) precinct eliminated in merger with Marshall's Store (301) precinct.  
	- Forks of Johns Creek (404) precinct eliminated in merger with Craig Springs (403) precinct.  
### 59 Fairfax County [5](#fairfax-county)
- 11/18/2014 Four new precincts and polling locations, several boundary adjustments and renamed precincts.  
	- Olde Creek (114) precinct created from the split of Little Run (109) precinct.  
	- Boundary of Westhampton (317) precinct changed to reflect Fairfax County and Falls Church City boundary changes.  
	- Holmes (506) precinct split to create Holmes #1 (506) and Holmes #2 (530) precincts.  
	- Crossroads (514) precinct created from split of Skyline (520) precinct.  
	- Boundary between Belvoir (619) and Woodlawn (627) precincts adjusted to eliminate House of Delegates split.  
	- Boundary of Marshall (708) precinct changed to reflect Fairfax County and Falls Church City boundary changes.  
	- Centre Ridge (901) precinct split and lost voters to Spindle (924) precinct.  
	- London Towne #1 (910) precinct renamed to London Towne (910).  
	- London Towne #2 (924) precinct renamed to Spindle (924), gained voters from split of Centre Ridge (901) precinct.  
- 6/23/2015 One new precinct, one eliminated precinct, four renamed precincts, one boundary adjustment.  
	- Boundary adjustment transferred some voters from Clearview (321) to Sugarland (327) precinct.  
	- Pioneer (409) precinct created from the split of Forestdale (403) precinct.  
	- Thoreu (720) eliminated in merger with Stenwood (719) precinct.  
	- Kinross East (908) precinct renamed to Hidden Meadow (908).  
	- Kinross West (909) precinct renamed to Oak Hill (909).  
	- Lees Corner #1 (927) precinct renamed to Armvield (927).  
	- Lees Corner #2 (930) precinct renamed to Lees Corner (930).  
### 107 Loudoun County [6](#loudoun-county)
- 4/23/2015 Nine new precincts and polling locations, three renamed and one renumbered precinct.  
	- Carter (117) created from split of Rock Ridge (125) precinct.  
	- Cardinal Ridge (123) created from split of Little River (107) precinct.  
	- Liberty (124) created from split of Freedom (112) precinct.  
	- Rock Ridge (125) created from split of Carter (117) precinct.  
	- Old Arcola VFD (317) precinct created from split of Briar Woods (312) precinct. 
	- Between the Hills precinct changed from number 417 to 421.  
	- Mill Run (618) precinct renamed to Moorefield Station (628).  
	- River Creek (420) precinct created from the split of Harper Park (407) precinct.  
	- Name of Moorefield Station (624) precinct changed to Discobery (629).  
	- Mill Run precinct (625) created from split of Eagle Ridge (616) precinct.  
	- Ashby Ponds precinct (626) created from split of Farmwell Station (622) precinct.  
	- Ashbrook (627) precinct created from split of Weller (623) and Russell Branch (620) precincts.  
	- Lansdowne precinct (821) renamed to Riverside (822) precinct.  
### 153 Prince William County [7](#prince-william-county)
- 12/20/2015 - Ashton (404) renamed to Ben Lomond (404).
### 165 Rockingham County [8](#rockingham-county)
- 7/22/2015 - Crossroads (307) created from split of Massanetta Springs (305) precinct.
### 510 Alexandria City [9](#alexandria-city)
- 3/14/2015 One new precinct and one renamed precinct.
	- Charles Houston (110) created from portions of Fire Department (109) and Durant Center (104) precincts.
	- St James Church (210) precinct renamed to The Hermitage (210)
### 685 Manassas Park City [10](#manassas-park-city)
- 2/24/2015 - Precinct Three (003) created from portions of Precinct One (001) and Precinct Two (002).
### 710 Norfolk City
- 11/5/2014 Hunton Y (411) precinct renamed to Ruffner Academy (411)
### 810 Virginia Beach City [11](#virginia-beach-city)
- 3/17/2015 - Four new precincts and polling locations  
	- Indian River (097) created from split of Round Hill (71) precinct.  
	- Independence (98) precinct created from split of Dahlia (73) precinct.  
	- Dam Neck (95) precinct created from split of Ocean Lakes (3) precinct.  
	- Hilltop (96) precinct created from split of Eastern Shore (67) precinct.  
## Sources
### Augusta County
Stuarts Draft precinct moves to Ridgeview. (2015, February 12). Retrieved from https://www.newsleader.com/story/news/local/2015/02/12/stuarts-draft-precinct-moves-ridgeview/23282827/
### Bedford County
Bedford County Code § 6-44–49 (Ord. No. O081015-18, 8-10-2015). Retrieved from https://library.municode.com/va/bedford_county/codes/code_of_ordinances/293567?nodeId=COCO_CH6EL_ARTIIIPRPOPL_DIV2PRBO
#### Botetourt County
Hammack, L. (2015, February 24). Botetourt County reduces voting precincts to save money. Retrieved from https://www.roanoke.com/news/local/botetourt-county-reduces-voting-precincts-to-save-money/article_7202555d-fc29-5d74-b7f9-a1766175adf8.html
#### Craig County
Election districts and precinct boundaries. Craig County Code § 18-26–11 (Ord. No. 11–09, 7-7-2011). Retrieved from http://craigcountyva.gov/wp-content/uploads/2018/08/Chapter-18-Elections-1.pdf
#### Fairfax County
Fairfax County Board of Supervisors. (2014, November 18). 2014 Precinct and polling place changes. Retrieved from https://www.fairfaxcounty.gov/elections/sites/elections/files/assets/precincts/01a_2015summary_of_changes.pdf

Fairfax County Board of Supervisors. (2015, June 23). 2015 Precinct boundary and polling place changes. Retrieved from https://www.fairfaxcounty.gov/elections/sites/elections/files/assets/precincts/1summaryofprecinctchanges_adopted_062315.pdf
#### Prince William County
Prince William Board of County Supervisors. Ordinance No. 55-15 (2015). Manassas, Virginia. Retrieved from https://eservice.pwcgov.org/documents/bocs/briefs/2015/1117/ord15-55.pdf
#### Rockingham County
Rockingham County GIS. (2015, July 10). Proposed Crossroads Precinct & Polling Place. Retrieved from http://www.rockinghamcountyva.gov/CivicAlerts.aspx?AID=273&ARC=428
#### Loudoun County
Gardezi, A. (2015, September 28). Election 2015: Precinct changes. Retrieved from https://patch.com/virginia/leesburg/election-2015-precinct-changes-0

Letourneau, M. F. (2015). Important voting information, including Dulles District precinct changes and absentee locations. Retrieved from https://www.loudoun.gov/Archive/ViewFile/Item/4899
#### Alexandria City
City of Alexandria Voter Registration Office. (2015). Proposed Precinct Changes in Alexandria. Retrieved from https://www.alexandriava.gov/news_display.aspx?id=82566

City of Alexandria Information and Technology Services GIS Division. (2015, February 11). Proposed creation of Charles Houston Center Precinct. Retrieved from https://www.alexandriava.gov/uploadedFiles/elections/PrecinctChange_Charles Houston Center_v2.pdf
#### Manassas Park City
Voting Places. Manassas Park City Code § 2–2 (Ord. No. 15-1700-964 § 2, 2-24-15). Retrieved from https://library.municode.com/va/manassas_park/codes/code_of_ordinances?nodeId=COCI_CH2AD_ARTIINGE_S2-2VOPL
### Norfolk City
Norfolk City Code § 14.1-122 ( Ord. No. 45,672, § 3, 9-9-14, eff. 11-5-14 ). Retrieved from https://library.municode.com/va/norfolk/ordinances/code_of_ordinances?nodeId=668118
#### Virginia Beach City
Virginia Beach City Council. (March 17, 2015) Meeting Minutes Item # 64662, An ordinance to amend section 10-1 of the City Code. Retrieved from http://edocs.vbgov.com/WebLink/DocView.aspx?id=49708797&dbid=0&repo=CityClerk
