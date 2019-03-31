---
permalink: /Translations/
title: "Translations"
---

{% for post in site.categories["Translations"] %}
<article class="archive-item">
    <h3><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h3>
</article>
{% endfor %}