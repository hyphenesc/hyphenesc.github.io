## Latest Post


{% for post in site.posts limit:1 %}


<article class='post'>
  <h1 class='post-title'>
    <a href="{{ site.path }}{{ post.url }}">
      {{ post.title }}
    </a>
  </h1>
  <div class="post-date">{{ post.date | date: "%b %-d, %Y" }}</div>
  {{ post.content }}
</article>

{% endfor %}


## Previous posts


{% for post in site.posts limit:5 offset:1 %}


<article class='post'>
  <h3>
    <a href="{{ site.path }}{{ post.url }}">
      {{ post.title }}
    </a>
  </h3>
  <div class="post-date">{{ post.date | date: "%b %-d, %Y" }}</div>
  {{ post.excerpt | strip_html }}
</article>

{% endfor %}


## Older posts

Find older blog posts on the _[archive](archive.md)_, or follow me via _[RSS](feed.xml)_.

