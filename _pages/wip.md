---
layout: archive
title: "Working Papers"
permalink: /wip/
author_profile: true
---

{% include base_path %}

<ol class="pub-list">
{% for post in site.working_papers reversed %}
  <li>
    <a href="{{ base_path }}{{ post.url }}" class="pub-title">{{ post.title }}</a><br>
    <span class="pub-authors">{{ post.authors | replace: 'H Ouyang', '<u><i>H Ouyang</i></u>' | replace: 'Huiyin Ouyang', '<u><i>Huiyin Ouyang</i></u>' }}</span><br>
    <span class="pub-venue">{{ post.venue }}</span>
  </li>
{% endfor %}
</ol>

<style>
.pub-list {
  list-style-type: decimal;
  padding-left: 1.5rem;
  margin-top: 1.5rem;
}
.pub-list li {
  margin-bottom: 1.25rem;
  font-size: 1rem;
  line-height: 1.5;
}
.pub-title {
  color: inherit;
  font-weight: normal;
  text-decoration: none;
  font-size: 1rem;
}
.pub-title:hover {
  text-decoration: underline;
}
.pub-authors, .pub-venue {
  color: inherit;
  font-size: 1rem;
}
</style>
