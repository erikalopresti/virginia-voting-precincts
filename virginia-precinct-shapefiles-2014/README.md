# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2014 shapefiles
These precinct shapefile maps reflect voting precinct boundaries for the 2014 Virginia November General Elections.

All maps were created using [QGIS](https://www.qgis.org/en/site/).  
Encoding: EPSG 4326.  
#### Table of Contents
[Attributes](#attributes)  
[Split Precinct Maps](#split-precinct-maps)  
[Precinct Changes for 2014](#precinct-changes-for-2014)  
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
In 2014, Virginia had 20 precincts split by Congressional district boundaries. This means voters at the same location could be voting in two different US House of Representatives races.
The 2014 set of precinct shapefiles includes:
- Map of precincts including Congressional district (CD) splits. This shapefile can be used to map the results of the US House of Representatives race and also the statewide race United States Senate, which is reported by Congressional district.

These maps are the same as the voting precinct shapefiles, but where district boundaries split a precinct, that precinct is two separate features in the shapefile. This way, election results can be mapped by both precinct and Congressional District. This is useful if one wants to compare, for example, the two-party vote share in a given  election with census demographic data such as income, race, and education rates.  
### Split precinct map attributes
**distSplits** - District splits within the precinct.  
**cdPrecinct** - PrecinctID prefixed by Congressional district number.
## Precinct Changes for 2014
### 25 Brunswick County [1](#brunswick-county) 
- 6/18/2014 Lawrenceville (501) precinct renamed to Totaro (501)
### 121 Montgomery County [2](#montgomery-county)
6/9/2014 - Precinct F-3 (603) created from portions of Precinct F-1 (601) and Precinct G-1 (701).  
### 152 Prince William County [3](#prince-william-county)
- 3/11/2014 County-wide precinct reorganization, 14 new precincts created
	- Boundary adjustment between Brentsville (101) and Nokesville (104).  
	- Limestone (105) gained voters from split of Piney Branch (109).  
	- Jackson (106) renamed to Westgate (106).  
	- Burke-Nickens (112) created from split of Buckland Mills (110).  
	- Rosa Parks (215) created from portions of Saunders (201), Hylton (208), and Penn (210).  
	- Spriggs (207) split to create Saratoga (213) precinct, and gained voters from the split of Hylton (208).  
	- Park (209) renamed to Independent Hill (209).  
	- Lucasville (214) created from split of Bennett (203).  
	- Triangle (312) precinct gained voters from split of Graham Park (303).  
	- Cardinal (313) created from split of Henderson (307).  
	- Cabin Branch (314) created from split of Montclair (308).  
	- Evergreen (401) split and lost voters to Battlefield (402).  
	- Battlefield (402) split and lost voters to Catharpin (412) and Haymarket (409).  
	- Ashton (404) created from portions of Mullen (411) and Stonewall (405).  
	- Sinclair (404) eliminated in merger with Stonewall (405).  
	- Catharpin (412) created from split of Battlefield (402).  
	- Reagan (413) created from split of Alvey (406).  
	- Lake Ridge (501) split and lost voters to Mohican (505) precinct.  
	- Old Bridge (503) split to create Lynnwood (513), and gained voters from the split of Springwoods (508).  
	- Rockledge (504) and Mohican (505) split to create Antietam (514).  
	- Springwoods (508) split and lost voters to Old Bridge (503).  
	- McCoart (509) gained voters from split of Stadium (510), which was renamed to Yates Ford (510).  
	- Stadium (510) renamed to Yates Ford (510), split and lost voters to McCoart (509).  
	- Lynnwood (513) created from split of Old Bridge (503) precinct.  
	- Antietam (514) created from portions of Rockledge (504) and Mohican (505).  
	- Neabsco (611) created from split of Hampton (603).
	- Civic Center (604) precinct renamed to Gideon (604)
	- Porter (704) new location created from split of Rippon (706) and Freedom (709).  
	- River Oaks (708) split to create Powells Creek (710) precinct, and part of Leesylvania (712).  
	- Powells Creek (710) created from split of River Oaks (708).  
	- Grayson (711) created from split of Library (702).  
	- Senate District 29 segments from Freedom (709), Rippon (706) and Porter (704) merged into Freedom (709), which was then split to create Leesylvania (712).  
## Sources
#### Brunswick County
Brunswick County Code § 22-35 (Ord. of 6-18-2014(2), §§ 1, 2). Retrieved from https://library.municode.com/va/brunswick_county/codes/code_of_ordinances?nodeId=CO_CH22EL_ARTIIELDIPRPOPL_S22-35POPL
#### Montgomery County
Montgomery County Board of Supervisors. Proposed Ordinance Amending Election Districts – Create On-Campus Voting Precincts (2014). Christiansburg, Virginia. Retrieved from https://go.boarddocs.com/va/montva/Board.nsf/files/BDZLFS55A6BC/$file/2014-06-09_m.pdf
#### Prince William County
Prince William Board of County Supervisors. Ordinance No. 14-08. Adopt changes to voting precinct boundaries, precinct polling places and precinct names (2014). Manassas, Virginia. Retrieved from https://eservice.pwcgov.org/documents/bocs/briefs/2014/0311/ord14-08.pdf
