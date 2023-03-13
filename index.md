---
title: {{ site.title }}
layout: default
---
<div class="container">
  <div class="row">
    <div class="bas">
      <img src="{{ site.profile-png }}" class="rounded-circle m-2 d-inline" alt="{{ site.title }}"><br>
      <h1 class="m-2">{{ site.title }}</h1>
      <p class="job">{{ site.job }}</p>
{% include social.html %}
     </div>
  </div>
</div>
<br>
{% include navigation.html %}
