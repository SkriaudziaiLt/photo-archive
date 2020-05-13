---
layout: page
title: Garsūs žmonės
permalink: /garsūs-žmonės/
---

* [Pranas Puskunigis]({{ "/pranas-puskunigis" | prepend: site.baseurl }})



<ul class="post-list">
    {% for page in site.pages.garsus-zmones %}
    <li>
        <h2>
            <a class="post-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a>
        </h2>
    </li>
    {% endfor %}
</ul>
    
    
    
  