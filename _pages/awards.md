---
layout: archive
title: "Awards"
permalink: /awards/
author_profile: true
---
<!-- 获奖主页 -->

{% include base_path %}

{% for post in site.awards reversed %}
  {% include archive-single.html %}
{% endfor %}