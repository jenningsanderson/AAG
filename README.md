EPIC-OSM and OMSDOWN Examples for 2015 AAG Annual Meeting
======================



####Contains Data for the following samples:
- Boulder 2013 - 2014
- Chicago April 2015
- Haiti Earthquake
- Typhoon Yolanda
- Tacloban, Philippines (During Typhoon Yolanda)


##Directory: analysis_windows
Individual Analysis Windows for each of these files for epic-osm

####Step 1: Cut file and import:

	rake new analysis_wndows/boulder_2013-2014.yml
	
####Step 2: Run Questions: 

	rake questions:all analysis_windows/boulder_2013-2014.yml

##Directory: osmdown_files
OpenStreetMap Markdown files for osmdown:

####Build the Site

	osmdown build osmdown_files/boulder.osmdown

