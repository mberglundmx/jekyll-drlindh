---
layout: page
title: För Medlemmar
permalink: /medlemmar
---
Här finner du information för medlemmar i föreningen, klicka på länkarna nedan för mer information

{% for post in site.pages %}
{% assign author = site.data.authors[post.author] %}
    <li>
    <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
    <time datetime="{{ post.date }}">
        <small>
        <strong>{{ post.date | date_to_string }}</strong>
        {% if author %}
            by {{ author.name }}
        {% endif %}
        </small>
    </time>
    {{ post.excerpt | strip_newlines | truncate: 180 }}
    </li>
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
