# virginia-voting-precincts
## Virginia voting precinct maps 2016
The 2016 maps reflect the voting precinct boundaries for the 2016 Virginia November General Elections.
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
In 2016, Virginia had 23 precincts split by Congressional district boundaries. These maps are the same as the voting precinct shapefiles, but split precincts are shown as separate features so that election results can be mapped by both precinct and Congressional district.
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.
## Precinct Changes for 2016
### 41 Chesterfield County
4/13/2016 - North Bird (215) precinct created from split of Bird (203) precinct.

4/13/2016 - West Beach (318) precinct created from split of Beach (305) precinct.
### 59 Fairfax County
7/12/2016 - Terraset (225) precinct renamed to Hughes (225) precinct.

7/12/2016 - Rotonda (735) precinct created from split of Tysons (731) precinct.
### 95 James City County
4/12/2016 - Berkeley D (104) precinct created from split of Berkeley A (101) precinct.
### 153 Prince William County
6/26/2016 - Godwin (603) precinct renamed to Hampton (603) precinct.
### 193 Westmoreland County
8/8/2016 - Precinct 2-2 (202) created from split of Precinct 2-1 (201).

8/8/2016 - Precinct 3-2 (302) created from split of Precinct 3-1 (301).
## Sources
Chesterfield County Board of Supervisors. Precinct boundaries and polling places, Ord. of 4-13-16(1), § 1, Section 7–3 § (2017). Chesterfield, Virginia: Chesterfield County Code of Ordinances. Retrieved from https://library.municode.com/va/chesterfield_county/codes/code_of_ordinances?nodeId=PTIITHCO_CH7EL_S7-3PRBOPOPL

Fairfax County Office of Elections. (2016, July 12). 2016 Precinct boundary and polling place changes. Retrieved from https://www.fairfaxcounty.gov/elections/sites/elections/files/assets/precincts/summary_jul2016_approved.pdf

James City County Board of Supervisors. Ordinance No. 55A-53 (2016). Williamsburg, Virginia: James City County Code of Ordinances. Retrieved from https://library.municode.com/va/james_city_county/ordinances/code_of_ordinances?nodeId=766617

Prince William Board of County Supervisors. (2016, July 12). Res. No. 16 Rename Godwin Precinct to Hampton Precinct - Neabsco Magesterial District. Retrieved from https://eservice.pwcgov.org/documents/bocs/agendas/2016/0712/8-A.pdf

Voters’ guide to Election Day in Westmoreland County. (2016, November 2). Retrieved from http://www.westmorelandnews.net/voters-guide-to-election-day-in-westmoreland-county/