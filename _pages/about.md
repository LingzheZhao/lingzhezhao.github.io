---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am a sencond-year Ph.D. student in the <a href='https://en-soe.westlake.edu.cn/OurSchool/departmentcenter/departmentAI/'>Department of Artificial Intelligence</a> at <a href='https://en.westlake.edu.cn/'>Westlake University</a>, supervised by <a href='https://ethliup.github.io/'>Prof. Peidong Liu</a>. Prior to this, I received my Bachelor's degree from <a href='https://en.tongji.edu.cn/'>Tongji University</a>.
My research interests lie in 3D vision (e.g., Scene Representation, Reconsctuction and Understanding), Large Multimodal Models and their applications into Embodied AI (i.e. robots) and Mixed Reality.

# 🔥 News
- *2025.09*: &nbsp;🎉🎉 Our paper <b><em><a href='https://insomniaaac.github.io/siu3r/'>SIU-3R</a></em></b> is accepted to NeurIPS 2025 as Spotlight! Thanks to all collaborators!
- *2025.08*: &nbsp;🎉🎉 Our paper <b><em><a href='https://wangpeng000.github.io/MBA-SLAM/'>MBA-SLAM</a></em></b> is accepted to TPAMI! Thanks to <a href='https://wangpeng000.github.io/'>Peng</a> and all collaborators!
- *2025.07*: &nbsp;🎉🎉 Our paper <b><em><a href='https://lingzhezhao.github.io/CasualHDRSplat/'>Casual3DHDR</a></em></b> is accepted to ACM Multimedia 2025! Thanks to <a href='https://openreview.net/profile?id=~Shucheng_Gong2'>Shucheng</a>, <a href='https://akawincent.github.io/'>Wenpu</a> and all collaborators!
- *2024.07*: &nbsp;🎉🎉 Our paper <b><em><a href='https://lingzhezhao.github.io/BAD-Gaussians/'>BAD-Gaussians</a></em></b> is accepted to ECCV 2024! Thanks to <a href='https://wangpeng000.github.io/'>Peng</a> and all collaborators!

# 📝 Publications 

<!-- ACM MM 2025 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='CasualHDRSplat/static/images/teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Casual3DHDR: High Dynamic Range 3D Gaussian Splatting from Casually Captured Videos](https://dl.acm.org/doi/10.1145/3746027.3755612)

<a href='https://openreview.net/profile?id=~Shucheng_Gong2'>Shucheng Gong</a>\*, **Lingzhe Zhao\***, <a href='https://openreview.net/profile?id=~Wenpu_Li'>Wenpu Li</a>\*, Hong Xie, Yin Zhang, Shiyu Zhao, Peidong Liu

Acknowledgement: Xiang Liu

[**Project**](https://lingzhezhao.github.io/CasualHDRSplat/) [**ArXiv**](https://arxiv.org/abs/2504.17728) [**Code**](https://github.com/WU-CVGL/CasualHDRSplat)<strong><span class='show_paper_citations' data='mN764NsAAAAJ:Se3iqnhoufwC'></span></strong>
- We present Casual3DHDR, the first method for casual 3D high dynamic range (HDR) imaging using hand-held devices. Our method reconstructs high-quality 3D HDR scenes from a set of low dynamic range (LDR) images captured with varying exposure settings, addressing challenges such as dynamic scenes, complex camera motions, and varying lighting conditions.


</div>
</div>

<!-- TPAMI 2025 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div>
<video src='MBA-SLAM/static/MBA-SLAM.mp4' alt="sym" width="100%" autoplay muted loop></video></div></div>
<div class='paper-box-text' markdown="1">

[MBA-SLAM: Motion Blur Aware Gaussian Splatting SLAM](https://ieeexplore.ieee.org/document/11120442)

<a href='https://wangpeng000.github.io/'>Peng Wang</a>\*, **Lingzhe Zhao\***, Yin Zhang, Shiyu Zhao, Peidong Liu

[**Project**](https://wangpeng000.github.io/MBA-SLAM/) [**ArXiv**](https://arxiv.org/abs/2411.08279) [**Code**](https://github.com/WU-CVGL/MBA-SLAM)
<strong><span class='show_paper_citations' data='mN764NsAAAAJ:roLk4NBRz8UC'></span></strong>
- MBA-SLAM, the first deblurring SLAM that can accurately estimate the local camera motion trajectories within the exposure time and recovers the high quality 3D scene from blurry sequences.
</div>
</div>

<!-- ECCV 2024 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='BAD-Gaussians/static/images/overview.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BAD-Gaussians: Bundle Adjusted Deblur Gaussian Splatting](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03633.pdf)

**Lingzhe Zhao\***, <a href='https://wangpeng000.github.io/'>Peng Wang</a>\*, Peidong Liu

[**Project**](https://lingzhezhao.github.io/BAD-Gaussians/) [**ArXiv**](https://arxiv.org/abs/2403.11831) [**Code**](https://github.com/WU-CVGL/BAD-Gaussians) <strong><span class='show_paper_citations' data='mN764NsAAAAJ:Tyk-4Ss8FVUC'></span></strong>
- BAD-Gaussians successfully deblurs severe motion-blurred images, synthesizes higher-quality novel views, and achieves real-time rendering, surpassing previous SOTA implicit deblurring rendering methods.

</div>
</div>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span id="total_cit" style="display:none;"></span>

More publications can be found on Google Scholar: <a href='https://scholar.google.com/citations?user=mN764NsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

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
- Journal Reviewer for <strong>IEEE RA-L</strong>, <strong>IEEE TCSVT</strong>, <strong>IEEE TVCG</strong>, <strong>IEEE TMM</strong>.

# 🤝 Contact Me
- Email:
  zhaolingzhe AT westlake.edu.cn
