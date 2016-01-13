{% for server in page.servers %}
{{ server }}
: [hardware](https://hardware.openstreetmap.org/servers/{{ server }}.openstreetmap.org/) [munin](http://munin.openstreetmap.org/openstreetmap/{{ server }}.openstreetmap/index.html)
{% endfor %}
