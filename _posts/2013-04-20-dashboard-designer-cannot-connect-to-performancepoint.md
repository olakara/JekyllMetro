---
layout: post
title:  Cannot Connect to PerformancePoint Service
date:   2013-04-20 15:30:00
tags:
- SharePoint
- PerformancePoint Service
---

After configuring my PerformancePoint Service on SharePoint 2013. This error hit me when trying to create a new data source from Dashboard Designer.



Here are the steps to make sure you have your PerformancePoint service configured properly.

**1. Make sure you have the PerformancePoint Service and Secure Store Service started.**


You can check this by going to Central Administration | Application Management | Service Applications |Manage services on server

**2. Make sure you have a Secure Store service application running.**


 You can check this by going to Central Administration | Application Management | Service Applications | Manage service applications.

Ensure that you have configured the service application properly.

**3. Make sure you have a PerformancePoint Service application running.**


You can check this by going to Central Administration | Application Management | Service Applications | Manage service application.

Ensure that you have configured the service application properly. Click on your performance point service application to take you to the management screen as shown below:


Verify you application setting by selecting PerformancePoint Service Application Settings.


Make sure you have your secure store displayed and you are using your appropriate unattended service account (If you are using the service account, click Change User and reenter the username and password).

**4. And finally check service application associations.**

Go to Central Administration | Application Management | Service Applications | Configure service application associations


Click on default and ensure that your performance point service is selected.

These steps should ensure that you get your PerformancePoint service up and running.
