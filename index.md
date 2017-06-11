

[![Franco Fontana](thumbs/franco-fontana-thumb.jpg)]({{ site.baseurl }}{% link fontana.md %})
[![Nobuyoshi Araki](thumbs/nobuyoshi-araki-01-thumb.jpg)]({{ site.baseurl }}{% link araki.md %})
[![Oliviero Toscani](thumbs/oliviero-toscani-02-thumb.jpg)]({{ site.baseurl }}{% link toscani.md %})
[![Henri Cartier-Bresson](thumbs/henri-cartier-bresson-02-thumb.jpg)]({{ site.baseurl }}{% link cartier-bresson.md %})
[![Sebastiao Salgado](thumbs/sebastiao-salgado-01-thumb.jpg)]({{ site.baseurl }}{% link salgado.md %})
[![Helmut Newton](thumbs/helmut-newton-02-thumb.jpg)]({{ site.baseurl }}{% link newton.md %})
[![Willy Ronis](thumbs/willy-ronis-01-thumb.jpg)]({{ site.baseurl }}{% link ronis.md %})
[![Peter Lindbergh](thumbs/peter-lindbergh-01-thumb.jpg)]({{ site.baseurl }}{% link lindbergh.md %})
[![Garry Winogrand](thumbs/garry-winogrand-01-thumb.jpg)]({{ site.baseurl }}{% link winogrand.md %})


{% for p in site.photographers %}[![{{ p.title }}](thumbs/{{ p.thumb }})]({{ site.baseurl }}{{ p.url }})
{% endfor %}
