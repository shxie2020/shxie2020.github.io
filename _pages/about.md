---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# 👨‍🎓 Biography
Hi! This is Shenghao Xie. I am currently a first-year Ph.D. student at Academy for Advanced Interdisciplinary Studies, Peking University, fortunately working with Prof. Lei Ma and Prof. Tiejun Huang. I am also a visiting student of [Tsinghua Statistical Artificial Intelligence & Learning (TSAIL)](https://ml.cs.tsinghua.edu.cn/) Group, Tsinghua University, advised by [Prof. Hang Su](https://www.suhangss.me/) and [Prof. Jun Zhu](https://ml.cs.tsinghua.edu.cn/~jun/index.shtml). Previously, I received my B.E. degree from School of Cyber Science and Engineering, Wuhan University in 2024, supervised by [Prof. Shanghang Zhang](https://www.shanghangzhang.com/).

My long-term research goal is to pursue the vision AGI and create corresponding social good. Recent interests have primarily focused on the vision foundation model, as well as its applications in AI4Healthcare:

**· Vision Foundation Model.** Firstly, I attempt to unlock the scaling law and zero-shot generalization in vision foundation models by integrating various data (both spatial and temporal, *e.g.,* 2D, 3D, videos, and 4D) and tasks (both perception and generation, *e.g.,* segmentation, caption, translation, and editing). Then I seek to further equip them with reasoning and emboddied interaction capabilities.     

**· AI for Healthcare.** I am committed to addressing valuable medical problems and building AI systems that effectively assist doctors. Specifically, I develop data-driven discriminative models based on large-scale medical images (*e.g.,* early cancer detection). Moreover, I also explore how to leverage generative models with clinically meaningful evaluation metrics for some data-scarce scenarios (*e.g.,* rare diseases).

I am open to both collaborations and discussions, please feel free to send me an email. 


# 🔥 News
- *2024.10*: &nbsp;🎉🎉 Our paper "[*Embedded Visual Prompt Tuning*](https://www.sciencedirect.com/science/article/abs/pii/S136184152400183X)" is accepted by **MIA 2024 AIFM Special Issue**.  

# 📝 Selected Publications
(__*__ denotes co-first author. __†__ denotes corresponding author. View the full publication list on my google scholar.)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/UGVFM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Towards Unifying Understanding and Generation in the Era of Vision Foundation Models: A Survey from the Autoregression Perspective**

**Shenghao Xie**, Wenqiang Zu, Mingyang Zhao, Duo Su, Shilong Liu, Ruohua Shi, Guoqi Li, Shanghang Zhang, Lei Ma

[**Paper**](https://arxiv.org/abs/2410.22217) <strong><span class='show_paper_citations' data='hcrnA7sAAAAJ:qjMakFHDy7sC'></span></strong>
[**Repo**](https://github.com/shxie2020/Awesome-UGVFM/)
- The first comprehensive survey to dive deep into the trend of unifying understanding and generation in vision foundation models from the autoregression perspective.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MIA 2024</div><img src='images/EPT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Embedded Visual Prompt Tuning**

Wenqiang Zu, **Shenghao Xie***, Qing Zhao, Guoqi Li, Lei Ma

[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S136184152400183X) <strong><span class='show_paper_citations' data='hcrnA7sAAAAJ:2osOgNQ5qMEC'></span></strong>
[**Code**](https://github.com/zuwenqiang/EPT)
- Embed but not prepend, let's insert prompts into embedding channels! 
</div>
</div>

# 🎖 Honors and Awards
- *2024.06* Outstanding Bachelor's Degree Thesis at Wuhan University.
- *2023.11* Lei Jun Computer Science Undergraduate Scholarship.
- *2023.08* First Prize at National College Student Information Security Contest.  

# 💻 Internships
- *2023.09 - 2024.09*, research intern, [Beijing Academy of Artificial Intelligence (BAAI)](https://www.baai.ac.cn/), Beijing, China. Mentor: Lei Ma, Tiejun Huang.
