---
layout: default
title: Community Technical Articles
hide_tagline: true
---

[← Back to Home](./)

## Community Technical Articles

Technical articles written by MMAUG community members covering Microsoft AI, Azure, DevOps, cloud infrastructure, and open-source technologies.

**Want to contribute?** Read our [contribution guidelines](./CONTRIBUTING.html) and submit a pull request.

---

{% if site.posts.size > 0 %}
{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

<small>{{ post.date | date: "%B %-d, %Y" }} · By {{ post.author }}</small>

{{ post.description }}

{% if post.tags.size > 0 %}
<small>Tags: {% for tag in post.tags %}`{{ tag }}`{% unless forloop.last %}, {% endunless %}{% endfor %}</small>
{% endif %}

---

{% endfor %}
{% else %}
*No articles published yet. Be the first to contribute!*
{% endif %}
