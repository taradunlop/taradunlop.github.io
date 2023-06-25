---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1>Portfolio Work</h1>

{% for post in site.categories.portfolio %}

<h2><a href="{{post.url}}">{{ post.title }}</a></h2>

{% endfor %}