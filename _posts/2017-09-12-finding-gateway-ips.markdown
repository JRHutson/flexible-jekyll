---
layout: post
title: Finding Gateway IP's
date: 2017-09-12 00:00:00 +0300
description: Script created as part of a software deployment project that automated manipulation of extremely large datasets # Add post description (optional)
img: CodeOnScreen.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Automation, Python, Pandas] # add tag
---
***Tools Used:***
1. Python
2. Pandas
3. ArcGIS API for Python


[View the Github Repository](https://github.com/JRHutson/PopulateGatewayIP)


This script was used to support a very large data collection effort. In order for the system being deployed to function it was necessary to know the Gateway IP address of each computer it would be installed on. Once other data was collected through ESRI's Survey 123 app, this script would run daily to pull features that had been uploaded to the server, identify the needed data by querying multiple datasets and update the feature. One of the datasets queried contains over 1 Million rows, leading to the need to use Pandas in the process. 

