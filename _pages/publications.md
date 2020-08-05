---
layout: archive
title: "First Author Publications"
permalink: /publications/
author_profile: true
---

See all my publications [here (ads)](https://ui.adsabs.harvard.edu/search/q=%20%20author%3A%22Mart%C3%ADnez-V%C3%A1zquez%2C%20C.%20E.%22&sort=date%20desc%2C%20bibcode%20desc&p_=0)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
