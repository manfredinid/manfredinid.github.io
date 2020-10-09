---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Seabra, F., Beck, A.L., Manfredini, D. and Muller, M., 2020. Do tourist attractions of an itinerary pull cruise ship lines? A logit model estimation for Southern Hemisphere destinations. Tourism Planning & Development, 17(1), pp.37-45.
