---
layout: archive
title: BRF Doktor Lindh
permalink: /
feature: /images/uploads/img_6220 (feature).jpg

pagination: 
  enabled: true
---

Här kan du läsa mer information om vår Bostadsrättsförening, klicka på menyerna ovan, eller läs senaste notiserna nedan.

<!-- Rör inte raderna nedan! --->
<div class="tiles">
{% for post in paginator.post %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<!-- 
    Showing buttons to move to the next and to the previous list of posts (pager buttons).
  -->
  {% if paginator.total_pages > 1 %}
  <ul class="pager">
      {% if paginator.previous_page %}
      <li class="previous">
          <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&larr; Newer Posts</a>
      </li>
      {% endif %}
      {% if paginator.next_page %}
      <li class="next">
          <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Older Posts &rarr;</a>
      </li>
      {% endif %}
  </ul>
  {% endif %}

