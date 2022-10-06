---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: index-style
---

{% for post in site.posts %}
    {% if post.category == "project" %}
        <h1>{{post.title}}</h1>
    {% endif %}
{% endfor %}

<h1>Hej</h1>