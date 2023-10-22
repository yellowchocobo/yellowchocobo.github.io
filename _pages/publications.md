---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

1. 🆕 Malvi, S., Shah, H., Chandarana, N., Purohit, M., Adler, J., **Kerner, H.** (2023). Automated Multi-class Crater Segmentation in Mars Orbital Images. To appear in *Proceedings of the 31st ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems (ACM SIGSPATIAL 2023), GeoAI Workshop*.

1. 🆕 **Kerner, H.**, Nakalembe, C., Yang, A., Zvonkov, I., McWeeny, R., Tseng, G., and Becker-Reshef, I. (2023). How accurate are existing land cover maps for agriculture in Sub-Saharan Africa? arXiv preprint, [link](https://arxiv.org/abs/2307.02575).
