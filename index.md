_Development Tools for Humans™_

- [🧳 Suitcase](https://github.com/Impedimenta/Suitcase) — A flexible command line tool for instantly deploying user interfaces for simple commands and scripts.

- [🎥 Suitcase Videos](https://vimeo.com/showcase/7102180) — A collection of demo videos, showcasing a range of Suitcase features. 

- [🧳 Suitcase Bazaar](https://impedimenta.github.io/Suitcase-Bazaar/) — Suitcase examples and documentation.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.subtitle }}
    </li>
  {% endfor %}
</ul>
