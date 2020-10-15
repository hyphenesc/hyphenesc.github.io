---
layout: "post"
title: "Write that down"
---

Recently I started university, again. This time I am pivoting from art to psychology. The course content seems very introductory. The teacher would mention authors, theories and techniques; It seems that the gold is hidden over the rainbow. One of my academic dreams has always been to `CTRL` + `F` my notes. So with some free time and my [blog preset][1] I built just that. <!--more-->

It's still under construction, but the basic idea is that I create blog posts for my class notes and homework. Then I tag them and display them in their respective categories, meaning that buy the end of the semester I can read the whole content of a class and search for keywords.

My blog preset is pretty simple to build, especially here on github. Just fork the repo, go to the `_config.yml` file and tweak some variables like the title, site description. Then just write posts in markdown / Jekyll and make sure to tag them, done!

A cool addition was adding an edit button to each post, to do that I added the following to the `post` layout:

````

  <div class="post-date">
    <a href="{site.editurl}{page.path}">
      [edit]
    </a>
  </div>

````

> *Note: I used two curly brakets arround site.editurl and page.path, here I'm only showing one because if I were to write two of them they would render as the value for those variables.*

After some quick additions like new items on the top bar (again by modifying the `default` layout) and removing some unnecessary features like the privacy notice and the RSS feed I was done. In about 15 minutes I made a basic layout to publish my school notes and documents online. With my mayor being in psychology I can really benefit from writing down all my concepts and having them handy on my phone, plus I should get accustomed to writing more often.

For a glimpse into the ins and outs of psychology visit my [notes and documents site][2] (written in Spanish), keep looking out for more posts on here (in English), expect essays about psychology and technology, [soon][3].

[1]: https://github.com/alex-esc/post-clone
[2]: https://alex-esc.github.io/notes/
[3]: https://alex-esc.github.io/posts/subscribe.html
