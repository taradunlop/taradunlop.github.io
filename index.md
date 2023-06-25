---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# layout: home

layout: page
order: 1
---

<h2>Portfolio Work</h2>

{% for post in site.categories.portfolio %}

<h3><a href="{{post.url}}">{{ post.title }}</a></h3>

{% endfor %}