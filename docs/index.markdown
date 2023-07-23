---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

{% assign sorted_posts = site.posts | sort:"order" %}
{% for post in sorted_posts %}
  <h2><a >{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
