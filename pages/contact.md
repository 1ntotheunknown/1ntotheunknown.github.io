---
layout: page
title: Contact
---
{% for post in site.categories.contact %}
  <a href="{{ site.github.url }}{{ post.url }}">
    <div class="featured-posts" {% if post.image %}style="background-image:url({{ site.github.url }}/assets/img/{{ post.image }})"{% endif %}>
      <h2><span>{{ post.title }}</span></h2>
    </div>
  </a>
{% endfor %}

This theme is completely free and open source software. You may use it however you want, as it is distributed under the [MIT License](http://choosealicense.com/licenses/mit/). If you are having any problems, any questions or suggestions, feel free to [tweet at me](https://twitter.com/intent/tweet?text=My%question%about%Millennial%is:%&amp;via=paululele), or [file a GitHub issue](https://github.com/lenpaul/Millennial/issues/new).