---
layout: single
title: "Soccer Album"
permalink: /life/soccer/
author_profile: true
---

{% assign gallery_files = site.static_files
  | where_exp: "f", "f.path contains '/assets/images/life/soccer/'"
  | where_exp: "f", "f.extname == '.jpg' or f.extname == '.jpeg' or f.extname == '.png' or f.extname == '.gif' or f.extname == '.webp'"
  | sort: "name"
  | reverse
%}

{% if gallery_files and gallery_files.size > 0 %}
  {% include gallery id="soccer-gallery" caption="Soccer Moments" %}
  <div id="soccer-gallery">
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
  <p>还没有上传 Soccer 照片。</p>
{% endif %}
