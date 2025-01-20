---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Full list at [ads](https://ui.adsabs.harvard.edu/search/p_=0&q=author%3A%22%C5%A0oltinsk%C3%BD%2C%20Tom%C3%A1%C5%A1%22&sort=date%20desc%2C%20bibcode%20desc){:target="_blank" rel="noopener"}.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
