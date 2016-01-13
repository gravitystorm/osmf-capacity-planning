{% assign increase = include.current | minus: include.previous %}
{% assign high = increase | times: 1.25 | plus: include.current %}
{% assign medium = increase | times: 1.0 | plus: include.current %}
{% assign low = increase | times: 0.75 | plus: include.current %}

**High**
: {{ high }} {{ include.units }}

**Medium**
: {{ medium }} {{ include.units }}

**Low**
: {{ low }} {{ include.units }}

**Current Capacity**
: {{ include.capacity }} {{ include.units }}

**Status**
{% if include.capacity > high %}
: Green
{% elsif include.capacity > medium %}
: Yellow
{% elsif include.capacity > low %}
: Orange
{% else %}
: Red
{% endif %}
