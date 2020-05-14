_Development Tools for Humans™_

- [🧳 Suitcase](https://github.com/Impedimenta/Suitcase) — A flexible command line tool for instantly deploying user interfaces for simple commands and scripts.

- [🎥 Suitcase Videos](https://vimeo.com/showcase/7102180) — A collection of demo videos, showcasing a range of Suitcase features. 

- [🧳 Suitcase Bazaar](https://impedimenta.github.io/Suitcase-Bazaar/) — Suitcase examples and documentation.

<ul>
  {% for post in site.posts %}
    <li>
      <p><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.subtitle }} <span style="colour: #CCC; font-size: 11px">{{ post.date | date_to_string }}</span></p>
    </li>
  {% endfor %}
</ul>

<script type="text/javascript" src="//downloads.mailchimp.com/js/signup-forms/popup/unique-methods/embed.js" data-dojo-config="usePlainJson: true, isDebug: false"></script><script type="text/javascript">window.dojoRequire(["mojo/signup-forms/Loader"], function(L) { L.start({"baseUrl":"mc.us7.list-manage.com","uuid":"3ca51398cd24bb1baa2e93461","lid":"817e807549","uniqueMethods":true}) })</script>
