# virginia-voting-precincts
## Virginia voting precinct maps 2011-2020
The 2019-2020 maps reflect the Virginia voting precinct boundaries for the 2019 June Primary, 2019 November General, 2020 March Presidential Primary, 2020 June Primary, and 2020 November General Elections. Shapefiles will be added for all election years from 2011-2020.
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
* hodDist - (For maps older than 2019) House of Delegates district current for the map year.
* hodDist17 - (2019-2020 map only) House of Delegates district prior to the new district maps adopted on 29 Jan 2019.
* hodDist19 - (2019-2020 map only) House of Delegates district according to the Final Remedial plan adopted on 29 Jan 2019.
* actVoters - Number of active registered voters in the precinct (or split precinct portion) at the time of the election.
* preUid - PrecinctUid given in the .csv files of Individual Election Results from the Virginia Department of Elections. These will not be completely updated for the 2019-2020 maps until 2019 November General Election results are released.
* locUid - LocalityUid given in the .csv files of Individual Election Results from the Virginia Department of Elections.
* changeDate - Date of last known change to the precinct boundaries, name or number.
* lastChange - Last known change to the precinct boundaries, name or number.
## Split Precinct Maps
Virginia has many election precincts that are split by Congressional, State Senate, or House of Delegates district boundaries. These maps are the same as the voting precinct shapefiles, but split precincts are shown as separate features so that election results can be mapped by both precinct and district.
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
#### 	1	Accomack County
Accomack County Department of Planning and Community Development. (2011, March 26). Accomack County Virginia Precincts and Polling Locations. Retrieved from https://www.co.accomack.va.us/departments/registrar/precincts-and-polling-locations		
#### 	3	Albemarle County
Albemarle County Office of Geographic Data Services. (2019, February 9). Voter Precincts. Retrieved from http://www.albemarle.org/department.asp?department=gds&relpage=3914#Political		
		
Wrabel, A. (2018, March 14). Albemarle supervisors OK changes to some voting precincts. Retrieved from https://www.dailyprogress.com/news/local/albemarle-supervisors-ok-changes-to-some-voting-precincts/article_49186dc8-27f2-11e8-a426-9fcb0dc095f6.html		
#### 	5	Alleghany County
Alleghany County 2011 districts and precincts. (2011). Retrieved from http://www.co.alleghany.va.us/wp-content/uploads/2016/08/magisterial.districts.pdf		
#### 	11	Appomattox County
Appomattox County Virginia 2011 Redistricting Map. (2011, April 25). Retrieved from http://www.appomattoxcountyva.gov/home/showdocument?id=40		
#### 	13	Arlington County
Arlington County GIS Mapping Center. (2019, September 19). Arlington County, Va Voter Precinct Polygons. Retrieved from https://gisdata-arlgis.opendata.arcgis.com/datasets/voter-precinct-polygons		
#### 	19	Bedford County
Bedford County GIS Department. (2018, August 2). Bedford County Voting Precincts. Retrieved from https://geohub-bedfordvagis.opendata.arcgis.com/datasets/voting-precincts		
#### 	23	Botetourt County
Botetourt County GIS Department. (2016, March). Botetourt County Virginia Voting Precincts. Retrieved from https://botetourtva.gov/botetourt/wp-content/uploads/2019/04/2016_Precincts_8x11.pdf		
		
Hammack, L. (2015, February 24). Botetourt County reduces voting precincts to save money. Retrieved from https://www.roanoke.com/news/local/botetourt-county-reduces-voting-precincts-to-save-money/article_7202555d-fc29-5d74-b7f9-a1766175adf8.html		
#### 	25	Brunswick County
Brunswick County Virginia Board of Supervisors. (n.d.). Election District Map. Retrieved September 19, 2019, from https://www.brunswickco.com/government/board_of_supervisors/election_district_map		
#### 	31	Campbell County
Campbell County GIS Office. (2019, July 2). Voting Precincts. Retrieved from https://data-campbellva.opendata.arcgis.com/datasets/843401e26d244a869543bd2a8443deb9_0		
#### 	33	Caroline County
Caroline County Election Districts and Precinct Boundaries. (2012, July 10). Retrieved from https://co.caroline.va.us/DocumentCenter/View/506/Election-District-Map-PDF		
#### 	41	Chesterfield County
Voting Precinct Boundaries in Chesterfield County, VA. (2019, September 18). Retrieved from http://opengeospace.chesterfield.gov/datasets/349dce35948843289e85e1a18ade455e_1		
		
Soptelean, C. M. (2019, January 15). County looking to create five new voting precincts. Retrieved from http://villagenewsonline.com/2019/01/15/county-looking-to-create-five-new-voting-precincts/		
#### 	47	Culpeper County
Culpeper County Virginia Voting Precinct Map. (2019, March 6). Retrieved from http://www.voteinculpeper.info/map-expanded/		
#### 	51	Dickenson County
Dickenson County Board of Supervisors. (2013, March 26). Meeting Minutes - Public Hearing. Retrieved from https://www.dickensonva.org/DocumentCenter/View/1658/BoS-Minutes---2013---0326---Public-Hearing		
		
Dickenson County Board of Supervisors. (2013, February 23). Meeting Minutes. Retrieved from https://www.dickensonva.org/DocumentCenter/View/1655/BoS-Minutes---2013---0226		
		
Dickenson County Board of Supervisors. (2011, August 23). Ordinance Book No. 2. Retrieved from https://dickensonva.org/DocumentCenter/View/17/Ordinance-Book-2		
#### 	53	Dinwiddie County
Dinwiddie County, Virginia 2012 Approved Precincts Based on 2010 Census Data. (2012). Retrieved from https://www.dinwiddieva.us/DocumentCenter/View/1592/Dinwiddie_Approved_Districts_2012		
#### 	57	Essex County
Middle Peninsula Planning District Commission. (2011, July 14). Essex County, Virginia New Voting Districts - 2011. Retrieved from http://www.essex-virginia.org/UserFiles/Servers/Server_62876/Image/Essex 2011 New Voting Districts - Area of Change 7-22-11.pdf		
#### 	59	Fairfax County
Fairfax County Office of Elections. (2019). Polling Places. Retrieved from https://www.fairfaxcounty.gov/elections/precincts		
		
Fairfax County Open Data. (2019, September 14). Voting Precincts. Retrieved from https://data-fairfaxcountygis.opendata.arcgis.com/datasets/7727de78b3984f4daa1ff0960d0da8cb_1		
#### 	61	Fauquier County
Fauquier County GIS. (2016, May 11). Voting Precincts Shapefile. Retrieved from ftp://vm-ftp.fauquiercounty.gov/		
#### 	65	Fluvanna County
Fluvanna County, VA Geographic Information System. (n.d.). Retrieved September 24, 2019, from https://www.webgis.net/va/fluvanna/		
#### 	67	Franklin County
Franklin County Virginia Precinct Maps. (n.d.). Retrieved September 19, 2019, from http://www.franklincountyva.gov/voter-registrar-precinct-maps		
#### 	69	Frederick County
Frederick County Virginia Voter Registration Office. (n.d.). Frederick County Polling Place. Retrieved September 19, 2019, from https://fredcogis.fcva.us/ElectionPollingPlace/		
#### 	75	Goochland County
Goochland County Virginia Official Electoral Map. (2013). Retrieved from https://www.goochlandva.us/DocumentCenter/View/477/Goochland-County-Voting-Districts-PDF		
#### 	83	Halifax County
Ready to vote? Some precincts have moved in Halifax County. (2017, October 31). Retrieved from http://www.yourgv.com/news/local_news/ready-to-vote-some-precincts-have-moved-in-halifax-county/article_5c9efd78-be78-11e7-a3b0-ff7937a00896.html		
#### 	85	Hanover County
Hanover County GIS. (2015). Hanover County Voting Precinct Map. Retrieved from https://www.hanovercounty.gov/DocumentCenter/View/1373/Hanover-County-Election-Districts-Map-PDF		
#### 	87	Henrico County
Henrico County GIS Office. (2019, August 26). Voting Precincts. Retrieved from https://data-henrico.opendata.arcgis.com/datasets/voting-precincts		
		
Henrico County Board of Supervisors Public Meeting. (2019, November 25). Retrieved from https://www.richmond.com/classifieds/community/announcements/legal/henrico-county-board-of-supervisors-public-meeting/ad_105eccb6-d1f4-5f6a-88f7-a5e5ff6c2ec1.html		
#### 	89	Henry County
Henry County Board of Supervisors. (2011, January 2). Organizational Meeting Minutes. Retrieved from https://www.henrycountyva.gov/content/uploads/PDF/2011_Board_of_Supervisors_Board_Packets/bos_minutes_2012.pdf		
#### 	93	Isle Of Wight County
Isle of Wight County – Election Districts, Precincts, and Polling Locations. (n.d.). Retrieved from http://www.co.isle-of-wight.va.us/voter-registration/districts-precincts-and-polling-locations/		
#### 	95	James City County
James City County Voting Precincts. (2019, March 12). Retrieved September 19, 2019, from https://opendata-jcc.opendata.arcgis.com/datasets/b61f172ab29e4db38d3ac7c9e6015d83_26		
		
James City County GIS Office. (2017, July 10). Voting Precincts State Senate and House Districts. Retrieved from https://jamescitycountyva.gov/DocumentCenter/View/459/Precincts--House-Districts-Map-PDF		
#### 	97	King & Queen County
King & Queen County Registrar. (n.d.). Precincts and Polling Places. Retrieved September 19, 2019, from http://www.kingandqueenco.net/html/Govt/registrar.html		
#### 	99	King George County
King George County GIS. (2019, March 4). Voting Precinct. Retrieved from https://data-king-george.opendata.arcgis.com/datasets/voting-precinct		
#### 	101	King William County
Brooks, B. (2016, March). King William County Supervisor/Voting Precinct Map. Retrieved from https://kingwilliamcounty.us/wp-content/uploads/2014/01/2014_SupervisorMap1.pdf		
#### 	105	Lee County
Lee County Board of Supervisors. (2013, March 19). Meeting Minutes. Retrieved from http://www.leecova.org/Minutes/2013/Minutes 3-19-13 Regular Meeting.pdf		
#### 	107	Loudoun County
Loudoun County Open Data Group. (2019, April 9). Loudoun Election Precincts. Retrieved from https://geohub-loudoungis.opendata.arcgis.com/datasets/ef2c7c42a1ca441fa839426cf1481a50_3		
		
LoudounNow. (2018, April 18). Leesburg Voting Precincts Relocated. Retrieved from https://loudounnow.com/2018/04/18/leesburg-voting-precincts-relocated/		
#### 	109	Louisa County
Louisa County Voter Registrar. (2017, November 20). Voting Districts and Precincts. Retrieved from https://www.louisacounty.com/1142/Voting-Districts-and-Precincts		
#### 	115	Mathews County
Mathews County Voter Registrar. (n.d.). Mathews County, VA Voting Precincts. Retrieved September 19, 2019, from http://www.mathewscountyva.gov/government/voter-registrar-s-office/precinct-information		
#### 	117	Mecklenburg County
Mecklenburg County Registrar’s Office. (2011). Mecklenburg County, Virginia Voter District Map 2011. Retrieved from https://www.mecklenburgva.com/voter-district-map.aspx		
#### 	119	Middlesex County
Middlesex County, Virginia 2016 Voting Precinct Map. (n.d.). Retrieved September 25, 2019, from http://www.co.middlesex.va.us/middlesex_precincts.html		
#### 	121	Montgomery County
Montgomery County Voter Registration. (n.d.). Voting Districts. Retrieved September 19, 2019, from https://www.montva.com/departments/voter-registration/maps-precincts-districts		
		
Gangloff, M. (2014, December 26). Del. Joseph Yost proposes rejoining split precincts in Montgomery County. Retrieved from https://www.roanoke.com/news/local/montgomery_county/del-joseph-yost-proposes-rejoining-split-precincts-in-montgomery-county/article_d4a2e017-5594-5ee3-a63a-78230f2d0ed1.html		
		
Gordon, M. (2014, June 10). On-campus voting location approved by Board of Supervisors. Retrieved from http://www.collegiatetimes.com/news/on-campus-voting-location-approved-by-board-of-supervisors/article_79ff1e72-f0b1-11e3-86d3-0017a43b2370.html		
#### 	125	Nelson County
Election District Map for Nelson County, VA. (2011, July 12). Retrieved from http://www.nelsoncounty-va.gov/wp-content/uploads/Election_RoadMap_92_neatline21.pdf		
#### 	127	New Kent County
New Kent County Virginia Districts, Precincts & Polling Places. (2011, August 5). Retrieved from http://www.nelsoncounty-va.gov/wp-content/uploads/Election_RoadMap_92_neatline21.pdf		
#### 	131	Northampton County
Northampton County Voting Districts September 2018. (2018, September). Retrieved from https://www.co.northampton.va.us/UserFiles/Servers/Server_14877142/File/Government/Departments_Elected Offices/Voter Registration and Elections/map Voting Districts and polling places 2018.pdf		
#### 	139	Page County
Page County GIS Office. (2017, April). Page County Voting District Maps. Retrieved from https://www.pagecounty.virginia.gov/309/Voting-District-Maps		
#### 	141	Patrick County
West Piedmont Planning District Commission. (2013, June). Patrick County Voting District & Precincts. Retrieved from https://www.co.patrick.va.us/content/uploads/PDF/2013 Voting Precinct map.pdf		
#### 	143	Pittsylvania County
Whitt, T. (2011, August 10). Pittsylvania County Polling Precincts - 2011. Retrieved from https://www.pittsylvaniacountyva.gov/DocumentCenter/View/285/Polling-Precincts-PDF		
#### 	145	Powhatan County
Powhatan County GIS. (2019, August 17). Voting Districts Shapefile. Retrieved from http://www.powhatanva.gov/1656/Download-GIS-Data		
#### 	149	Prince George County
Prince George GIS Office. (2011, June 8). Map of the Voting Precincts in Prince George County. Retrieved from https://www.princegeorgeva.org/departments/registrar_s_office/map_of_county_precincts.php		
#### 	153	Prince William County
Prince William County GIS Office. (2019, February 13). Voting Precincts. Retrieved from https://gisdata-pwcgov.opendata.arcgis.com/datasets/voting-precincts		
		
Sides, E. (2019, February 7). Prince William County splits up largest election precincts. Retrieved from https://www.insidenova.com/news/prince_william/prince-william-county-splits-up-largest-election-precincts/article_7568f5a8-2a46-11e9-b841-6b729f881c28.html		
#### 	155	Pulaski County
Pulaski County, Virginia Precinct Map. (n.d.). Retrieved September 24, 2019, from http://pulaskicounty.org/documents/registrar/county-precinct.pdf		
#### 	157	Rappahannock County
Rappahannock-Rapidan Regional Commission. (2013, May 28). Rappahannock County Voting District Boundaries. Retrieved from http://www.rappahannockcountyva.gov/documents/District Map as of 2013.pdf		
#### 	159	Richmond County
Richmond County Voter Registration Office. (2011, April 25). Voting District Boundaries. Retrieved from https://co.richmond.va.us/pdf/Adopted-4-25-2011.pdf		
#### 	161	Roanoke County
Roanoke County Open Data. (2019, September 20). Voting Precincts. Retrieved from https://data.roanokecountyva.gov/datasets/voting-precincts		
		
Petska, A. (2019, January 22). Roanoke County votes to change two of its largest precincts. Retrieved from https://www.roanoke.com/news/local/roanoke-county-votes-to-change-two-of-its-largest-precincts/article_8ff7c57a-d00b-50e2-8a35-3b4ef6d0ef27.html		
#### 	165	Rockingham County
Rockingham County GIS. (n.d.). Election Districts. Retrieved September 24, 2019, from https://www.rockinghamcountyva.gov/659/GIS-Data-Downloads		
		
Casey, M. (2018, August 27). Bridgewater voting precinct to split in two. Retrieved from https://www.whsv.com/content/news/Bridgewater-voting-precinct-to-split-in-two-491804791.html		
#### 	171	Shenandoah County
Shenandoah County GIS. (2013, November 18). Election Districts & Precinct Boundaries. Retrieved from http://shenandoahcountyva.us/voting/wp-content/uploads/sites/18/2013/11/ElectionPrecinctsDistricts2014map_11x17.pdf		
#### 	173	Smyth County
Smyth County GIS. (2011). Smyth County Voting Districts and Precincts. Retrieved from http://www.smythcounty.org/voter_registrar/map_voting_dist_precincts.pdf		
#### 	177	Spotsylvania County
Spotsylvania County, Virginia Voting District Maps. (n.d.). Retrieved September 24, 2019, from http://www.spotsylvania.va.us/262/Voting-District-Maps		
#### 	179	Stafford County
Stafford County GIS Office. (2013, September 5). Stafford County Districts, Precincts & Polling Locations. Retrieved from https://staffordcountyva.gov/DocumentCenter/View/1074/New-Election-Districts-Precincts		
#### 	185	Tazewell County
Tazewell County GIS Viewer. (n.d.). Retrieved September 24, 2019, from http://gis.tazewellcounty.org/tazewellcountygis/		
		
Boothe, C. (2018, June 25). Tazewell advancing plan to consolidate several voting precincts. Retrieved from https://www.bdtonline.com/news/local_news/tazewell-advancing-plan-to-consolidate-several-voting-precincts/article_fc26a606-168b-5d5c-a475-1b61f35a538b.html		
#### 	187	Warren County
Warren County GIS Office. (2015). Warren County, VA Election Districts. Retrieved from https://www.warrencountyva.net/images/Voter_Locations__Precincts_2015.pdf		
#### 	191	Washington County
Washington County GIS. (2011, June 15). Election District Maps. Retrieved from https://www.washcova.com/government/voter-registrar/election-district-maps/		
#### 	193	Westmoreland County
Voting Districts for Westmoreland County, Virginia. (2016). Retrieved from https://www.westmoreland-county.org/sites/default/files/sites/default/files/wc_vot_district.pdf		
#### 	197	Wythe County
Wythe County, Virginia - iGIS. (2019). Retrieved from http://wythe.interactivegis.com/index.php		
#### 	199	York County
York County, Virginia Election District Maps. (n.d.). Retrieved September 24, 2019, from https://www.yorkcounty.gov/666/Election-District-Maps		
#### 	510	Alexandria City
Open Data Group for the City of Alexandria Virginia. (2019, July 25). City of Alexandria, Virginia voting precincts. Retrieved from https://cityofalexandria-alexgis.opendata.arcgis.com/datasets/voting-precincts		
		
Proposed Precinct Changes in Alexandria. (2015, November 20). Retrieved from https://www.alexandriava.gov/news_display.aspx?id=82566		
#### 	540	Charlottesville City
Charlottesville Open Data. (2018, January 12). City of Charlottesville Voting Precinct Boundaries. Retrieved from https://opendata.charlottesville.org/datasets/voting-precinct-area		
#### 	550	Chesapeake City
City of Chesapeake. (2019). Chesapeake Precinct Changes. Retrieved from http://www.cityofchesapeake.net/government/city-departments/departments/Voter-Registrar/precincts/Chesapeake-Precinct-Changes.htm		
		
Chesapeake Virginia GIS. (2019, September 19). Voting precincts in the City of Chesapeake. Retrieved from https://public-chesva.opendata.arcgis.com/datasets/739d17a0c6f94d2b948843763ada43a1_0		
#### 	570	Colonial Heights City
City of Colonial Heights Virginia Voting Precincts Map. (2012, June 25). Retrieved from https://www.colonialheightsva.gov/DocumentCenter/View/1163/Colonial-Heights-Voting-Precincts		
#### 	600	Fairfax City
City of Fairfax Virginia. (n.d.). City Polling Locations. Retrieved September 25, 2019, from https://www.fairfaxva.gov/government/voter-registration/how-to-vote/city-polling-locations		
#### 	630	Fredericksburg City
City of Fredericksburg, VA Map of Wards. (2019, May 30). Retrieved September 25, 2019, from https://www.fredericksburgva.gov/DocumentCenter/View/15313/Official-Wards_24X36_2019		
#### 	650	Hampton City
City of Hampton Precinct Information. (2019, May 6). Retrieved from https://hampton.gov/DocumentCenter/View/1422/PRECINCT-INFORMATION		
		
Hampton, Virginia 2nd and 3rd Congressional Districts. (2014, October 6). Retrieved from https://hampton.gov/DocumentCenter/View/1423/2nd-and-3rd-Congressional-Districts		
#### 	660	Harrisonburg City
City of Harrisonburg Voter Registrar. (n.d.). Voting Districts & Precincts. Retrieved September 25, 2019, from https://harrisonburg.maps.arcgis.com/apps/webappviewer/index.html?id=76fd384bc4c54343b366478566191928		
#### 	680	Lynchburg City
City of Lynchburg GIS. (2017, November 22). Voting Precincts. Retrieved from http://data-cityoflynchburg.opendata.arcgis.com/datasets/voting-precincts		
#### 	700	Newport News City
City of Newport News Virginia. (2019). Newport News Election Locations. Retrieved from https://nngov.maps.arcgis.com/apps/webappviewer/index.html?id=d0e4156f13434b6abded2affd5cdd1b4		
		
Mullin, M. (2018, August 24). Split precincts damage democracy. Retrieved from https://www.dailypress.com/virginiagazette/opinion/va-vg-edit-mullin-0825-story.html		
#### 	710	Norfolk City
City of Norfolk GIS. (2019, June 27). Election Precincts. Retrieved from http://norfolkgisdata-orf.opendata.arcgis.com/datasets/election-precincts		
		
Newsome, C. (2011, December 23). Norfolk looks to save by combining voting precincts. Retrieved from https://www.pilotonline.com/government/article_3208b296-df02-59b5-9b97-c44e9dd3bfbb.html		
#### 	730	Petersburg City
City of Petersburg, VA Ward Map and Polling Centers. (n.d.). Retrieved from http://www.petersburg-va.org/DocumentCenter/View/4671/WardMap		
#### 	740	Portsmouth City
Portsmouth, Virginia House Districts & Polling Locations. (2019). Retrieved from http://portsmouthva.gov/DocumentCenter/View/6489/House-Districts-2019		
#### 	750	Radford City
Ordinance Establishing New Precinct and Polling Place (New River Precinct). (2018). Retrieved from https://www.radfordva.gov/DocumentCenter/View/3062/Ordinance-Establishing-New-Precinct-and-Polling-Place-New-River-Precinct-1707		
#### 	760	Richmond City
City of Richmond GIS. (2019, February 3). Election Districts. Retrieved from ftp://ftp.ci.richmond.va.us/GIS/Shapefiles/		
		
Code of the City of Richmond Ordinance No. 2011-215-2012-4. (2012, January 9). Retrieved September 9, 2019, from ftp://ftp.ci.richmond.va.us/Redistricting2011/ExhibitB/Certified Ordinance No  2011-215-2012-4.pdf		
#### 	770	Roanoke City
City of Roanoke GIS. (2019, August 5). Voting Precincts. Retrieved from ftp://ftp.roanokeva.gov/GIS/Shapefiles/		
		
Chittum, M. (2017, December 18). Roanoke City Council votes to eliminate Virginia Heights-Norwich voting precinct. Retrieved from https://www.roanoke.com/news/local/roanoke-city-council-votes-to-eliminate-virginia-heights-norwich-voting/article_a2bd900d-4709-5090-9db4-169578dfa225.html		
		
Proposed Roanoke Voting Precinct Changes. (2017, December 17). Retrieved from https://www.roanoke.com/proposed-roanoke-voting-precinct-changes/pdf_12c57448-4e25-50ee-8725-ca626cb75880.html		
		
City of Roanoke GIS. (2015, October 29). Voter Precinct Map, Engineering Plan 6754. Retrieved from https://www.roanokeva.gov/DocumentCenter/View/3784/Voter-Precincts-Map		
		
Adams, M. (2012, November 10). Roanoke reviewing precincts, long lines. Retrieved from https://www.roanoke.com/webmin/news/roanoke-reviewing-precincts-long-lines/article_f03a947f-f9c2-59dc-83c0-01692fa2c5dc.html		
		
City of Roanoke GIS. (2011, August 22). Voter Precincts & House of Delegates Districts. Retrieved from https://www.roanokeva.gov/DocumentCenter/View/787/Voter-Precincts-Map-PDF		
#### 	775	Salem City
City of Salem GIS Systems. (2018, December 14). Voting Precincts. Retrieved from https://data-salemva.opendata.arcgis.com/datasets/834bb3271e0640db8bd1bb18fbe121f1_0		
#### 	790	Staunton City
Staunton GIS Coordinator. (2017, November). Voting Wards. Retrieved from https://www.ci.staunton.va.us/home/showdocument?id=2234		
#### 	800	Suffolk City
City of Suffolk Registrar. (n.d.). Borough & Precinct Maps. Retrieved September 25, 2019, from http://www.suffolkva.us/854/Borough-Precinct-Maps		
		
Bourne, V. (2016, January 8). Some Suffolk voters might cast ballots in new polling places this year. Retrieved from https://www.pilotonline.com/government/local/article_7c8b5aff-e5c3-5a75-81f6-a577f1e755e2.html		
		
Sheler, J. (2011, November 3). Suffolk council OKs map for new voter precincts. Retrieved from https://www.pilotonline.com/government/local/article_5bd991d5-7820-54f6-ac77-8dfa83aaadba.html		
#### 	810	Virginia Beach City
Virginia Beach Center for GIS. (2019, May 13). Precinct Boundaries. Retrieved from https://gis.data.vbgov.com/datasets/7cae00e39a684380b7aa912b3d6c9d55?layer=1		
		
Skelton, A. (2018, March 22). Two new polling places being added in Virginia Beach to deal with more voters. Retrieved from https://www.pilotonline.com/government/local/article_f065a0f0-2bad-11e8-a027-37eee602651f.html		
		
The Independent News. (2016, September 6). Creeds polling location moves to Oak Grove Baptist; boundary shift between Oceana, Red Wing precincts. Retrieved from http://princessanneindy.com/2016/09/06/elections/		
#### 	830	Williamsburg City
City of Williamsburg GIS Data Share. (2019, May 24). Voter Precinct by Parcel. Retrieved from https://data-williamsburg.opendata.arcgis.com/datasets/citygdb-dbo-votprecnctbyparcel		
#### 	840	Winchester City
City of Winchester Open Data Initiative Open Data Group. (2019, February 13). Voting Precincts. Retrieved from http://city-of-winchester-open-data-1-winchestercity.hub.arcgis.com/datasets/voting-precincts		

