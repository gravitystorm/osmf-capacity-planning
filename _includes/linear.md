{% assign increase = include.current | minus: include.previous %}
{% assign high = increase | times: 1.5 | plus: include.current %}
{% assign medium = increase | times: 1.0 | plus: include.current %}
{% assign low = increase | times: 0.75 | plus: include.current %}
{% assign full = 0.92 %}
{% assign capacity = include.capacity | times: full %}

**High**
: {{ high }} {{ include.units }}

**Medium**
: {{ medium }} {{ include.units }}

**Low**
: {{ low }} {{ include.units }}

**Capacity** (at {{ full| times: 100 }}%)
: {{ capacity }} {{ include.units }}

**Status**
{% if capacity > high %}
: Green
{% elsif capacity > medium %}
: Yellow
{% elsif capacity > low %}
: Orange
{% else %}
: Red
{% endif %}
