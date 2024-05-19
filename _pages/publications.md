---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}


<p style="font-size: 24pt;"><strong>Posters and Presentations</strong></p>
K. Bhattarai, I. Y.Oh, J. M. Sierra, P. R.O. Payne, Z. Abrams, A. M. Lai. “Leveraging GPT-4 for Identifying Clinical
Phenotypes in Electronic Health Records: A Performance Comparison between GPT-4, GPT-3.5-turbo and spaCy’s
Rule-based & Machine Learning-based methods.” Accepted at AMIA Informatics Summit, 2024


M. Zhao, I. Oh, A. Lewis, K. Bhattarai, A. Kernberg, M. Nelson, P. R.O. Payne, A. M. Lai, A. Gupta, Predicting
Superimposed Preeclampsia in Women with Chronic Hypertension Using Electronic Health Records Data. Accepted at
AMIA Annual Informatics Summit, 2023

K. Bhattarai, M. Hofford, S. Yu, S. Kim, A. Gupta, A. M. Lai, P. R.O. Payne, A. Michelson, Evaluation of SOFA
score for Outcome Prediction in COVID-19 ICU Patients. Accepted at AMIA Annual Informatics Summit, 2021
