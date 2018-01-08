---
layout: default
---

{% include figure.html file="decomposition.png" alt="intro image here" width="85%" %}

# Summer school

> organized by WestGrid and UBC

This event is brought to you by WestGrid (https://www.westgrid.ca) and the UBC ARC Department (https://arc.ubc.ca)

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | prepend: site.url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}}. (get [source code]({{ site.repo }}))
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
