---
layout: index
title: Barathi Ganesh Hullathy Balakrishnan
---

---

{% include cv.md %}

## <i class="fa fa-chevron-right"></i> Recent Blog Posts

<table class="table table-hover">
  {% for post in site.posts limit: 5 %}
    {% unless post.draft %}
    <tr>
      <td><a href="{{ post.url }}">{{ post.title }}</a></td>
      <td class="col-md-3" style="text-align: right;">{{ post.date | date: "%B %e, %Y" }}</td>
    </tr>
    {% endunless %}
  {% endfor %}
</table>
<h4><a href="/blog">View all</a></h4>

## <i class="fa fa-chevron-right"></i> Fun Side Projects
+ [Workshops conducted by CEN](https://barathiganesh-hb.github.io/cen-workshops/).
+ [Recent talks given by CEN faculties](https://barathiganesh-hb.github.io/cen-talks/)
+ [CEN NLP Group](https://barathiganesh-hb.github.io/cen-nlp-group/)

---

Last updated on {% include last-updated.txt %}
