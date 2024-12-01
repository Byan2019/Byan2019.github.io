---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

 
## Preprints
 
 - <span style="font-weight: 600;">Maximum Likelihood Estimation of Short Panel Autoregressive Models with Flexible Form of Fixed Effects</span>   
 <span style="font-size:14px;">Kazuhiko Hayakawa and </span><span style="font-size:14px;font-weight:500;">Boyan Yin\*</span><span style="font-size:14px;">, 2024.

<p style="margin-bottom: 20px;"> </p>

----

<p style="margin-bottom: -10px;"> </p>

## Publications

 - <span style="font-weight: 600;">Comparison of GMM and MD estimators for a panel regression model with endogenous regressors and an AR(1) disturbance</span>   
 <span style="font-size:14px;">Kazuhiko Hayakawa, </span><span style="font-size:14px;font-weight:500;">Boyan Yin\*</span><span style="font-size:14px;"> , 2024.</span>    
     <span style="color:grey;font-size:14px;">Applied Economics Letters</span>  <span style="font-size:14px;">(**Spotlight**)</span>. 
    <span style="font-size:14px;">[Taylor&Francis](https://www.tandfonline.com/doi/pdf/10.1080/13504851.2024.2352166) | [GitHub](https://github.com/Byan2019/)</span>


<span style="font-size:14px">(* equal contribution or alphabetical order)</span>

---

<p style="margin-bottom: -10px;"> </p>

## Under reviewing

- <span style="font-weight: 600;">A Comparison of Estimators for Dynamic Structural Equation Models with Intensive Longitudinal Data</span>      
  <span style="font-size:14px;font-weight:500;">Kazuhiko Hayakawa</span><span style="font-size:14px">, Boyan Yin*/.</span>  
 <span style="color:grey;font-size:14px;">



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
