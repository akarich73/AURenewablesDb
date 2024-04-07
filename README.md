# AU Renewables Database

An open source structured PostgreSQL & PostGIS database of renewable energy projects in Australia.

## Description

The goal of the AU Renewables Database is to provide a consolidated and, in so far as practicable, complete set a of 
GIS based data for renewable energy projects in Australia.

Yes, there are many other similar datasets available but imo most/all have gaps or are not maintained.

Initially this started out as a means to improving my understanding of PostgreSQL, PostGIS and QGIS. But given the time and
effort to check and fill in missing data I decided to share it for others to hopefully use and potentially contribute to.  

## Getting Started

There are a number of ways the data and/or database can be used.

1. Access online via QGISCloud
   - https://qgiscloud.com/akarich73/AURenewablesDb/?
2. Access in your GIS software of choice via WMS
   - https://qgiscloud.com/akarich73/AURenewablesDb/wms?SERVICE=WMS&REQUEST=GetCapabilities 
3. Download exported CSV from the database saved here under the Data folder
4. (TBD) Download and restore a backup of the database onto your own PostgreSQL database

How you use the data is up to you. But some ideas I have for my own work includes:
* Analysing wind turbine spacing
* Forecasting of recycling of wind turbines, PV modules, etc
* Life extension and repowering

## Authors

Contributors names and contact info:
- TBD

## Version History

* 20240407
    * Initial Release
      * Power plant and renewable project locations for NEM included
      * Wind farm and wind turbine details and locations for all operating wind farms included
      * Not fully quality checked

## Roadmap

The following is a list of further updates planned for the database:

* Update WA and non-NEM projects
* Add solar farm details for PV modules, inverters, qtys, etc
* Add project areas from public cadastral data
* Review and update development projects
* Expand included data
* Quality check all data
* Improve symbology for online version

And for the project:
* Instructions for local setup

## How to help

Aside from much trial and error learning PostgreSQL, many hours have gone into manually consolidating, correcting and adding missing data.  
If you want to support let me know if and how you are using the data.

Also, let me know if there are any discrepancies or issues here on this GitHub project. 

You can also contribute by providing data to be included in the database. 
For now there is a basic Excel spreadsheet which can be used to provide data for projects, but please only provide back in CSV file format.

**Note: it must be open source and shareable under the license terms below**

And if you are so inclined you can 
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/richardgledhill)

## License

This project is licensed under the Creative Commons Attribution 4.0 International License - see the LICENSE.md file for details.

## Acknowledgments

In part the initial data included has been sourced from the following: 
* [AEMO Generation Information](https://aemo.com.au/en/energy-systems/electricity/national-electricity-market-nem/nem-forecasting-and-planning/forecasting-and-planning-data/generation-information)
* [Openstreetmap](https://www.openstreetmap.org/#map=4/-28.54/131.57)
* [Wikipedia](https://www.wikipedia.org/)
* Additional project specific sources are also noted in the data under project notes.

And developed using the following amazing open source software: 
* [PostgreSQL](https://www.postgresql.org/)
* [PostGIS](https://postgis.net/)
* [DBeaver Community](https://dbeaver.io/) (IMO the best database management tool) 
* [QGIS](https://www.qgis.org/en/site/)
* [QGISCloud](https://qgiscloud.com/)