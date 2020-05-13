---
layout: page
title: Garsūs žmonės
permalink: /garsūs-žmonės/
---

* [Pranas Puskunigis]({{ "/pranas-puskunigis" | prepend: site.baseurl }})

{% for page in site.people %}
* [page.title]({{ page.url | prepend: site.baseurl }})
{% endfor %}
    
    
  