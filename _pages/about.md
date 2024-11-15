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
Hello! This is Shenghao Xie. I am currently a first-year Ph.D. student at Academy for Advanced Interdisciplinary Studies, Peking University, working with Prof. Lei Ma and Prof. Tiejun Huang. I am now also a visiting student of [Tsinghua Statistical Artificial Intelligence & Learning(TSAIL)](https://ml.cs.tsinghua.edu.cn/) Group, Tsinghua University, collaborating with [Prof. Hang Su](https://www.suhangss.me/) and [Prof. Jun Zhu](https://ml.cs.tsinghua.edu.cn/~jun/index.shtml). Before that, I received my B.E. degree from School of Cyber Science and Engineering, Wuhan University in 2024, advised by [Prof. Shanghang Zhang](https://www.shanghangzhang.com/).

My long-term research goal is to build vision foundation models unifying understanding and generation across various types of data and tasks, and ultimately enabling flexible interactions with the real physical world. Recently, I am interested in expanding vision foundation models into 3D vision and medical image analysis. If you are interested in my work, please feel free to send me an email. 


# 🔥 News
- *2024.10*: &nbsp;🎉🎉 Our paper "[Embedded prompt tuning: Towards enhanced calibration of pretrained models for medical images](https://www.sciencedirect.com/science/article/abs/pii/S136184152400183X)" is accepted by *MIA 2024 AIFM Special Issue*.  

# 📝 Selected Publications
(__*__ denotes equal contribution. __†__ denotes corresponding author.)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Towards Unifying Understanding and Generation in the Era of Vision Foundation Models: A Survey from the Autoregression Perspective**

**Shenghao Xie**, Wenqiang Zu, Mingyang Zhao, Duo Su, Shilong Liu, Ruohua Shi, Guoqi Li, Shanghang Zhang, Lei Ma

[**Paper**](https://arxiv.org/abs/2410.22217) <strong><span class='show_paper_citations' data='hcrnA7sAAAAJ:qjMakFHDy7sC'></span></strong>
[**Repo**](https://github.com/EmmaSRH/ARVFM)
- The first comprehensive survey to dive deep into the trend of unifying understanding and generation in vision foundation models from the autoregression perspective.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MIA 2024</div><img src='images/EPT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Embedded prompt tuning: Towards enhanced calibration of pretrained models for medical images**

Wenqiang Zu, **Shenghao Xie***, Qing Zhao, Guoqi Li, Lei Ma

[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S136184152400183X) <strong><span class='show_paper_citations' data='hcrnA7sAAAAJ:2osOgNQ5qMEC'></span></strong>
[**Code**](https://github.com/zuwenqiang/EPT)
- A new PEFT method, let's try to concat vision prompts with channels to achieve better adaptabilities of the vision foundation model!
</div>
</div>

# 🎖 Honors and Awards
- *2024.06* Outstanding Bachelor's Degree Thesis in Wuhan University.
- *2023.11* Lei Jun Undergraduate Scholarship in Computer Science.
- *2023.08* First Prize in National College Student Information Security Contest.  

# 💻 Internships
- *2023.09 - 2024.09*, research intern, [BAAI](https://www.baai.ac.cn/), China.
