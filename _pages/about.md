---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am **Junteng Liu**, a first-year PhD candidate at the **HKUST NLP Group** of the Hong Kong University of Science and Technology, where I am supervised by **Professor Junxian He**. I completed my B.Eng. at Shanghai Jiao Tong University in June 2024.

My research lies at the intersection of **natural language processing** and **machine learning**, with a focus on large language models. My research interests are:

- **LLM reasoning and reinforcement learning**
- **Hallucination in vision-language models (VLMs)**
- **LLM truthfulness and interpretability**

## Academic background

- **Ph.D. in Computer Science** — Hong Kong University of Science and Technology, 2024–Present
- **B.Eng.** — Shanghai Jiao Tong University, 2020–2024

## Research experience

- **Research Intern, MINIMAX** (February 2025–present)
- **Research Intern, Tencent WXG** (June 2024–September 2024), advised by Zifei Shan
- **Research Intern, Shanghai AI Lab** (June 2023–December 2023), advised by Prof. Yu Cheng

## Awards

- **Zhiyuan Honor Scholarship** — Shanghai Jiao Tong University

## Publications

{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h3>{{ category[1].title }}</h3>
        <hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

## Skills

- **Machine learning and natural language processing**: large language models, vision-language models, and empirical research on LLM reasoning, hallucination in vision-language models, and LLM truthfulness
- **Research engineering**: designing and running large-scale experiments, and open-sourcing the research code, including the codebases released for SynLogic and for the chart-understanding study of vision-language models

## Contact

- **Email**: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub**: [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar**: [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter)**: [@junteng88716710](https://twitter.com/junteng88716710)
