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
I currently serve as a Senior Engineer specializing in Perception Technologies for Robotaxi at [Baidu](https://en.wikipedia.org/wiki/Baidu) Inc. Prior to this role, I embarked on a wanderful journey at [SenseTime](https://www.sensetime.com/cn)'s Intelligent Automotive Group, where I contributed to the development of [SparseLIF](https://arxiv.org/pdf/2403.07284), a high-performance fully-sparse 3D object detector, which ranks **1st** on the [nuScenes leaderboard](https://www.nuscenes.org/object-detection?externalData=no&mapData=all&modalities=Any), outperforming all state-of-the-art 3D detectors by a notable margin. Thanks to Director [Zhe Wang](https://wang-zhe.me/), [Xiao Song](https://scholar.google.com.hk/citations?user=tXuvWDYAAAAJ&hl=zh-CN), and all other teammates!

My research interests include 3D Vision and Multi-modality Learning for Autonomous Driving. During my master's studies at the College of Computer Science, [Sichuan University](https://www.scu.edu.cn), I had the privilege of publishing research papers in esteemed journals and conferences, _i.e_, TPAMI and CVPR.


# 🔥 News
- *2024.07*: &nbsp;🔥 Our paper [SparseLIF: High-Performance Sparse LiDAR-Camera Fusion for 3D Object Detection](https://arxiv.org/pdf/2403.07284) is accepted by ECCV’ 2024. 
- *2024.03*: &nbsp;🔥 Our 3D object detector SparseLIF ranks **1st** on the nuScenes leaderboard! 
- *2023.11*: &nbsp;🔥 Our paper [Semantic Invariant Multi-view Clustering with Fully Incomplete Information](https://ieeexplore.ieee.org/document/10319403/media#media) is accepted by TPAMI’ 2023.  
- *2023.10*: &nbsp;🎉 I am awarded the National Scholarship of China (Top 1%). 
- *2023.10*: &nbsp;🎉 I am awarded the Outstanding Graduate of Sichuan Province (Top 4%). 
<!-- - *2023.10*: &nbsp;🎉 I join SenseTime, Intelligent Automative Group as a research intern in Beijing. -->
- *2023.09*: &nbsp;🎉 I am awarded the Top-grade Scholarship for Graduate Students. 
- *2023.02*: &nbsp;🔥 Our paper [Deep Fair Clustering via Maximizing and Minimizing Mutual Information: Theory, Algorithm and Metric](https://openaccess.thecvf.com/content/CVPR2023/papers/Zeng_Deep_Fair_Clustering_via_Maximizing_and_Minimizing_Mutual_Information_Theory_CVPR_2023_paper.pdf) is accepted by CVPR’ 2023. 


# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<div class='paper-box'>

<div class='paper-box-text' markdown="1">

[ECCV’ 2024] [SparseLIF: High-Performance Sparse LiDAR-Camera Fusion for 3D Object Detection](https://arxiv.org/pdf/2403.07284)

Hongcheng Zhang<sup>†</sup>, Liu Liang<sup>†</sup>, **Pengxin Zeng<sup>†</sup>**, Xiao Song, and Zhe Wang

- Ranking **1st** on the [nuScenes leaderboard](https://www.nuscenes.org/object-detection?externalData=no&mapData=all&modalities=Any) in the 3D object detection
- Robust against Camera Occlusion, LiDAR Failure, and Stuck
</div>

<div class='paper-box-image'><div>
<video width="416" height="117" controls> 
<!-- <video width="32" height="9" controls>  -->
  <source src="images/Visual.mp4" type="video/mp4">
  <source src="images/Visual.mp4" type="video/ogg">
  Your browser does not support the video tag.
</video>
</div></div>
<!-- <div class='paper-box-image'><div> <img src='Visual.mp4' alt="sym" width="100%"></div></div> -->
</div> 

- [TPAMI’ 2023] [Semantic Invariant Multi-view Clustering with Fully Incomplete Information](https://ieeexplore.ieee.org/document/10319403/media#media). **Pengxin Zeng**, Mouxing Yang, Yiding Lu, Changqing Zhang, Peng Hu, and Xi Peng
<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->
<!-- † -->

- [CVPR’ 2023] [Deep Fair Clustering via Maximizing and Minimizing Mutual Information: Theory, Algorithm and Metric](https://openaccess.thecvf.com/content/CVPR2023/papers/Zeng_Deep_Fair_Clustering_via_Maximizing_and_Minimizing_Mutual_Information_Theory_CVPR_2023_paper.pdf). **Pengxin Zeng<sup>†</sup>**, Yunfan Li<sup>†</sup>, Peng Hu, Dezhong Peng, Jiancheng Lv, and Xi Peng

†: Equal Contribution

# 📖 Experiences & Educations 
- *2023.10 - now*, Research Intern, Sense Time, Intelligent Automative Group.
  - Director: [Zhe Wang](https://wang-zhe.me/)

- *2021.09 - now*, Master, Sichuan University, China.
  - Mentor: Prof. Xi Peng
  - National Scholarship of China (Top 1%)
  - Outstanding Graduate of Sichuan Province (Top 4%)
  - Top-grade Scholarships throughout all years

- *2017.09 - 2021.06*, Bachelar, Sichuan University, China.
  - Outstanding Graduate Nomination
  - Member of Innovation Class


<!-- # 🎖 Honors and Awards -->
<!-- - *2023.10*: National Scholarship of China (Top 1%). 
- *2023.10*: Outstanding Graduate of Sichuan Province (Top 4%). 
- *2023.09*: Top-grade Scholarship for Graduate Students, 2023. 
- *2021.09*: Top-grade Scholarship for Graduate Students, 2021 & 2022.  -->
<!-- - *2021.06*: Outstanding Graduate Nomination, Bachelar.  -->



# 💬 Academic Service
- *2024*, Reviewer for IEEE Transactions on Circuits and Systems for Video Technology (TCSVT) 
- *2023*, Program committee member for Australasian Joint Conference on Artificial Intelligence (AJCAI) 
- *2021*, Reviewer for Asian Conference on Machine Learning (ACML)

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->