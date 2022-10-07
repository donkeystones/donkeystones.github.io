---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: index-style
---
<div class="projects">
{% for post in site.posts %}
    {% if post.category == "project" %}
        <div class="project-container">
            <div id="picture" style="background: url({{post.proj_img}}) no-repeat;">
                <div class="pic_transform">
                    <div class="text_display">
                        <h>{{post.desc}}</h>
                    </div>
                </div>
            </div>
            <div class="project-name">{{post.title}}</div>
        </div>
    {% endif %}
{% endfor %}
</div>
<h1>Hej</h1>