---
title: "Junteng Liu"
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a first-year PhD candidate at HKUST NLP Group, pursuing a Ph.D. in Computer Science (2024-Present). My PhD supervisor is Professor Junxian He. I graduated from Shanghai Jiao Tong University (SJTU) in June 2024, where I completed a B.Eng. (2020-2024). Professor Junxian He also advised me during my undergraduate studies at SJTU.

My research focuses on natural language processing and machine learning. My interests include LLM reasoning and reinforcement learning, hallucination in vision-language models (VLM), and LLM truthfulness and interpretability.

## Research Experience

- **Research Intern, MINIMAX** — February 2025 - Present.
- **Research Intern, Tencent WXG** — June 2024 - September 2024. Advisor: Zifei Shan.
- **Research Intern, Shanghai AI Lab** — June 2023 - December 2023. Advisor: Prof. Yu Cheng.

## Education

- **Hong Kong University of Science and Technology (HKUST)** — Ph.D. in Computer Science, 2024-Present. PhD supervisor: Professor Junxian He.
- **Shanghai Jiao Tong University (SJTU)** — B.Eng., 2020-2024. Graduated in June 2024. Undergraduate advisor: Professor Junxian He.

## Honors

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

## Publications

{% for category in site.publication_category %}
  {% assign title_shown = false %}
  {% for post in site.publications reversed %}
    {% if post.category == category[0] %}
      {% unless title_shown %}
### {{ category[1].title }}
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
{% endfor %}

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Publication profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
