---
layout: page
title: About
permalink: /about/
---

This is the working documents for the OSMF annual capacity planning exercises.

The Operations Working Group (OWG) is tasked with planning sufficient server
capacity for the OSMF-owned and operated hardware, which is used for both OSMF
matters and also, of course, for the OpenStreetMap project.

We divide the services into a number of "tiers", based on how critical they are
to the OpenStreetMap project. This helps us define priorities. For example, the
editing API and planet file services are critical, without them the project
cannot operate in any form. The wiki and tileservers are important but the
project could function without them for a few days, if necessary. Other services
such as the CGI web interface, form the third category.

The capacity planning exercises involve a lot of predicting the future,
otherwise knowns as guesswork. For each service we identify resources that are
the most likely to require intervention. These are usually:

* Disk capacity
* Disk performance
* Network traffic
* CPU utilisation
* Memory utilisation

For each of these we only worry about significant use. If a service is using 5%
CPU on a server, then we can ignore it, even if it doubles every year.

For the resources examined, we attempt to provide realistic High, Medium and Low
estimates for the year ahead. After the estimates are made they are then
compared with what is available and colour-coded appropriately:

* Green - current capacity is greater than the High estimate.
* Yellow - current capacity is between the Medium and High estimates.
* Orange - current capacity is between the Low and Medium estimates.
* Red - current capacity is below the Low estimate.

This information can then be used for planning for the year ahead - either in
changing configurations, software, or budgeting for more capacity.
