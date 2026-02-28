---
layout: archive
title: "Journal Publications"
permalink: /publications/
author_profile: false
sidebar: false
classes: wide
---
{% for post in site.publications reversed %}
  <div class="list__item">
    <article class="archive__item" itemscope itemtype="https://schema.org/CreativeWork">
      <h2 class="archive__item-title" itemprop="headline">
        {% if post.link %}
          <a href="{{ post.link }}" rel="permalink noopener noreferrer" target="_blank">{{ post.title }}</a>
        {% else %}
          {{ post.title }}
        {% endif %}
      </h2>
      <p class="archive__item-excerpt" itemprop="description">
        {% if post.authors %}{{ post.authors }}<br>{% endif %}
        {% if post.venue %}{{ post.venue }} ({{ post.year }}){% endif %}
      </p>
    </article>
  </div>
{% endfor %}


# Conference Publications

{% for post in site.talks reversed %}
  <div class="list__item">
    <article class="archive__item" itemscope itemtype="https://schema.org/CreativeWork">
      <h2 class="archive__item-title" itemprop="headline">
        {% if post.link %}
          <a href="{{ post.link }}" rel="permalink noopener noreferrer" target="_blank">{{ post.title }}</a>
        {% else %}
          {{ post.title }}
        {% endif %}
      </h2>
      <p class="archive__item-excerpt" itemprop="description">
        {% if post.authors %}{{ post.authors }}<br>{% endif %}
        {% if post.venue %}{{ post.venue }} ({{ post.year }}){% endif %}
      </p>
    </article>
  </div>
{% endfor %}
