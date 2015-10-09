---
layout: page
title: Posts
permalink: /posts/
---

{:.post-list }
{% for post in site.posts %}

{:.post-meta }
* {{ post.date | date: "%b %-d, %Y" }}

{: .post-link }
[{{ post.title }}]({{ post.url | prepend: site.baseurl }})

{% endfor %}
