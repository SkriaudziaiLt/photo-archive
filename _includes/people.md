{% for page in site.people %}* [{{page.title}}]({{ page.url | prepend: site.baseurl }})
{% endfor %}