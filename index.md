---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: main
---
# My Blogs



 {% for post in site.posts %}
 <a href="/LSCSWebsiteSample{{post.url}}">
  {{ post.title }}
 </a>
 {% endfor %}