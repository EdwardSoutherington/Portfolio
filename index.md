---
title: Home
---
<html>
  <head>
  </head>
  <body>

    <h1 >Edward Southerington</h1>
    <h2>Edward Southerington</h2>
    <p style="color: blue">MSc in Economics Graduate from Nova School of Business and Economics

    Bacehlor of Laws / Bachelor of Business Under-graguate from La Trobe University</p>
     <div>This is a div.</div>

  </body>
</html>

## Analysis Portfolio

MSc in Economics Graduate from Nova School of Business and Economics

Bacehlor of Laws / Bachelor of Business Under-graguate from La Trobe University

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>
