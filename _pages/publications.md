---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
* [2021](#2021)
* [2020](#2020)
* [2019](#2019)
* [2001](#2001)


<div id="2021"></div>
2021
--
* Paper 1
* Paper 2
* Paper 3

<div id="2020"></div>
2020
--
* Paper 1
* Paper 2

<div id="2019"></div>
2019
--
* Paper 1

2001
--
1. Venkatasubramanian, K., Bastin Tony Roy, S. and Dasari, M.V., 2001. [Teaching and using PSP in a software engineering course: an experience report](/publications/2001/2001_1.pdf). In Software Engineering Education and Training Annual Conference.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
