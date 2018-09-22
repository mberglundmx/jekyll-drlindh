---
layout: page
title: För Medlemmar
permalink: /medlemmar
sitemap:
    priority: 0.7
    lastmod: 2018-09-22
    changefreq: weekly
---
Här finner du information för medlemmar i föreningen, klicka på länkarna nedan för mer information

{% for post in site.pages %}
<p>
<h4>
<a href="{{ post.url }}">
{{ post.title }}
</a>
</h4>

{{ post.excerpt | strip_newlines | truncate: 180 }}
</p>
<a href="{{ post.url | absolute_url }}" class="button">Läs mer</a></li>

{% endfor %}

# Medlemskap

# Trivselregler

# Aktiviteter

# Husråd

# Lokaler

# Ska du renovera?

# Telefoni, internet och TV

# Parkering och förråd

# Sophantering

# Brandskydd och säkerhet

# Att hyra ut i andra hand

# Lindhbladet
