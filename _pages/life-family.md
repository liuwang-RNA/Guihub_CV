---
layout: single
title: "Family Album"
permalink: /life/family/
author_profile: true
---

{% assign gallery_files = site.static_files
  | where_exp: "f", "f.path contains '/assets/images/life/family/'"
  | where_exp: "f", "f.extname matches '\\.(jpg|jpeg|png|gif|webp)$'"
  | sort: "name"
  | reverse
%}

{% if gallery_files and gallery_files.size > 0 %}
  {% include gallery id="family-gallery" caption="Family Moments" %}
  <div id="family-gallery">
    {% for f in gallery_files %}
      <figure>
        <a href="{{ f.path | relative_url }}">
          <img src="{{ f.path | relative_url }}" alt="{{ f.name }}">
        </a>
        <figcaption>{{ f.name }}</figcaption>
      </figure>
    {% endfor %}
  </div>
{% else %}
  <p>还没有上传 Family 照片。</p>
{% endif %}
