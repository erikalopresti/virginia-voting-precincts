<meta name="google-site-verification" content="40S93IIlLJok-0QCMvjzt784RiVlVB9q2mJvrDsnfUA" />

# Virginia Voting Precincts and Election Districts
The shapefiles in this project reflect voting precinct boundaries for Virginia primary and general elections from 2009-2020.
![image](https://user-images.githubusercontent.com/20375915/66661177-93855280-ec14-11e9-9f8f-3f1621ec3c4c.png)
Precinct changes prior to each election were obtained from precinct and district-level voter registration statistics, individual locality sources such as GIS data and Codes of Ordinances. The information was confirmed with election result and turnout data from the Virginia Department of Elections.

Please see the [Virginia Voting Precincts Wiki](https://github.com/erikalopresti/virginia-voting-precincts/wiki) for more information and a full list of sources. 
- All maps were created in QGIS
- Encoding: EPSG 4326
## Shapefiles
### File Suffixes
- va_precincts_YYYY_nov_general
- va_precincts_YYYY_jun_primary
- va_precincts_YYYY_MON_clipped_shore
- va_precincts_YYYY_MON_split_by_CD
- va_precincts_YYYY_MON__split_by_SD
- va_precincts_YYYY_MON__split_by_HD
### Years and Elections available
- 2019
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
* precUid - PrecinctUid given in the .csv files of Individual Election Results from the Virginia Department of Elections.
* localUid - LocalityUid given in the .csv files of Individual Election Results from the Virginia Department of Elections.
* changeDate - Date of last known change to the precinct boundaries, name or number.
* lastChange - Last known change to the precinct boundaries, name or number.
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* hdPrecinct - For maps showing precincts split by House of Delegates district boundaries. Unique identifyer (House of Delegates district number concatenated with precinctID) for each precinct or precinct split portion.
* sdPrecinct - For maps showing precincts split by State Senate district boundaries. Unique identifyer (State Senate district number concatenated with precinctID) for each precinct or precinct split portion.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.
## Full Index of Files
#### [Virginia voting precincts: 2019-2020](https://github.com/erikalopresti/virginia-voting-precincts/tree/master/virginia-precinct-shapefiles-2019-2020)
	- va_precincts_2019_2020
	- va_precincts_2019_clipped_shore
	- va_precincts_2020_split_by_CD
	- va_precincts_2019_split_by_SD
	- va_precincts_2019_split_by_HD
#### [Virginia voting precincts: 2018](https://github.com/erikalopresti/virginia-voting-precincts/tree/master/virginia-precinct-shapefiles-2018)
	- va_precincts_2018_nov_general
	- va_precincts_2018_nov_clipped_shore
	- va_precincts_2018_nov_split_by_CD
	- va_precincts_2018_jun_primary (coming soon)
#### [Virginia voting precincts: 2017](https://github.com/erikalopresti/virginia-voting-precincts/tree/master/virginia-precinct-shapefiles-2017)
	- va_precincts_2017_nov_general
	- va_precincts_2017_clipped_shore
	- va_precincts_2017_nov_split_by_CD
	- va_precincts_2017_nov_split_by_HD
#### [Virginia voting precincts: 2016](https://github.com/erikalopresti/virginia-voting-precincts/tree/master/virginia-precinct-shapefiles-2016)
	- va_precincts_2016_nov_general
	- va_precincts_2016_clipped_shore
	- va_precincts_2016_nov_split_by_CD
#### [Virginia voting precincts: 2015](https://github.com/erikalopresti/virginia-voting-precincts/tree/master/virginia-precinct-shapefiles-2015)
	- va_precincts_2015_nov_general
	- va_precincts_2015_clipped_shore
	- va_precincts_2015_nov_split_by_HD
	- va_precincts_2015_nov_split_by_SD
#### [Virginia voting precincts: 2014](https://github.com/erikalopresti/virginia-voting-precincts/tree/master/virginia-precinct-shapefiles-2014)
	- va_precincts_2014_nov_general
	- va_precincts_2014_clipped_shore
	- va_precincts_2014_nov_split_by_CD
#### [Virginia voting precincts: 2013](https://github.com/erikalopresti/virginia-voting-precincts/tree/master/virginia-precinct-shapefiles-2013)
	- va_precincts_2013_nov_general
	- va_precincts_2013_clipped_shore
	- va_precincts_2013_nov_split_by_CD
	- va_precincts_2013_nov_split_by_HD
#### [Virginia voting precincts: 2012](https://github.com/erikalopresti/virginia-voting-precincts/tree/master/virginia-precinct-shapefiles-2012)
	- va_precincts_2012_nov_general
	- va_precincts_2012_clipped_shore
	- va_precincts_2012_nov_split_by_CD
#### Virginia voting precincts: 2011 (coming soon)
	- va_precincts_2011_nov_general
	- va_precincts_2011_clipped_shore
	- va_precincts_2011_nov_split_by_HD
	- va_precincts_2011_nov_split_by_SD
#### Virginia voting precincts: 2009-2010 (coming soon)
	- va_precincts_2009_2010
	- va_precincts_2009_2010_clipped_shore
	- va_precincts_2009_2010_split_by_CD
	- va_precincts_2009_2010_split_by_HD
	- va_precincts_2009_2010_split_by_CD
#### Virginia magisterial districts: 2011-2020
	- va_magisterial_districts_2011_2020
