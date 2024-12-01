---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

 
## Preprints
 
 - <span>Maximum Likelihood Estimation of Short Panel Autoregressive Models with Flexible Form of Fixed Effects</span>, <span>Kazuhiko Hayakawa and **Boyan Yin**\*,</span> <span>2024</span>, <span>_Journal of Statistical Planning and Inference_.</span>

----


## Publications

 - <span>[Comparison of GMM and MD estimators for a panel regression model with endogenous regressors and an AR(1) disturbance](https://www.tandfonline.com/doi/pdf/10.1080/13504851.2024.2352166)</span> <span>, Kazuhiko Hayakawa and **Boyan Yin**\*, </span> <span>2024,</span> <span>_Applied Economics Letters_, </span><span> [GitHub](https://github.com/Byan2019/).</span>

---


## Under reviewing

- <span>A Comparison of Estimators for Dynamic Structural Equation Models with Intensive Longitudinal Data, </span>  <span>Kazuhiko Hayakawa and **Boyan Yin**\*,</span> <span>2024</span>, <span>_Structural Equation Modeling: A Multidisciplinary Journal_</span>,<span> [GitHub](https://github.com/Byan2019/)</span>.

---
<span>(* corresponding author)</span>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
