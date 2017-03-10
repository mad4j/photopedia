
[![Vivian Maier](thumbs/vivian-maier-01-thumb.jpg)]({% link maier.md | predend:site..baseurl %})
[![Franco Fontana](thumbs/franco-fontana-01-thumb.jpg)](fontana.html)
[![Nobuyoshi Araki](thumbs/nobuyoshi-araki-01-thumb.jpg)](araki.html)
[![Oliviero Toscani](thumbs/oliviero-toscani-02-thumb.jpg)](toscani.html)
[![Henri Cartier-Bresson](thumbs/henri-cartier-bresson-02-thumb.jpg)](cartier-bresson.html)
[![Sebastiao Salgado](thumbs/sebastiao-salgado-01-thumb.jpg)](salgado.html)

{% for p in site.photographers %}
<p>{{ p.name }}</p>
{% endfor %}
