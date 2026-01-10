---
layout: default
---

Hello! 

I’m Michael. I like [learning](https://ocw.mit.edu) and [programming](https://www.ruby-lang.org/en/). I’m on Github as [@themichaelyang](http://github.com/themichaelyang).

Professionally, I'm taking a break to figure out life with [chronic orofacial pain](https://link.springer.com/chapter/10.1007/978-981-15-1346-6_25). I recently completed a retreat at [Recurse Center](https://www.recurse.com), and hope to return soon. 

Previously, I worked at [Stripe](https://stripe.com/) for five years, building APIs for [Issuing](https://stripe.com/issuing). In school, I studied math and computer science. I was also a [hackNY Fellow](https://hackny.org/).

I believe we have a responsibility to maximize the [well-being](https://en.wikipedia.org/wiki/Well-being) of ourselves and [others](https://en.wikipedia.org/wiki/Altruism). I hope that we can design systems, structures, and society (and software) that encourage that. I think it's difficult, it's necessary, and it's possible. I hope you agree with that.

<div class="Home__Featured">
  <ul class="Home__Projects">
    <h1 class="Home__Heading">Selected projects</h1>
    {% assign projects = site.projects | reverse %}
    {% for project in projects %}
      <li>
        <a class="project-name" href="{{ project.link }}">{{ project.name }}</a>
        <p class="project-description">{{ project.description }}</p>
      </li>
      {% endfor %}
  </ul>

  <!--<ul class="Home__Posts">
    <h1 class="Home__Heading">Latest posts</h1>
    {% for post in site.posts limit:3%}
      <li>
        <a class="post-name" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        <p class="post-description">{{ post.description }}</p>
      </li>
    {% endfor %}
    <p><em>Read more at the <a href='/blog'>blog</a> </em>   ➡️</p>-->
  <!--</ul>-->
<div>
