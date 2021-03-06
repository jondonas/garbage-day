
<a rel="Exploration" href="https://github.com/BCDevExchange/docs/blob/master/discussion/projectstates.md"><img alt="Being designed and built, but in the lab. May change, disappear, or be buggy." style="border-width:0" src="http://bcdevexchange.org/badge/2.svg" title="Being designed and built, but in the lab. May change, disappear, or be buggy." /></a>  

[![Stories in Ready](https://badge.waffle.io/BCDevExchange/garbage-day.png?label=ready&title=Ready)](https://waffle.io/BCDevExchange/garbage-day)

[![Join the chat at https://gitter.im/BCDevExchange/garbage-day](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/BCDevExchange/garbage-day?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge "The BCDevExchange will not collect, use, or disclose personal information using Gitter. Please be aware however that IP addresses and other information may be collected by Gitter itself, and these IP addresses and other information collected may be stored on Gitter servers located outside of Canada.  Please do not provide any personal information, or third party information (ie. talk about others) in your use of the Gitter application.")

<a href="https://waffle.io/BCDevExchange/garbage-day/join">Join the Waffle.io board</a>

# Waste Pickup Reminder



The purpose of this repo is to collaborate on ways to notify municipal residents when their garbage pickup day is.

## Features
Geographic data on municipal waste removal zones.

## Data
Two sets of data are required to determine garbage pickup days for a given address (GIST_Garbage_Schedule, GIST_Garbage_Zone). The first is a list of addresses and the pickup zone with which they are associated (there are 5 zones in Kamloops, 1 for each week day, numbered 1-5). The second is a list of each day of the year and the pickup zone associated with each pickup day (w=weekend, s=statuatory holiday). The data represents 2015 pickup dates only however this will be extended to include 2016 closer to the end of the year.

The two tables of data can be accessed here: http://maps.kamloops.ca/arcgis3/rest/services/BCDevExchange/GarbagePickup/MapServer

Also included (in case the spatial location of addresses and zones is of use) are two spatial datasets of AddressPoint (their address attribute is the data source in GIST_Garbage_Schedule) and GarbageZone (select the ArcGIS JavaScript link to see the map and zoom in to see the AddressPoints in their Zone). I don't think this is required for this development though.

## Requirements

## Installation
None yet.

## Project Status
Under active development.

## Goals/Roadmap
Collaborate with the local tech community to develop project goals and/or a product roadmap.

## Getting Help or Reporting an Issue
To report bugs/issues/feature requests, please file an [issue](https://github.com/BCDevExchange/garbage-day/issues).

## How to Contribute
Pull requests are welcome. If you would like to contribute a package, please see our [CONTRIBUTING guidelines](https://github.com/BCDevExchange/garbage-day/blob/lm0625/CONTRIBUTING.md).

## License
Code, data and content in this repository are licensed under different licenses.

- All code in the /code directory is licensed under the Apache License 2.0. See [LICENSE.Apache-2.0](https://github.com/BCDevExchange/garbage-day/blob/lm0625/code/LICENSE.Apache.2.0) in the appropriate directories.
- Source data in /data directory is licensed under the Open Government License - British Columbia. See [LICENCE OGL-Kamloops-1.0](data/LICENCE OGL-Kamloops-1.0) in the appropriate directories.
