---
layout: default
---

{% include figure.html file="decomposition.png" alt="intro image here" width="85%" %}

# Research computing summer school

> Monday June 11th to Thursday June 14th, 2018

This event is brought to you by [WestGrid](https://www.westgrid.ca) and the
[UBC ARC Department](https://arc.ubc.ca). The main focus of this school is training researchers to use
[Compute Canada's national systems](https://docs.computecanada.ca/wiki/National_systems) efficiently for
their scientific workflows in all disciplines and introducing the modern tools and techniques.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | prepend: site.url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
