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


Select Publications
===
<a href="https://www.sciencedirect.com/science/article/abs/pii/S1532046420302495">An Empirical Characterization of Fair Machine Learning For Clinical Risk Prediction</a>
<br>
<b>Stephen R. Pfohl</b>, Agata Foryciarz, Nigam H. Shah.
<br>
<i>Journal of Biomedical Informatics, 113:103621, 2021</i>
<br>
\[<a href="https://www.sciencedirect.com/science/article/abs/pii/S1532046420302495">paper</a>\] \[<a href="https://arxiv.org/abs/2007.10306">pre-print</a>\] \[<a href="https://github.com/som-shahlab/fairness_benchmark">code</a>\]

<a href="http://proceedings.mlr.press/v106/pfohl19a.html">Counterfactual Reasoning for Fair Clinical Risk Prediction</a>
<br>
<b>Stephen R. Pfohl</b>, Tony Duan, Daisy Yi Ding, Nigam H. Shah.
<br>
<i>Proceedings of the 4th Machine Learning for Healthcare Conference, PMLR 106:325-358, 2019</i>
<br>
\[<a href="http://proceedings.mlr.press/v106/pfohl19a.html">abstract</a>\] \[<a href="http://proceedings.mlr.press/v106/pfohl19a/pfohl19a.pdf">pdf</a>\]

<a href="https://dl.acm.org/doi/abs/10.1145/3306618.3314278">Creating fair models of atherosclerotic cardiovascular disease risk</a>
<br>
<b>Stephen Pfohl</b>, Ben Marafino, Adrien Coulet, Fatima Rodriguez, Latha Palaniappan, Nigam H Shah.
<br>
<i>Proceedings of the 2019 AAAI/ACM Conference on AI, Ethics, and Society, 2019</i>
<br>
\[<a href="https://arxiv.org/abs/1809.04663">arxiv post-print with erratum</a>\] \[<a href="https://arxiv.org/pdf/1809.04663.pdf">pdf</a>\] \[<a href="https://dl.acm.org/doi/abs/10.1145/3306618.3314278">paper</a>\]