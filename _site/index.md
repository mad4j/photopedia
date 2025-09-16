
{% for p in site.photographers %}[![{{ p.title }}](thumbs/{{ p.thumb }})]({{ site.baseurl }}{{ p.url }})
{% endfor %}
