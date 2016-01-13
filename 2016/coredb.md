---
title: Core databases
servers:
  - katla
  - ramoth
---

[2016]({{ site.baseurl }}/2016/)

# {{ page.title }}

{% include server-links.md %}

# Disk space

## Katla /store/arrays/fast

[![]({{ site.baseurl }}/images/2015/katla-df-year.png)](http://munin.openstreetmap.org/openstreetmap/katla.openstreetmap/df.html)

Increase is roughly linear.

* Jan 2015: 4.66 TB
* Jan 2016: 5.53 TB (0.87 TB increase)
* Jan 2017 Estimates:

{% include linear.md units='TB' previous=4.66 current=5.53 capacity=7 %}

## Katla /store/arrays/slow

No trend, plenty of space

## Katla /store/arrays/ssd

Increase is roughly linear.

* Jan 2015: 183 GB
* Jan 2016: 245 GB (62 GB increase)
* Jan 2017 Estimates:

{% include linear.md units='GB' previous=183 current=245 capacity=367 %}


## Ramoth /store/postgresql/openstreetmap

[![]({{ site.baseurl }}/images/2015/ramoth-df-year.png)](http://munin.openstreetmap.org/openstreetmap/ramoth.openstreetmap/df.html)

Increase is roughly linear.

* Jan 2015: 4.64 TB
* Jan 2016: 5.67 TB (1.03 TB increase)
* Jan 2017 Estimates:

{% include linear.md units='TB' previous=4.64 current=5.67 capacity=8 %}

# Disk utilisation

## Katla

[![]({{ site.baseurl }}/images/2015/katla-utilization-sda-year.png)](http://munin.openstreetmap.org/openstreetmap/katla.openstreetmap/diskstats_utilization/index.html)

Full utilisation. Discussion required as to whether this is a problem!

## Ramoth

[![]({{ site.baseurl }}/images/2015/ramoth-sdb-year.png)](http://munin.openstreetmap.org/openstreetmap/ramoth.openstreetmap/diskstats_utilization/sdb.html)

Constant utilisation.

# Network

* Katla: N/A
* Ramoth: N/A

# CPU

* Katla: N/A
* Ramoth: N/A

# Memory

* Katla: Constant usage.
* Ramoth: Constant usage.
