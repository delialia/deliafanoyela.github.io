---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on <a href="https://scholar.google.co.uk/citations?user=fUp2rucAAAAJ">my Google Scholar profile</a>.

You can download **my thesis** *Signal Processing and Graph Theory techniques for Sound Source Separation* {% include test-thesis.html %}.


{% include base_path %}

2023
------
<ul>
{% for post in site.publications reversed %}
  {% if post.year == 2023 and post.type == "published" %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
</ul>



2020
------
<ul>
{% for post in site.publications reversed %}
  {% if post.year == 2020 and post.type == "published" %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
</ul>

2019
------
<ul>
{% for post in site.publications reversed %}
  {% if post.year == 2019 and post.type == "published" %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
</ul>


2018
------
<ul>
{% for post in site.publications reversed %}
  {% if post.year == 2018 and post.type == "published" %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
</ul>

2017
------
<ul>
{% for post in site.publications reversed %}
  {% if post.year == 2017 and post.type == "published" %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
</ul>
