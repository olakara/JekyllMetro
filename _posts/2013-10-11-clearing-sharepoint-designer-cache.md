---
layout: post
title:  Clearing SharePoint Designer Cache
date:   2013-10-11 15:30:00
categories: SharePoint
tags: SharePoint Designer
---

Sometimes, SharePoint Designer just goes haywire! You try to edit or publish a workflow and it says the item cannot be displayed. At times, it even says that the site is disabled to be edited from SharePoint Designer. But, you know what you are doing and are sure that these are just "crazy" errors!

All you need to to fix these kind of issues are to clear the cache and make SharePoint Designer feel that you are starting from scratch. SharePoint Designer's cache is spread around three different folders. Close any running instance of designer and delete all folders and files in the following directories:


1. C:\Users\\AppData\Local\Microsoft\WebsiteCache
2. C:\Users\\AppData\Roaming\Microsoft\SharePoint Designer\ProxyAssemblyCache
3. C:\Users\\AppData\Roaming\Microsoft\Web Server Extensions\Cache

Fire up your SharePoint Designer and you should get a clean start. 