mountaincrowdmap
================

Advanced Collaberative Mountain Runners App (GIS)

Purpose :
An app designed for serious Alpine mountain runners to share GPX tracks online. Theoretically this app serves a 
dual purpose as a hiking tool, mountaineering resource, and possible a Search and Rescue (SAR) Asset.

Framework Technologies :
USGS Topographical Data Sets : for maps to display accurate mapping of mountain regions.
Open Data Kit (ODK) : for mobile updates.
Openlayers : for displaying map data on web.

Languages and Database Technologies :
PostgreSQL, PostGIS, SQLite, JavaScript, Java, Objective C,  

Preliminary GIS Decisions :
Google Maps and Bing Maps bring little to the table for this project other than a fast depricating API
and arbitrary TOS and EULA. Sidestepping these products is a primary objective. Accessing equivical maps
is possible by accessing open map systems developed for the US Geological Survey (USGS). USGS has
accumulated a great data-set with sufficient elevation and terrain detail. Optional layers include 
NASA's Jet Propulsion Labratories (NASA-JPL) Shuttle Radar Topography Mission (SRTM) scans. 



"SRTM consisted of a specially modified radar system that flew onboard the Space Shuttle Endeavour during 
an 11-day mission in February of 2000."
http://www2.jpl.nasa.gov/srtm/

