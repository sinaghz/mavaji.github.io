---
permalink: /Papers/
title: "Papers"
---

{% for post in site.categories["Papers"] %}
<article class="archive-item">
    <h3><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h3>
</article>
{% endfor %}

