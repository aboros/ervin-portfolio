---
layout: page
title: 'Címlap'
order: 1
---

# Üdvözlöm, és köszönöm, hogy ellátogatott az oldalamra!

Mekota Ervin építész és pszichológus vagyok.  

Számomra az ember és a környezet kapcsolata - kezdetektől fogva - kiemelten fontos terület. Szakmai utamon, elsősorban az építészet és a pszichológia összefonódását kutatom, különösen a fenntarthatóság és az emberi jóllét szempontjából. Jelenleg **környezetvédelmi szakpszichológus** képzésre járok azért, hogy még mélyebb ismereteket szerezzek az ember és a természet összhangjának megteremtéséhez.

<div class="row">
    <div class="col box flex">
        <h2>Cikkek</h2>
        <p>Szakmai cikkek építészet és klímaváltozás témában.</p>
        <a href="{{ site.baseurl }}/posts" class="btn">Böngéssz az általam javasolt cikkek között</a>
    </div>
    <div class="col box flex">
        <h2>Magamról</h2>
        <p>Röviden bemutatkozom, hogy ki vagyok és mit csinálok.</p>
        <a href="{{ site.baseurl }}/about" class="btn">További részletek</a>
    </div>
</div>
<div class="row">
    <div class="col box">
        <h2>Legfrissebb bejegyzés</h2>
        {% assign latest_post = site.posts.first %}
        <h3>{{ latest_post.title }}</h3>
        <p>{{ latest_post.excerpt | strip_html | truncatewords: 50 }}</p>
        <a href="{{ latest_post.url | prepend: site.baseurl }}" class="btn">Tovább</a>
    </div>
</div>
