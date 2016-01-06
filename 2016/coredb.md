---
title: Core databases
---

# {{ page.title }}

# Disk space

## Katla /store/arrays/fast

[![]({{ site.baseurl }}/images/2015/katla-df-year.png)](http://munin.openstreetmap.org/openstreetmap/katla.openstreetmap/df.html)

Increase is roughly linear. H/M/L set to 125%/100%/75% of last year's increase.

* Jan 2015: 4.66 TB
* Jan 2016: 5.53 TB (0.87 TB increase)
* Jan 2017:
  * High: 6.62 TB
  * Medium: 6.40 TB
  * Low: 6.18TB

7TB Capacity = Green

## Katla /store/arrays/slow

No trend, plenty of space

## Katla /store/arrays/ssd

Increase is roughly linear. H/M/L 125/100/75 of last year's increase.

* Jan 2015: 183 GB
* Jan 2016: 245 GB (62 GB increase)
* Jan 2017:
  * High: 323 GB
  * Medium: 307 GB
  * Low: 291 GB

Capacity: 367 GB = Green

## Ramoth /store/postgresql/openstreetmap

[![]({{ site.baseurl }}/images/2015/ramoth-df-year.png)](http://munin.openstreetmap.org/openstreetmap/ramoth.openstreetmap/df.html)

Increase is roughly linear. H/M/L 125/100/75 of last year's increase.

* Jan 2015: 4.64 TB
* Jan 2016: 5.67 TB (1.03 TB increase)
* Jan 2017:
  * High: 6.96 TB
  * Medium: 6.70 TB
  * Low: 6.44 TB

Capacity: 8 TB = Green

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
