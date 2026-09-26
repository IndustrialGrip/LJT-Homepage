---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present
* **B.Eng.**, Shanghai Jiao Tong University, 2020–2024

Work experience
======
* **Research Intern**, MINIMAX, February 2025–present
* **Research Intern**, Tencent WXG, June 2024–September 2024
* **Research Intern**, Shanghai AI Lab, June 2023–December 2023

Awards
======
* **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University

Skills
======
* **Machine learning and natural language processing**: large language models, vision-language models, and empirical research on LLM reasoning, hallucination in vision-language models, and LLM truthfulness
* **Research engineering**: designing and running large-scale experiments, and open-sourcing the research code, including the codebases released for SynLogic and for the chart-understanding study of vision-language models

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
