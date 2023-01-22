---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

*    ["Severe Weather and the Macroeconomy"](https://hskim27.github.io/files/weather_2022.pdf) with Christian Matthes and Toan Phan (Submitted)

*    ["On the Macro Impact of Extreme Climate Events in Central America: A Higher Frequency Investigation"](https://www.imf.org/en/Publications/WP/Issues/2022/12/02/On-the-Macro-Impact-of-Extreme-Climate-Events-in-Central-America-A-Higher-Frequency-526284) with Carlos Chaverri, Emilio William Fernandez Corugedo, and Pedro Juarros, IMF Working Paper 

*    ["Are the Effects of a US Financial Shock on non-US Countries Asymmetric"](https://hskim27.github.io/files/us_financial_shock_asymmetric.pdf) Working Paper



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
