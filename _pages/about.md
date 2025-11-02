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

I am a sencond-year Ph.D. student in the <a href='https://en-soe.westlake.edu.cn/OurSchool/departmentcenter/departmentAI/'>Department of Artificial Intelligence</a> at <a href='https://en.westlake.edu.cn/'>Westlake University</a>, supervised by <a href='https://ethliup.github.io/'>Prof. Peidong Liu</a>. Prior to this, I received my Bachelor's degree from <a href='https://en.tongji.edu.cn/'>Tongji University</a>.
My research interests lie in 3D vision (e.g., Scene Representation, Reconsctuction and Understanding), Large Multimodal Models and their applications into Embodied AI (i.e. robots) and Mixed Reality.

(google scholar badge <a href='https://scholar.google.com/citations?user=mN764NsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

# 🔥 News
- *2005.08*: &nbsp;🎉🎉 Our paper <b><em>MBA-SLAM</em></b> is accepted to TPAMI! Thanks to <a href='https://wangpeng000.github.io/'>Peng</a> and all collaborators!
- *2025.07*: &nbsp;🎉🎉 Our paper <b><em>Casual3DHDR</em></b> is accepted to ACM 2025! Thanks to <a href='https://openreview.net/profile?id=~Shucheng_Gong2'>Shucheng</a>, <a href='https://akawincent.github.io/'>Wenpu</a> and all collaborators!
- *2024.07*: &nbsp;🎉🎉 Our paper <b><em>BAD-Gaussians</em></b> is accepted to ECCV 2024! Thanks to <a href='https://wangpeng000.github.io/'>Peng</a> and all collaborators!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='BAD-Gaussians/static/images/overview.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BAD-Gaussians: Bundle Adjusted Deblur Gaussian Splatting](https://arxiv.org/abs/2403.11831)

**Lingzhe Zhao\***, Peng Wang*, Peidong Liu

[**Project**](https://lingzhezhao.github.io/BAD-Gaussians/) <strong><span class='show_paper_citations' data='mN764NsAAAAJ:Tyk-4Ss8FVUC'></span></strong>
- BAD-Gaussians successfully deblurs severe motion-blurred images, synthesizes higher-quality novel views, and achieves real-time rendering, surpassing previous SOTA implicit deblurring rendering methods.


</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->

# 🔍 Services
- Conference Reviewer for <strong>CVPR</strong>, <strong>NeurIPS</strong>, <strong>ACM Multimedia</strong>, <strong>IROS</strong>.
- Journal Reviewer for <strong>IEEE TMM</strong>, <strong>IEEE TCSVT</strong>, <strong>IEEE RA-L</strong>.

# 🤝 Contact Me
- Email:
  zhaolingzhe AT westlake.edu.cn
