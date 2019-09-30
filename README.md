# Virginia Voting Precincts and Election Districts
## Virginia voting precinct maps, 2009-2020 shapefiles 
These precinct shapefile maps reflect voting precinct boundaries for Virginia primary and general elections from 2009-2020. All maps were created in QGIS using the sources listed below. Voting district (VTD) maps exist from the US Census Bureau for the 2010 Census, with a partnership shapefile update in January 2018. Between each election, changes are made by individual localities by merging, splitting, renaming, and shifting precinct boundaries. Precinct changes prior to each election were obtained from precinct and district-level voter registration statistics, individual locality sources such as GIS data and Codes of Ordinances, and newspaper notices of precinct and polling place changes. The information was confirmed with election result and turnout data from the Virginia Department of Elections.
![image](https://user-images.githubusercontent.com/20375915/65660713-886bd900-dffd-11e9-9900-0574487f37df.png)
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
Virginia has many election precincts that are split by Congressional, State Senate, or House of Delegates district boundaries. These maps are the same as the voting precinct shapefiles, but split precincts are shown as separate features so that election results can be mapped by both precinct and district.
![image](https://user-images.githubusercontent.com/20375915/65730807-2e1c5800-e091-11e9-8e02-c69e6baa6571.png)
### Attributes for split precinct maps
* distSplits - District splits within the precinct.
* hdPrecinct - For maps showing precincts split by House of Delegates district boundaries. Unique identifyer (House of Delegates district number concatenated with precinctID) for each precinct or precinct split portion.
* sdPrecinct - For maps showing precincts split by State Senate district boundaries. Unique identifyer (State Senate district number concatenated with precinctID) for each precinct or precinct split portion.
* cdPrecinct - For maps showing precincts split by Congressional district boundaries. Unique identifyer (Congressional district number concatenated with precinctID) for each precinct or precinct split portion.
##	Sources
###	All Localities
####	US Census Bureau
United States Census Bureau. (2019). Partnership Shapefiles. Retrieved from https://www.census.gov/geographies/mapping-files/time-series/geo/partnership.html
####	Virginia Department of Elections
Virginia Department of Elections. (2019). Election Results. Retrieved from https://www.elections.virginia.gov/resultsreports/index.html	

Virginia Department of Elections. (2019). Registration Statistics and Polling Places. Retrieved from https://www.elections.virginia.gov/resultsreports/registration-statistics/	

Virginia Department of Elections. (2019). Registration/Turnout Reports. Retrieved from https://www.elections.virginia.gov/registrationturnout-statistics/
###	Individual Locality Resources  
#### 1 Accomack County
Accomack County Department of Planning and Community Development. (2011, March 26). Accomack County Virginia Precincts and Polling Locations. Retrieved from https://www.co.accomack.va.us/departments/registrar/precincts-and-polling-locations
#### 3 Albemarle County
Albemarle County Office of Geographic Data Services. (2019, February 9). Voter Precincts. Retrieved from http://www.albemarle.org/department.asp?department=gds&relpage=3914#Political

Albemarle Board of Supervisors. Ordinance No. 18-2(2), 2 § (2018). Charlottesville, Virginia: Albemarle County Code. Retrieved from https://library.municode.com/va/albemarle_county/ordinances/code_of_ordinances?nodeId=978605
#### 5 Alleghany County
Alleghany County 2011 districts and precincts. (2011). Retrieved from http://www.co.alleghany.va.us/wp-content/uploads/2016/08/magisterial.districts.pdf
#### 7 Amelia County
Amelia County Redistricting Committee. (2011, May 2). Voting District Map. Retrieved from http://ameliacova.com/Voting%20District%20Map.pdf
#### 9 Amherst County
Amherst County Voter Registration. (n.d.). Voter District Map (Revised). Retrieved September 26, 2019, from https://www.countyofamherst.com/egov/documents/1425326147_07445.pdf
#### 11 Appomattox County
Appomattox County Virginia 2011 Redistricting Map. (2011, April 25). Retrieved from http://www.appomattoxcountyva.gov/home/showdocument?id=40
#### 13 Arlington County
Arlington County GIS Mapping Center. (2019, September 19). Arlington County, Va Voter Precinct Polygons. Retrieved from https://gisdata-arlgis.opendata.arcgis.com/datasets/voter-precinct-polygons
#### 15 Augusta County
Augusta County Voter Registration. (2015). Magisterial Districts and Precincts 2015. Retrieved from https://www.co.augusta.va.us/home/showdocument?id=7392
#### 17 Bath County
Bath County Board of Supervisors. Precincts-names and polling places, 9–5 § (2016). Warm Springs, Virginia: Bath County Local Code. Retrieved from http://www.bathcountyva.org/common/pages/DisplayFile.aspx?itemId=11784780
#### 19 Bedford County
Bedford County GIS Department. (2018, August 2). Bedford County Voting Precincts. Retrieved from https://geohub-bedfordvagis.opendata.arcgis.com/datasets/voting-precincts
#### 21 Bland County

#### 23 Botetourt County
Botetourt County GIS Department. (2016, March). Botetourt County Virginia Voting Precincts. Retrieved from https://botetourtva.gov/botetourt/wp-content/uploads/2019/04/2016_Precincts_8x11.pdf
#### 25 Brunswick County
Brunswick County Virginia Board of Supervisors. (n.d.). Election District Map. Retrieved September 19, 2019, from https://www.brunswickco.com/government/board_of_supervisors/election_district_map
#### 27 Buchanan County

#### 29 Buckingham County
Buckingham County General Registrar and Elections. (2010). Voting Districts 2010. Retrieved from http://www.buckinghamcountyva.org/Docs/Registrar Docs/votingmapdistricts.jpg
#### 31 Campbell County
Campbell County GIS Office. (2019, July 2). Voting Precincts. Retrieved from https://data-campbellva.opendata.arcgis.com/datasets/843401e26d244a869543bd2a8443deb9_0
#### 33 Caroline County
Caroline County Election Districts and Precinct Boundaries. (2012, July 10). Retrieved from https://co.caroline.va.us/DocumentCenter/View/506/Election-District-Map-PDF
#### 35 Carroll County
Carroll County Voter Registration. (2018). Voting districts and precinct maps. Retrieved from http://www.carrollcountyva.gov/residents_and_community_services/elections_and_voter_registration/county_voting_districts_and_precincts_maps.php
#### 36 Charles City County
Charles City Board of Supervisors. Elections, 14 § (2011). The Code of the County of Charles City. Retrieved from https://library.municode.com/va/charles_city_county/codes/code_of_ordinances?nodeId=COOR_CH14EL_ARTIIIELDI
#### 37 Charlotte County
Charlotte County Voter Registration. (2011, August 8). Charlotte Final Redistricting Plan - Precincts. Retrieved from http://www.charlotteva.com/pdfs/Voting_precincts.pdf
#### 41 Chesterfield County
Voting Precinct Boundaries in Chesterfield County, VA. (2019, September 18). Retrieved from http://opengeospace.chesterfield.gov/datasets/349dce35948843289e85e1a18ade455e_1
#### 43 Clarke County
Clarke County GIS. (n.d.). Clarke County MapsOnline. Retrieved September 26, 2019, from https://www.mapsonline.net/clarkecounty/
#### 45 Craig County
Craig County Board of Supervisors. Election districts and precinct boundaries, 11–09 § (2016). New Castle, Virginia: Code of Ordinances for Craig County. Retrieved from http://craigcountyva.gov/wp-content/uploads/2018/08/Chapter-18-Elections-1.pdf
#### 47 Culpeper County
Culpeper County Virginia Voting Precinct Map. (2019, March 6). Retrieved from http://www.voteinculpeper.info/map-expanded/
#### 49 Cumberland County
Cumberland County Redistricting Committee. (2011). Cumberland County Magisterial District Map. Retrieved from https://www.cumberlandcounty.virginia.gov/sites/default/files/2017-10/Registrar_Redistricting_2010.pdf
#### 51 Dickenson County
Dickenson County Board of Supervisors. (2011, August 23). Ordinance Book No. 2. Retrieved from https://dickensonva.org/DocumentCenter/View/17/Ordinance-Book-2

Dickenson County Board of Supervisors. (2013, February 23). Meeting Minutes. Retrieved from https://www.dickensonva.org/DocumentCenter/View/1655/BoS-Minutes---2013---0226
#### 53 Dinwiddie County
Dinwiddie County, Virginia 2012 Approved Precincts Based on 2010 Census Data. (2012). Retrieved from https://www.dinwiddieva.us/DocumentCenter/View/1592/Dinwiddie_Approved_Districts_2012
#### 57 Essex County
Middle Peninsula Planning District Commission. (2011, July 14). Essex County, Virginia New Voting Districts - 2011. Retrieved from http://www.essex-virginia.org/UserFiles/Servers/Server_62876/Image/Essex 2011 New Voting Districts - Area of Change 7-22-11.pdf
#### 59 Fairfax County
Fairfax County Office of Elections. (2019). Polling Places. Retrieved from https://www.fairfaxcounty.gov/elections/precincts

Fairfax County Open Data. (2019, September 14). Voting Precincts. Retrieved from https://data-fairfaxcountygis.opendata.arcgis.com/datasets/7727de78b3984f4daa1ff0960d0da8cb_1
#### 61 Fauquier County
Fauquier County GIS. (2016, May 11). Voting Precincts Shapefile. Retrieved from ftp://vm-ftp.fauquiercounty.gov/
#### 63 Floyd County
King Moore Professional GIS/IT Services. (2011). Floyd County Voting District Map. Retrieved from https://www.floydcova.org/departments/2011VotingDistrictMap.pdf
#### 65 Fluvanna County
Fluvanna County, VA Geographic Information System. (n.d.). Retrieved September 24, 2019, from https://www.webgis.net/va/fluvanna/
#### 67 Franklin County
Franklin County Virginia Precinct Maps. (n.d.). Retrieved September 19, 2019, from http://www.franklincountyva.gov/voter-registrar-precinct-maps
#### 69 Frederick County
Frederick County Virginia Voter Registration Office. (n.d.). Frederick County Polling Place. Retrieved September 19, 2019, from https://fredcogis.fcva.us/ElectionPollingPlace/
#### 71 Giles County

#### 75 Goochland County
Goochland County Virginia Official Electoral Map. (2013). Retrieved from https://www.goochlandva.us/DocumentCenter/View/477/Goochland-County-Voting-Districts-PDF
#### 77 Grayson County

#### 79 Greene County
Thomas Jefferson Planning District Commission. (2011, June 14). Greene County Election Districts. Retrieved from https://www.greenecountyva.gov/forms/documents/voter-registration/164-greene-county-election-districts/file
#### 81 Greensville County
Greensville County Geographic Information Systems. (2019, September). Retrieved from https://www.webgis.net/va/greensville/
#### 83 Halifax County
Halifax County Voter Registrar. (2011, April 5). Voting Precincts & Election Districts. Retrieved from https://www.halifaxcountyva.gov/?SEC=E3E00860-36AA-48CE-87F1-36994BCF345A
#### 85 Hanover County
Hanover County GIS. (2015). Hanover County Voting Precinct Map. Retrieved from https://www.hanovercounty.gov/DocumentCenter/View/1373/Hanover-County-Election-Districts-Map-PDF
#### 87 Henrico County
Henrico County GIS Office. (2019, August 26). Voting Precincts. Retrieved from https://data-henrico.opendata.arcgis.com/datasets/voting-precincts
#### 89 Henry County
Henry County Board of Supervisors. (2011, January 2). Organizational Meeting Minutes. Retrieved from https://www.henrycountyva.gov/content/uploads/PDF/2011_Board_of_Supervisors_Board_Packets/bos_minutes_2012.pdf
#### 91 Highland County
Central Shenandoah Planning District Commission. (2010, June). County of Highland - Magisterial Districts. Retrieved from http://www.highlandcova.org/Compmaps/1 - Magisterial Districts.pdf
#### 93 Isle Of Wight County
Isle of Wight County – Election Districts, Precincts, and Polling Locations. (n.d.). Retrieved from http://www.co.isle-of-wight.va.us/voter-registration/districts-precincts-and-polling-locations/
#### 95 James City County
James City County Voting Precincts. (2019, March 12). Retrieved September 19, 2019, from https://opendata-jcc.opendata.arcgis.com/datasets/b61f172ab29e4db38d3ac7c9e6015d83_26

James City County GIS Office. (2017, July 10). Voting Precincts State Senate and House Districts. Retrieved from https://jamescitycountyva.gov/DocumentCenter/View/459/Precincts--House-Districts-Map-PDF
#### 97 King & Queen County
King & Queen County Registrar. (n.d.). Precincts and Polling Places. Retrieved September 19, 2019, from http://www.kingandqueenco.net/html/Govt/registrar.html
#### 99 King George County
King George County GIS. (2019, March 4). Voting Precinct. Retrieved from https://data-king-george.opendata.arcgis.com/datasets/voting-precinct
#### 101 King William County
Brooks, B. (2016, March). King William County Supervisor/Voting Precinct Map. Retrieved from https://kingwilliamcounty.us/wp-content/uploads/2014/01/2014_SupervisorMap1.pdf
#### 103 Lancaster County
Lancaster County, Virginia voting districts map. (2017, December 11). Retrieved from http://www.lancova.com/documents/Voting_Districts_2011.pdf
#### 105 Lee County
Lee County Board of Supervisors. (2013, March 19). Meeting Minutes. Retrieved from http://www.leecova.org/Minutes/2013/Minutes 3-19-13 Regular Meeting.pdf
#### 107 Loudoun County
Loudoun County Open Data Group. (2019, April 9). Loudoun Election Precincts. Retrieved from https://geohub-loudoungis.opendata.arcgis.com/datasets/ef2c7c42a1ca441fa839426cf1481a50_3
#### 109 Louisa County
Louisa County Voter Registrar. (2017, November 20). Voting Districts and Precincts. Retrieved from https://www.louisacounty.com/1142/Voting-Districts-and-Precincts
#### 111 Lunenburg County
Timmons Group Web LoGIStics. (n.d.). Lunenburg Web LoGIStics, District Boundaries. Retrieved September 26, 2019, from https://lunenburggis.timmons.com/#/mwl
#### 113 Madison County

#### 115 Mathews County
Mathews County Voter Registrar. (n.d.). Mathews County, VA Voting Precincts. Retrieved September 19, 2019, from http://www.mathewscountyva.gov/government/voter-registrar-s-office/precinct-information

Mathews County Board of Supervisors. Boundaries of precincts, 44–5 § (2001). Mathews, Virginia: Mathews County Code of Ordinances. Retrieved from https://ecode360.com/8426450
#### 117 Mecklenburg County
Mecklenburg County Registrar’s Office. (2011). Mecklenburg County, Virginia Voter District Map 2011. Retrieved from https://www.mecklenburgva.com/voter-district-map.aspx
#### 119 Middlesex County
Middlesex County, Virginia 2016 Voting Precinct Map. (n.d.). Retrieved September 25, 2019, from http://www.co.middlesex.va.us/middlesex_precincts.html
#### 121 Montgomery County
Montgomery County Voter Registration. (n.d.). Voting Districts. Retrieved September 19, 2019, from https://www.montva.com/departments/voter-registration/maps-precincts-districts
#### 125 Nelson County
Election District Map for Nelson County, VA. (2011, July 12). Retrieved from http://www.nelsoncounty-va.gov/wp-content/uploads/Election_RoadMap_92_neatline21.pdf
#### 127 New Kent County
New Kent County Virginia Districts, Precincts & Polling Places. (2011, August 5). Retrieved from http://www.nelsoncounty-va.gov/wp-content/uploads/Election_RoadMap_92_neatline21.pdf
#### 131 Northampton County
Northampton County Voting Districts September 2018. (2018, September). Retrieved from https://www.co.northampton.va.us/UserFiles/Servers/Server_14877142/File/Government/Departments_Elected Offices/Voter Registration and Elections/map Voting Districts and polling places 2018.pdf
#### 133 Northumberland County
Northumberland County Board of Supervisors. Precinct Boundaries, 9–6 § (2018). Northumberland County Code of Ordinances. Retrieved from https://ecode360.com/7758608
#### 135 Nottoway County

#### 139 Page County
Page County GIS Office. (2017, April). Page County Voting District Maps. Retrieved from https://www.pagecounty.virginia.gov/309/Voting-District-Maps
#### 141 Patrick County
West Piedmont Planning District Commission. (2013, June). Patrick County Voting District & Precincts. Retrieved from https://www.co.patrick.va.us/content/uploads/PDF/2013 Voting Precinct map.pdf
#### 143 Pittsylvania County
Whitt, T. (2011, August 10). Pittsylvania County Polling Precincts - 2011. Retrieved from https://www.pittsylvaniacountyva.gov/DocumentCenter/View/285/Polling-Precincts-PDF
#### 145 Powhatan County
Powhatan County GIS. (2019, August 17). Voting Districts Shapefile. Retrieved from http://www.powhatanva.gov/1656/Download-GIS-Data
#### 147 Prince Edward County
Prince Edward County Voter Registrar. (2011, March 8). Prince Edward County Final Approved Redistricting Plan. Retrieved from http://www.co.prince-edward.va.us/pdf/REDISTRICTING - PEApprovedFinalPlan.pdf
#### 149 Prince George County
Prince George GIS Office. (2011, June 8). Map of the Voting Precincts in Prince George County. Retrieved from https://www.princegeorgeva.org/departments/registrar_s_office/map_of_county_precincts.php
#### 153 Prince William County
Prince William County GIS Office. (2019, February 13). Voting Precincts. Retrieved from https://gisdata-pwcgov.opendata.arcgis.com/datasets/voting-precincts
#### 155 Pulaski County
Pulaski County, Virginia Precinct Map. (n.d.). Retrieved September 24, 2019, from http://pulaskicounty.org/documents/registrar/county-precinct.pdf
#### 157 Rappahannock County
Rappahannock-Rapidan Regional Commission. (2013, May 28). Rappahannock County Voting District Boundaries. Retrieved from http://www.rappahannockcountyva.gov/documents/District Map as of 2013.pdf
#### 159 Richmond County
Richmond County Voter Registration Office. (2011, April 25). Voting District Boundaries. Retrieved from https://co.richmond.va.us/pdf/Adopted-4-25-2011.pdf
#### 161 Roanoke County
Roanoke County Open Data. (2019, September 20). Voting Precincts. Retrieved from https://data.roanokecountyva.gov/datasets/voting-precincts
#### 163 Rockbridge County
Rockbridge County Board of Supervisors. Precinct boundaries., 11–33 § (2013). Lexington, Virginia: Rockbridge County Code. Retrieved from http://www.co.rockbridge.va.us/DocumentCenter/View/212/Chapter11
#### 165 Rockingham County
Rockingham County GIS. (n.d.). Election Districts. Retrieved September 24, 2019, from https://www.rockinghamcountyva.gov/659/GIS-Data-Downloads

Rockingham County Board of Supervisors. Ordinance No. PCO 18-10, 6A-6–7 § (2018). Harrisonburg, Virginia: Rockingham County Code. Retrieved from https://library.municode.com/va/rockingham_county/ordinances/code_of_ordinances?nodeId=909700
#### 167 Russell County

#### 169 Scott County
Scott County Virginia E-911/GIS. (n.d.). Scott County election precincts. Retrieved September 26, 2019, from http://www.scottcountyva.com/ScottCountyElectionPrecincts.pdf

Scott County Virginia E-911/GIS. (n.d.). Scott County election districts. Retrieved September 26, 2019, from http://www.scottcountyva.com/ScottCountyElectionDistricts.pdf

#### 171 Shenandoah County
Shenandoah County GIS. (2013, November 18). Election Districts & Precinct Boundaries. Retrieved from http://shenandoahcountyva.us/voting/wp-content/uploads/sites/18/2013/11/ElectionPrecinctsDistricts2014map_11x17.pdf
#### 173 Smyth County
Smyth County GIS. (2011). Smyth County Voting Districts and Precincts. Retrieved from http://www.smythcounty.org/voter_registrar/map_voting_dist_precincts.pdf
#### 175 Southampton County
Southampton County Board of Supervisors. (2011, April 25). Meeting Minutes. Retrieved from https://www.southamptoncounty.org/document_center/BOS/2011/BOS%20Minutes_04-25-11.pdf
#### 177 Spotsylvania County
Spotsylvania County, Virginia Voting District Maps. (n.d.). Retrieved September 24, 2019, from http://www.spotsylvania.va.us/262/Voting-District-Maps
#### 179 Stafford County
Stafford County GIS Office. (2013, September 5). Stafford County Districts, Precincts & Polling Locations. Retrieved from https://staffordcountyva.gov/DocumentCenter/View/1074/New-Election-Districts-Precincts
#### 181 Surry County
Surry County Board of Supervisors. Election districts, precincts, and places (2011). Surry, Virginia: Surry County Code of Ordinances. Retrieved from https://library.municode.com/va/surry_county/codes/code_of_ordinances?nodeId=PTIGEOR_CH8EL_ARTIIELDIPRPL
#### 183 Sussex County

#### 185 Tazewell County
Tazewell County GIS Viewer. (n.d.). Retrieved September 24, 2019, from http://gis.tazewellcounty.org/tazewellcountygis/
#### 187 Warren County
Warren County GIS Office. (2015). Warren County, VA Election Districts. Retrieved from https://www.warrencountyva.net/images/Voter_Locations__Precincts_2015.pdf
#### 191 Washington County
Washington County GIS. (2011, June 15). Election District Maps. Retrieved from https://www.washcova.com/government/voter-registrar/election-district-maps/
#### 193 Westmoreland County
Voting Districts for Westmoreland County, Virginia. (2016). Retrieved from https://www.westmoreland-county.org/sites/default/files/sites/default/files/wc_vot_district.pdf
#### 195 Wise County
Wise County Geographic Information Sciences Department. (2019, July). Wise County GIS Map. Retrieved from https://www.webgis.net/va/Wise/

Wise County Board of Supervisors. Precincts and polling places (2011). Wise, Virginia: Wise County Code of Ordinances. Retrieved from https://library.municode.com/va/wise_county/codes/code_of_ordinances?nodeId=COCO_CH6EL_ARTIIIPRPOPL
#### 197 Wythe County
Wythe County, Virginia - iGIS. (2019). Retrieved from http://wythe.interactivegis.com/index.php
#### 199 York County
York County, Virginia Election District Maps. (n.d.). Retrieved September 24, 2019, from https://www.yorkcounty.gov/666/Election-District-Maps
#### 510 Alexandria City
Open Data Group for the City of Alexandria Virginia. (2019, July 25). City of Alexandria, Virginia voting precincts. Retrieved from https://cityofalexandria-alexgis.opendata.arcgis.com/datasets/voting-precincts

Proposed Precinct Changes in Alexandria. (2015, November 20). Retrieved from https://www.alexandriava.gov/news_display.aspx?id=82566
#### 515 Bedford City
Bedford Town Council. Town wards and polling places, 2–451 § (2005). Bedford, Virginia: Bedford Code of Ordinances. Retrieved from https://library.municode.com/va/bedford/codes/code_of_ordinances?nodeId=PTIITHCO_CH2AD_ARTVIEL_S2-451TOWAPOPL
#### 520 Bristol City
Bristol City Council. Elections, Article II. Wards, 30-26–29 § (2013). Bristol, Virginia: Bristol Code of Ordinances. Retrieved from https://library.municode.com/va/bristol/codes/code_of_ordinances?nodeId=PTIICO_CH30EL_ARTIIWA
#### 530 Buena Vista City
Buena Vista City Council. Elections, Article III. Wards, 12-42–44 § (1981). Buena Vista, Virginia: Buena Vista Code of Ordinances. Retrieved from https://library.municode.com/va/buena_vista/codes/code_of_ordinances?nodeId=PTIICOOR_CH12EL_ARTIIIWA
#### 540 Charlottesville City
Charlottesville Open Data. (2018, January 12). City of Charlottesville Voting Precinct Boundaries. Retrieved from https://opendata.charlottesville.org/datasets/voting-precinct-area
#### 550 Chesapeake City
City of Chesapeake. (2019). Chesapeake Precinct Changes. Retrieved from http://www.cityofchesapeake.net/government/city-departments/departments/Voter-Registrar/precincts/Chesapeake-Precinct-Changes.htm

Chesapeake Virginia GIS. (2019, September 19). Voting precincts in the City of Chesapeake. Retrieved from https://public-chesva.opendata.arcgis.com/datasets/739d17a0c6f94d2b948843763ada43a1_0
#### 570 Colonial Heights City
City of Colonial Heights Virginia Voting Precincts Map. (2012, June 25). Retrieved from https://www.colonialheightsva.gov/DocumentCenter/View/1163/Colonial-Heights-Voting-Precincts
#### 580 Covington City
Covington City Council. Electoral district boundaries, 16–21 § (1991). Covington, Virginia: Covington Code of Ordinances. Retrieved from https://library.municode.com/va/covington/codes/code_of_ordinances?nodeId=PTIICOOR_CH16EL_ARTIIELDI_S16-21ELDIBO
#### 595 Emporia City
City of Emporia Voter Registrar. (n.d.). Emporia Voting Districts. Retrieved September 26, 2019, from https://www.ci.emporia.va.us/sites/emporiava/files/uploads/votingdistricts.pdf
#### 600 Fairfax City
City of Fairfax Virginia. (n.d.). City Polling Locations. Retrieved September 25, 2019, from https://www.fairfaxva.gov/government/voter-registration/how-to-vote/city-polling-locations
#### 610 Falls Church City
Falls Church City Council. Elections, 2-21–25 § (2011). Falls Church, Virginia: Falls Church Code of Ordinances. Retrieved from https://library.municode.com/va/falls_church/codes/code_of_ordinances?nodeId=PTIICOOR_CH2AD_ARTIIEL
#### 620 Franklin City

#### 630 Fredericksburg City
City of Fredericksburg, VA Map of Wards. (2019, May 30). Retrieved September 25, 2019, from https://www.fredericksburgva.gov/DocumentCenter/View/15313/Official-Wards_24X36_2019
#### 640 Galax City

#### 650 Hampton City
City of Hampton Precinct Information. (2019, May 6). Retrieved from https://hampton.gov/DocumentCenter/View/1422/PRECINCT-INFORMATION

Hampton, Virginia 2nd and 3rd Congressional Districts. (2014, October 6). Retrieved from https://hampton.gov/DocumentCenter/View/1423/2nd-and-3rd-Congressional-Districts
#### 660 Harrisonburg City
City of Harrisonburg Voter Registrar. (n.d.). Voting Districts & Precincts. Retrieved September 25, 2019, from https://harrisonburg.maps.arcgis.com/apps/webappviewer/index.html?id=76fd384bc4c54343b366478566191928
#### 670 Hopewell City
Hopewell City Council. Election districts, 13-22–28 § (2011). Hopewell, Virginia: Hopewell Code of Ordinances. Retrieved from https://library.municode.com/va/hopewell/codes/code_of_ordinances?nodeId=COCI_CH13EL_ARTIIELDI
#### 678 Lexington City

#### 680 Lynchburg City
City of Lynchburg GIS. (2017, November 22). Voting Precincts. Retrieved from http://data-cityoflynchburg.opendata.arcgis.com/datasets/voting-precincts
#### 683 Manassas City
Manassas City Council. Precincts established, 50–1 § (2017). Manassas, Virginia: Manassas Code of Ordinances. Retrieved from https://library.municode.com/va/manassas/codes/code_of_ordinances?nodeId=PTIICOOR_CH50EL_S50-1PRES
#### 685 Manassas Park City
Manassas Park City Council. Voting Places, 2–2 § (2015). Manassas Park, Virginia: Manassas Park Code of Ordinances. Retrieved from https://library.municode.com/va/manassas_park/codes/code_of_ordinances?nodeId=COCI_CH2AD_ARTIINGE_S2-2VOPL
#### 690 Martinsville City

#### 700 Newport News City
City of Newport News Virginia. (2019). Newport News Election Locations. Retrieved from https://nngov.maps.arcgis.com/apps/webappviewer/index.html?id=d0e4156f13434b6abded2affd5cdd1b4
#### 710 Norfolk City
City of Norfolk GIS. (2019, June 27). Election Precincts. Retrieved from http://norfolkgisdata-orf.opendata.arcgis.com/datasets/election-precincts
#### 720 Norton City
Norton City Council. Elections, 6 § (2007). Norton, Virginia: Norton Code of Ordinances. Retrieved from https://library.municode.com/va/norton/codes/code_of_ordinances?nodeId=CO_CH6EL
#### 730 Petersburg City
City of Petersburg, VA Ward Map and Polling Centers. (n.d.). Retrieved from http://www.petersburg-va.org/DocumentCenter/View/4671/WardMap
#### 735 Poquoson City
Poquoson City Council. Precincts, 30–1 § (2011). Poquoson, Virginia. Retrieved from https://library.municode.com/va/poquoson/codes/code_of_ordinances?nodeId=PTIICOOR_CH30EL_S30-1PR
#### 740 Portsmouth City
Portsmouth, Virginia House Districts & Polling Locations. (2019). Retrieved from http://portsmouthva.gov/DocumentCenter/View/6489/House-Districts-2019
#### 750 Radford City
Ordinance Establishing New Precinct and Polling Place (New River Precinct). (2018). Retrieved from https://www.radfordva.gov/DocumentCenter/View/3062/Ordinance-Establishing-New-Precinct-and-Polling-Place-New-River-Precinct-1707
#### 760 Richmond City
City of Richmond GIS. (2019, February 3). Election Districts. Retrieved from ftp://ftp.ci.richmond.va.us/GIS/Shapefiles/
#### 770 Roanoke City
City of Roanoke GIS. (2019, August 5). Voting Precincts. Retrieved from ftp://ftp.roanokeva.gov/GIS/Shapefiles/

City of Roanoke GIS. (2015, October 29). Voter Precinct Map, Engineering Plan 6754. Retrieved from https://www.roanokeva.gov/DocumentCenter/View/3784/Voter-Precincts-Map

City of Roanoke GIS. (2011, August 22). Voter Precincts & House of Delegates Districts. Retrieved from https://www.roanokeva.gov/DocumentCenter/View/787/Voter-Precincts-Map-PDF
#### 775 Salem City
City of Salem GIS Systems. (2018, December 14). Voting Precincts. Retrieved from https://data-salemva.opendata.arcgis.com/datasets/834bb3271e0640db8bd1bb18fbe121f1_0
#### 790 Staunton City
Staunton GIS Coordinator. (2017, November). Voting Wards. Retrieved from https://www.ci.staunton.va.us/home/showdocument?id=2234
#### 800 Suffolk City
City of Suffolk Registrar. (n.d.). Borough & Precinct Maps. Retrieved September 25, 2019, from http://www.suffolkva.us/854/Borough-Precinct-Maps
#### 810 Virginia Beach City
Virginia Beach Center for GIS. (2019, May 13). Precinct Boundaries. Retrieved from https://gis.data.vbgov.com/datasets/7cae00e39a684380b7aa912b3d6c9d55?layer=1
#### 820 Waynesboro City
Waynesboro City Council. Election districts; voting places, 1–13 § (2017). Waynesboro, Virginia: Waynesboro Code of Ordinances. Retrieved from https://library.municode.com/va/waynesboro/codes/code_of_ordinances?nodeId=PTIICO_CH1GEPR_S1-13ELDIVOPL
#### 830 Williamsburg City
City of Williamsburg GIS Data Share. (2019, May 24). Voter Precinct by Parcel. Retrieved from https://data-williamsburg.opendata.arcgis.com/datasets/citygdb-dbo-votprecnctbyparcel
#### 840 Winchester City
City of Winchester Open Data Initiative Open Data Group. (2019, February 13). Voting Precincts. Retrieved from http://city-of-winchester-open-data-1-winchestercity.hub.arcgis.com/datasets/voting-precincts
