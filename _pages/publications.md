---
layout: archive
title: "Author Publications"
permalink: /publications/
author_profile: true
---

See all my publications <font color=pink|>[here (ads)](https://ui.adsabs.harvard.edu/search/q=%20%20author%3A%22Mart%C3%ADnez-V%C3%A1zquez%2C%20C.%20E.%22&sort=date%20desc%2C%20bibcode%20desc&p_=0)></font>: 
[refereed](https://ui.adsabs.harvard.edu/search/filter_property_fq_property=AND&filter_property_fq_property=property%3A%22refereed%22&fq=%7B!type%3Daqp%20v%3D%24fq_property%7D&fq_property=(property%3A%22refereed%22)&q=%20%20author%3A%22Mart%C3%ADnez-V%C3%A1zquez%2C%20C.%20E.%22&sort=date%20desc%2C%20bibcode%20desc&p_=0) 
and [non-refereed](https://ui.adsabs.harvard.edu/search/filter_property_fq_property=AND&filter_property_fq_property=property%3A%22notrefereed%22&fq=%7B!type%3Daqp%20v%3D%24fq_property%7D&fq_property=(property%3A%22notrefereed%22)&q=%20%20author%3A%22Mart%C3%ADnez-V%C3%A1zquez%2C%20C.%20E.%22&sort=date%20desc%2C%20bibcode%20desc&p_=0)

**First Author Publications**

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
