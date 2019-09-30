# virginia-voting-precincts
## Virginia voting precinct maps 2016
The 2015 maps reflect the voting precinct boundaries for the 2015 Virginia November General Elections.
* Encoding: EPSG 4269
### Attributes
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
In 2015, Virginia had 127 precincts split by State Senate district boundaries, and 129 precincts split by House of Delegates district boundaries. These maps are the same as the voting precinct shapefiles, but split precincts are shown as separate features so that election results can be mapped by both precinct and State Senate or House of Delegates district.
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.
## Precinct Changes for 2015
### 23 Botetourt County [Hammack, L. (2015, February 24). Botetourt County reduces voting precincts to save money. Retrieved from https://www.roanoke.com/news/local/botetourt-county-reduces-voting-precincts-to-save-money/article_7202555d-fc29-5d74-b7f9-a1766175adf8.html][1]
2/24/2015 - Amsterdam (101) precinct renamed to Daleville (101).

2/24/2015 - Asbury (102) precinct renamed to Greenfield (102).

2/24/2015 - New boundaries of Buchanan (301) precinct formed from the merger of Buchanan (301), Roaring Run (303) and Springwood (304) precints.

2/24/2015 - New boundaries of Mill Creek (302) precinct formed from the merger of Buchanan (301), Mill Creek (302) and Springwood (304) precints.

2/24/2015 - New boundaries of Eagle Rock (403) precinct formed from the merger of Eagle Rock (403) and Glen Wilton (404) precincts.

2/24/2015 - Fincastle (406) precinct formed from the merger of Courthouse (402), Town Hall (406), and Oriskany (405) precincts.

2/24/2015 - New boundaries of Troutville (501) precinct formed by merger of Coyner Springs (501) and Troutville (503).
### 45 Craig County
7/2/2015 - North Mountain (202) precinct eliminated in merger with Ammendale (201) precinct.

7/2/2015 - McGuire's Store (302) precinct eliminated in merger with Marshall's Store (301) precinct.

7/2/2015 - Forks of Johns Creek (404) precinct eliminated in merger with Craig Springs (403) precinct.
### 59 Fairfax County
11/18/2014 - Olde Creek (114) precinct created from the split of Little Run (109) precinct.

11/18/2014 - Boundary of Westhampton (317) precinct changed to reflect Fairfax County and Falls Church City boundary changes.

11/18/2014 - Holmes (506) precinct split to create Holmes #1 (506) and Holmes #2 (530) precincts.

11/18/2014 - Crossroads (514) precinct created from split of Skyline (520) precinct.

11/18/2014 - Boundary between Belvoir (619) and Woodlawn (627) precincts adjusted to eliminate House of Delegates split.

11/18/2014 - Boundary of Marshall (708) precinct changed to reflect Fairfax County and Falls Church City boundary changes.

11/18/2014 - Centre Ridge (901) precinct split and lost voters to Spindle (924) precinct.

11/18/2014 - London Towne #1 (910) precinct renamed to London Towne (910).

11/18/2014 - London Towne #2 (924) precinct renamed to Spindle (924), gained voters from split of Centre Ridge (901) precinct.

6/23/2015 - Boundary adjustment transferred some voters from Clearview (321) to Sugarland (327) precinct.

6/23/2015 - Pioneer (409) precinct created from the split of Forestdale (403) precinct.

6/23/2015 - Thoreu (720) eliminated in merger with Stenwood (719) precinct.

6/23/2015 - Kinross East (908) precinct renamed to Hidden Meadow (908).

6/23/2015 - Kinross West (909) precinct renamed to Oak Hill (909).

6/23/2015 - Lees Corner #1 (927) precinct renamed to Armvield (927).

6/23/2015 - Lees Corner #2 (930) precinct renamed to Lees Corner (930).
### 107 Loudoun County
4/23/2015 - Carter precinct (117) created from split of Rock Ridge (125) precinct.

4/23/2015 - Cardinal Ridge precinct (123) created from split of Little River (107) precinct.

4/23/2015 - Liberty precinct (124) created from split of Freedom (112) precinct.

4/23/2015 - Rock Ridge precinct (125) created from split of Carter (117) precinct.

4/23/2015 - Mill Run (618) precinct renamed to Moorefield Station (628) precinct.

4/23/2015 - Old Arcola VFD (317) precinct created from split of Briar Woods (312) precinct.

4/23/2015 - Between the Hills precinct changed from number 417 to 421.

4/23/2015 - River Creek (420) precinct created from the split of Harper Park (407) precinct.

4/23/2015 - Name of Moorefield Station (624) precinct changed to Discobery (629).

4/23/2015 - Mill Run precinct (625) created from split of Eagle Ridge (616) precinct.

4/23/2015 - Ashby Ponds precinct (626) created from split of Farmwell Station (622) precinct.

4/23/2015 - Ashbrook (627) precinct created from split of Weller (623) and Russell Branch (620) precincts.

4/23/2015 - Lansdowne precinct (821) renamed to Riverside (822) precinct.
### 153 Prince William County
12/20/2015 - Ashton (404) precinct renamed to 404 Ben Lomond (404) precinct.
### 165 Rockingham County
7/22/2015 - Crossroads (307) precinct created from split of Massanetta Springs (305) precinct.
### 510 Alexandria City
3/14/2015 - Charles Houston (110) precinct created from portions of Fire Department (109) and Durant Center (104) precincts.
### 685 Manassas Park City
2/24/2015 - Precinct Three (003) created from portions of Precinct One (001) and Precinct Two (002).
### 810 Virginia Beach City
3/17/2015 - Indian River (097) precinct created from split of Round Hill (71) precinct.

3/17/2015 - Independence (98) precinct created from split of Dahlia (73) precinct.

3/17/2015 - Dam Neck (95) precinct created from split of Ocean Lakes (3) precinct.

3/17/2015 - Hilltop (96) precinct created from split of Eastern Shore (67) precinct.

## Sources
Craig County Board of Supervisors. Election districts and precinct boundaries, 11–09 § (2016). New Castle, Virginia: Code of Ordinances for Craig County. Retrieved from http://craigcountyva.gov/wp-content/uploads/2018/08/Chapter-18-Elections-1.pdf

Gardezi, A. (2015, September 28). Election 2015: Precinct changes. Retrieved from https://patch.com/virginia/leesburg/election-2015-precinct-changes-0

Hammack, L. (2015, February 24). Botetourt County reduces voting precincts to save money. Retrieved from https://www.roanoke.com/news/local/botetourt-county-reduces-voting-precincts-to-save-money/article_7202555d-fc29-5d74-b7f9-a1766175adf8.html

Letourneau, M. F. (2015). Important voting information, including Dulles District precinct changes and absentee locations. Retrieved from https://www.loudoun.gov/Archive/ViewFile/Item/4899

Manassas Park City Council. Voting Places, 2–2 § (2015). Manassas Park, Virginia: Manassas Park Code of Ordinances. Retrieved from https://library.municode.com/va/manassas_park/codes/code_of_ordinances?nodeId=COCI_CH2AD_ARTIINGE_S2-2VOPL