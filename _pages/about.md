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

Shenghui WU (伍圣晖) received his B.Eng. degree from Huazhong University of Science and Technology <a href='https://english.hust.edu.cn/'>(HUST)</a> in 2019. He earned his MPhil and Ph.D. degree from the Hong Kong University of Science and Technology <a href='https://hkust.edu.hk/'>(HKUST)</a> in 2021 and 2024, respectively, under the supervision of <a href="https://ece.hkust.edu.hk/eewangyw">Prof. Yiwen Wang</a> in the [Computational Cognitive Engineering Lab](https://bmi.hkust.edu.hk/). He is now a [**Research Assistant Professor**](https://ece.hkust.edu.hk/eewushenghui) in HKUST. 

His research interests include <strong>brain-machine interfaces</strong>, <strong>neural engineering</strong>, and <strong>reinforcement learning</strong>. His work has been published in top journals, including a cover story of *Nature Computational Science*, and selected for oral presentation and spotlight poster at multiple flagship international conferences. His work has also been featured in media outlets such as *Ta Kung Pao* and *HKEJ*.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2026.08.25*: &nbsp;🎉🎉I am invited to present at the Young Investigator Colloquiums (YIC) on the APSN-FAONS-HKSN Neuroscience conference 2026!
- *2026.06.26*: &nbsp;🎉🎉One paper is accecpted by SMC 2026!
- *2026.06.12*: &nbsp;🎉🎉I am awarded the Best Student Oral Presentation Finalist in SSNR2026!
- *2026.06.10*: &nbsp; One paper is selected for oral presentation at EMBC 2026.
- *2026.03.27*: &nbsp; Our work was selected for the [2026 Brain Machine Interfaces Innovation Achievements at the Zhongguancun Forum (中关村论坛) held on March 27th](https://news.qq.com/rain/a/20260328A02OC600).
- *2026.02.26*: &nbsp; Our work on behavior-reinforced spike generation has been selected as a featured article and the cover story of *Nature Computational Science*!
- *2026.01.05-01.09*: &nbsp; I am nominated to participate in the Global Young Scientists Summit (GYSS) 2026. See you in Singapore!
- *2025.12.12*: &nbsp; Our study was featured as a Spotlight Poster at the 2nd Chinese Conference on Brain-Machine Intelligence.
- *2025.08.05*: &nbsp; Three papers are accepted by EMBC NER 2025.


# 📝 Publications 

### 2026

<div class='paper-box' style="display:flex; flex-direction:row-reverse;">
  <div class='paper-box-image' style="flex:1; margin-left:20px;">
    <div><img src='images/TransregionalProsthesis.jpg' alt="prosthesis" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex:2;">

  [J6] _Transregional Neural Prostheses: Applications and Computational Tools_

  <strong style="color:#DE3163">Shenghui Wu</strong>, Jose C. Principe, Yiwen Wang.  
  In IEEE Transactions on Neural Systems and Rehabilitation Engineering (**Invited review paper**).

  [**Paper**](https://ieeexplore.ieee.org/abstract/document/11625931)  
  - This review systematizes and defines the **transregional neural prosthesis** as an artificial systems that re-establish endogenous neural communication across damaged pathways, and proposes a **computational framework** to provide a roadmap for future research.
  </div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nat. Comp. Sci.</div><img src='images/RLPP.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box'><div class='paper-box-image'><div><img src='images/RLPP.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[J5] _A generative spike prediction model using behavioral reinforcement for re-establishing neural functional connectivity_

<strong style="color:#DE3163">Shenghui Wu</strong>, Zhiwei Song, Xiang Zhang, Yifan Huang, Shuhang Chen, Xiang Shen, Jieyuan Tan, Mingdong Li, Ziyi Wang, Yujun Chen, Kai Liu, Dario Farina, Jose C. Principe, Yiwen Wang. In Nature Computational Science (**Featured Cover Article**).

[**Paper**](https://www.nature.com/articles/s43588-025-00915-5) | [**Code**](https://github.com/WuShenghui97/RLPP) 
- The study presents a generative spike-based framework to re-establish functional connectivity across pathway-damaged brain regions, enabling biomimetic neural prostheses and closed-loop brain stimulation.
</div>
</div>

### 2025
  - [C7] Zhiwei Song, <strong style="color:#DE3163">Shenghui Wu</strong>, Taiyan Zhou, Yiwen Wang. _Extracting Preserved Neural Latent Dynamics Across Tasks using Convolutional Transformer-based Variational Autoendecoder_. In Proceedings of 2025 47th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC). 🔗[[Paper]](https://ieeexplore.ieee.org/document/11251780/)
  - [C8] <strong style="color:#DE3163">Shenghui Wu</strong>, Xiang Zhang, Yiwen Wang. _Behavior-Reinforced Latent Alignment for Generating Functional Neural Spike Patterns_. In Proceedings of 2025 International Joint Conference on Neural Networks (IJCNN). 🔗[[Paper]](https://ieeexplore.ieee.org/document/11228048/)

### 2024
  - [C4] <strong style="color:#DE3163">Shenghui Wu</strong>, Xiang Zhang, Yifan Huang, Yiwen Wang. _Aligning Transregional Neural Dynamics with Transformer-based Variational Autoencoders_. In Proceedings of 2024 46th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC). 🔗[[Paper]](https://ieeexplore.ieee.org/document/10782188/)
  - [C5] Shicheng Qiu, Hongwei Mao, <strong style="color:#DE3163">Shenghui Wu</strong>, Yiwen Wang. _Investigating Internal Dynamics in Monkey’s Primary Motor Cortex during Reaching_. In Proceedings of 2024 46th Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC). 🔗[[Paper]](https://ieeexplore.ieee.org/document/10782466/)
  - [J3] <strong style="color:#DE3163">Shenghui Wu</strong>, Xiang Zhang, Yiwen Wang. _Neural Manifold Constraint for Spike Prediction Models under Behavioral Reinforcement_. In IEEE Transactions on Neural Systems and Rehabilitation Engineering 🔗[[Paper]](https://ieeexplore.ieee.org/document/10614238/)
  - [C6] Mingyi Wang, Jieyuan Tan, Yifan Huang, <strong style="color:#DE3163">Shenghui Wu</strong>, Zhiwei Song, Yiwen Wang. _Extracted Audio-Induced Reward Expectation Information from Local Field Potential in the Medial Prefrontal Cortex_. In Proceedings of 2024 IEEE International Conference on Systems, Man, and Cybernetics (SMC). 🔗[[Paper]](https://ieeexplore.ieee.org/document/10831756/)
  - [J4] Jieyuan Tan, Xiang Zhang, <strong style="color:#DE3163">Shenghui Wu</strong>, Zhiwei Song, Yiwen Wang. _Hidden Brain State-based Internal Evaluation Using Kernel Inverse Reinforcement Learning in Brain-machine Interfaces_. In IEEE Transactions on Neural Systems and Rehabilitation Engineering. 🔗[[Paper]](https://ieeexplore.ieee.org/document/10759843/)

### 2023
  - [C2] <strong style="color:#DE3163">Shenghui Wu (Corresponding)</strong> and Yiwen Wang. _Applying Neural Manifold Constraint on Point Process Model for Neural Spike Prediction_. In Proceedings of 2023 45th Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC). 🔗[[Paper]](https://ieeexplore.ieee.org/document/10340489/)
  - [C3] Jieyuan Tan, Xiang Zhang, <strong style="color:#DE3163">Shenghui Wu</strong>, Yiwen Wang. _State-space Model Based Inverse Reinforcement Learning for Reward Function Estimation in Brain-machine Interfaces_. In Proceedings of 2023 45th Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC). 🔗[[Paper]](https://ieeexplore.ieee.org/document/10340953/)
  - [J2] Jieyuan Tan, Xiang Zhang, <strong style="color:#DE3163">Shenghui Wu</strong>, Zhiwei Song, Shuhang Chen, Yifan Huang, Yiwen Wang. _Audio-induced medial prefrontal cortical dynamics enhances coadaptive learning in brain–machine interfaces_, In Journal of Neural Engineering. 🔗[[Paper]](https://iopscience.iop.org/article/10.1088/1741-2552/ad017d)

### 2022
  - [J1] <strong style="color:#DE3163">Shenghui Wu</strong>, Cunle Qian, Xiang Shen, Xiang Zhang, Yifan Huang, Shuhang Chen, Yiwen Wang. _Spike prediction on primary motor cortex from medial prefrontal cortex during task learning_. In Journal of Neural Engineering. 🔗[[Paper]](https://iopscience.iop.org/article/10.1088/1741-2552/ac8180)

### 2020
  - [C1] <strong style="color:#DE3163">Shenghui Wu</strong>, Cunle Qian, Xiang Shen, Xiang Zhang, Yifan Huang, Shuhang Chen, Yiwen Wang. _Investigating Co-Activation between Medial Prefrontal and Primary Motor Cortical Spike Trains during Task Learning_. In Proceedings of 2020 IEEE International Conference on Systems, Man, and Cybernetics (SMC). 🔗[[Paper]](https://ieeexplore.ieee.org/document/9283121)
  
  <!-- 💻 [[Github]](https://github.com/ArabelaTso/Learning-Based-ParaVerifer)  🎬 [[Video]](https://www.youtube.com/watch?v=6Dl2HiiiS4E&list=LL&index=8&t=1s&ab_channel=BellaTSO) -->


# 🎖 Honors and Awards
- *2026* Best Student Oral Presentation Finalist, Summer School on NeuroRehabilitation (SSNR 2026), Baiona, Spain
- *2026* Outstanding Publication in Neuroscience Award, Hong Kong Plexon Inc. 
- *2026* Brain-Machine Interfaces Innovation Achievement at the Zhongguancun Forum, Beijing, China 
- *2025* Spotlight Poster, the 2nd Chinese Conference on Brain-Machine Intelligence
- *2024, 2023* HKUST RedBird Academic Excellence Award
- *2024* NextGen Scholar Award, IEEE EMBC
- *2023* HKUST ECE Best Teaching Assistant Award 2022/23
- *2019* HUST Outstanding Graduate
- *2018* National Encouragement Scholarship
- *2018* First Prize of Microchip China Scholarship


# 🎓 Educations
- *2021.09 - 2024.08*, **Ph.D**, The Hong Kong University of Science and Technology.
- *2019.09 - 2021.08*, **MPhil**, The Hong Kong University of Science and Technology.
- *2015.09 - 2019.06*, **B.Eng**, Huazhong University of Science and Technology.


# 🖐️ Academic Services & Activities
- **Reviewer** for J. Neural Eng., EMBC 2025, IJCNN 2025 2026, EMBC NER 2025.
- Attending the **GYSS (Global Young Scientists Summit) 2026** in Singapore 
- **Session Chair** of IJCNN 2025.
- **Ambassador** for 2023 IEEE EMBS Student Mentoring Program (Online).
- **Organization Committee member** for the 4th International Workshop on Neural Engineering and Rehabilitation (Chengdu, China).


# 💬 Presentations & Invited Talks
- *2026.08.25*, <strong>Towards Transregional Neural Prostheses: Re-establishing neural functional connectivity with generative spike prediction models </strong>. In the Young Investigator Colloquiums (YIC) of the APSN-FAONS-HKSN Neuroscience conference 2026, Hong Kong.
- *2026.06.07*, <strong>Shaping population spike patterns under behavioral reinforcement with neural manifold constraint</strong>. In SSNR2026, Baiona, Spain. 
- *2024.05*, <strong>Reinforcement learning-based spike prediction for transregional neural prostheses</strong>. In ECE Future Leaders PG Seminar, HKUST, Hong Kong. 


# 📖 Teaching
- *2022 Fall*, *2020 Fall*, **Teaching Assistant**, Signals and Systems (ELEC 2100).
- *2022 Spring*, **Teaching Assistant**, Machine Learning on Images (ELEC 4130).
- *2020 Spring*, **Teaching Assistant**, Statistical Signal Analysis and Applications in Neural Engineering (ELEC 4830 & BIEN 4310).


# 💻 Working Experience
- *2026.01 - present*, <strong>Research Assistant Professor</strong>, HKUST
- *2024.09 - 2025.12*, <strong>Research Associate</strong>, HKUST, working with <a href="https://ece.hkust.edu.hk/eewangyw">Prof. Yiwen Wang</a>
- *2017.09 - 2019.06*, <strong>Backend Developer</strong>, Part-time Intern at [Wuhan Xiaoan Technology Co., Ltd](https://www.xiaoantech.com/)
