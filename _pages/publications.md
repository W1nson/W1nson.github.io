---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}


**Active Listening: Personalized Question Generation in Open-Domain Social Conversation with User Model Based Prompting** \\
Kevin Bowden, Yue Fan, <ins>Winson Chen</ins>, Wen Cui, Davan Harrison, Xin Wang, Marilyn Walker \\
_EMNLP 2024_ \\
[[paper](https://aclanthology.org/2024.findings-emnlp.826/)]

**Athena 3.0: personalized multimodal chatbot with neuro-symbolic dialogue generators** \\
Yue Fan, Kevin K. Bowden, Wen Cui, <ins>Winson Chen</ins>, Vrindavan Harrison, Angela Ramirez, Saaket Agashe, Xinyue Gabby Liu, Neha Pullabhotla, Nan Qiang Jeshwanth Bheemanpally, Sugam Garg, Marilyn Walker, Xin Eric Wang \\
_Alexa Prize SocialBot Grand Challenge 5 Proceedings 2023_ \\
[[paper](https://assets.amazon.science/2c/ff/d6eb3f0148b8bf0b2fc446c1d5f8/athena-3.0%20Personalized%20Multimodal%20ChatBot%20with%20Neuro-Symbolic%20Dialogue%20Generators.pdf)]


**Early experience with transformer-based similarity analysis for DataRaceBench** \\
<ins>Winson Chen</ins>, Tristan Vanderbruggen, Pei-Hung Lin, Chunhua Liao, Murali Emani \\
_SC 2024 / Correctness 2022_ \\
[[paper](https://ieeexplore.ieee.org/abstract/document/10027519)]


**Making Machine Learning Datasets and Models FAIR for HPC: A Methodology and Case Study** \\
Pei-Hung Lin*, Chunhua Liao, <ins>Winson Chen</ins>, Tristan Vanderbruggen, Murali Emani, Hailu Xu \\
_TransAI 2022_ \\
[[paper](https://ieeexplore.ieee.org/abstract/document/9951530)]


**Aerial vision-and-dialog navigation** \\
Yue Fan*, <ins>Winson Chen</ins>, Tongzhou Jiang, Chun Zhou, Yi Zhang, Xin Eric Wang \\
_Findings of ACL 2023_ \\
[[paper](https://aclanthology.org/2023.findings-acl.190/)]





<!-- New style rendering if publication categories are defined -->
<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} -->



