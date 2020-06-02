---
title: Home
---

<p align="center"> # Edward Southerington </p>

## Analysis Portfolio

MSc in Economics Graduate from Nova School of Business and Economics

Bacehlor of Laws / Bachelor of Business Under-graguate from La Trobe University

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>
