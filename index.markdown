---
layout: page
title: ' '
---

# Üdvözöllek a portfólió oldalamon!

Ez a portfólió oldal a munkáimat mutatja be. Lépj velem kapcsolatba, ha új munkát keresel vagy érdekelnek a munkáim.

<div class="row">
    <div class="col box flex">
        <h2>Cikkek</h2>
        <p>Szakmai cikkek építészet és klímaváltozás témában.</p>
        <a href="{{ site.baseurl }}/posts" class="btn">Böngéssz a cikkeim között</a>
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
        <a href="{{ latest_post.url | prepend: site.baseurl }}" class="btn">Tovább olvasom</a>
    </div>
</div>
