---
title: Dev
servers:
  - ramoth
---

[2016]({{ site.baseurl }}/2016/)

# {{ page.title }}

{% include server-links.md %}

Dev is hard to capacity plan for, since by definition anything that uses up capacity on dev shouldn't be there!

The one area for concern is disk usage, which varied wildly through 2015. It's likely that any filling of the disks can be dealt with by cleanups or evictions. Extra disk space would only be necessary when the cleanups are happening more frequently.

![]({{ site.baseurl }}/images/2015/errol-df-year.png)
