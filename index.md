---
title: Home
---
<html>
  <head>
  </head>
  <body>
    <h1 align="center">Edward Southerington</h1>
    <p style="color: blue" align="center">MSc in Economics Graduate, Nova School of Business and Economics</p>
    <p style="color: blue" align="center">Bacehlor of Laws / Bachelor of Business Under-graguate, La Trobe University</p>
  </body>
</html>

## Analysis Portfolio

MSc in Economics Graduate, Nova School of Business and Economics

Bacehlor of Laws / Bachelor of Business, La Trobe University

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>
