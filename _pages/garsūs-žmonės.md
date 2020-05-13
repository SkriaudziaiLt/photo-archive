---
layout: page
title: Garsūs žmonės
permalink: /garsūs-žmonės/
---

{% for page in site.people %}
* [{{page.title}}]({{ page.url | prepend: site.baseurl }})
{% endfor %}
    
    
  