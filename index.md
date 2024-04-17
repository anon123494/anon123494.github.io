---
layout: default
---

# __{{site.title}}__

# Hi, I'm {{site.author}}!

This is my repository of unwanted words
some translation some math and other random stuff!

{% capture contact %}{% include contact.md %}{% endcapture %}
{{ contact | markdownify }}


_Blog posts_
{% if site.posts %}
<table>{% for post in site.posts %}<tr><td class="d">{{ post.date | date: "%B %e, %Y" }} >></td><td><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></td></tr>{% endfor %}</table>
{% endif %}