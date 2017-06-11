[![Willy Ronis](thumbs/willy-ronis-01-thumb.jpg)]({{ site.baseurl }}{% link ronis.md %})
[![Garry Winogrand](thumbs/garry-winogrand-01-thumb.jpg)]({{ site.baseurl }}{% link winogrand.md %})


{% for p in site.photographers %}[![{{ p.title }}](thumbs/{{ p.thumb }})]({{ site.baseurl }}{{ p.url }})
{% endfor %}
