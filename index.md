---
title: A Developer Blog
---
## Feed your head, Free your mind..

Early Adopter, Technologist, CommunityGrid Creator. Read more about.me/dwightaspencer and sign my key at keybase.io/denzuko

### Articles
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
