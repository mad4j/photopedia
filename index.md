

[![Henri Cartier-Bresson](thumbs/henri-cartier-bresson-02-thumb.jpg)]({{ site.baseurl }}{% link cartier-bresson.md %})
[![Sebastiao Salgado](thumbs/sebastiao-salgado-01-thumb.jpg)]({{ site.baseurl }}{% link salgado.md %})
[![Helmut Newton](thumbs/helmut-newton-02-thumb.jpg)]({{ site.baseurl }}{% link newton.md %})
[![Willy Ronis](thumbs/willy-ronis-01-thumb.jpg)]({{ site.baseurl }}{% link ronis.md %})
[![Garry Winogrand](thumbs/garry-winogrand-01-thumb.jpg)]({{ site.baseurl }}{% link winogrand.md %})


{% for p in site.photographers %}[![{{ p.title }}](thumbs/{{ p.thumb }})]({{ site.baseurl }}{{ p.url }})
{% endfor %}
