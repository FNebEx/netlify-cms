---
layout: default
---

# Hello. This is the Netlify CMS.

{% for post in collections.post %}
  [{{ post.data.title }}]({{ post.url }})
{% endfor %}