---
title: Index 
layout: template
filename: index
--- 

## RFID-Enabled Fish Tagging

In order to assist marine biologists in tracking highly migratory species of fish such as Tuna and Billfish, Olin Intelligent Vehicles Lab, in partnership with the Large Pelagics Lab, has been developing an alternative tagging platform denoted “HI-Tags,” which encompass modern technology such as RFID, bluetooth, and mobile application to integrate a seamless tagging procedure within the fishing experience.

### Submission on IEEE OCEANS '16 Conference

<a href="report.pdf">report.pdf</a>

### Sub-projects

#### Android

Android Mobile Application for use on-board.

We tested the application in July 2016 off the coast of Kona, Hawaii.

The test version is currently downloadable [Here](https://play.google.com/apps/testing/bft.fishtagsapp).

#### Server (MongoDB)

Initial Implementation of Web Database Interface.

##### Database : MongoDB(MLab)

##### FileSystem : GridFS

##### Host : Heroku

Current version is alive [Here](https://hitag-database.herokuapp.com/).

#### Server (MySQL)

Second Implementation of Web Database Interface.

We learned that our data structure was not relational;

i.e. we didn't need the overhead accrued over a relational database.

Therefore, we re-implemented the database with MySQL.

##### Database : MySQL(AWS-RDS)

##### FileSystem : AWS-S3

##### Host : Heroku
