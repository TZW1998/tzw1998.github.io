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

# 🧑‍💻️ About Me
<span class='anchor' id='about-me'></span>

I was born and raised in Shenzhen, a beautiful seaside city in China, in 1998. Currently, I am a final-year PhD student in Computer Science at The Chinese University of Hong Kong, Shenzhen. Prior to pursuing my PhD, I earned my bachelor's degree in Statistics from Sun Yat-sen University in Guangzhou, China, in 2020. My passions include mathematics, coding, and sports.

I have also had the privilege of interning at notable organizations such as SenseTime, Damo Academy, Alibaba, and Amazon, where I gained valuable experience and insights on Reinforcement Learning, Optimization and Generative AI.

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 💬 About My Research
<span class='anchor' id='-research'></span>
Throughout my PhD studies, I have focused on tackling challenges in modern machine learning using insights from mathematical optimization.

One line of my research spans new techniques for combinatorial optimization, as demonstrated in [Tang et al. UAI 2023](https://proceedings.mlr.press/v216/tang23a.html), and distributed optimization, as seen in [Tang et al. AAAI 2024](https://ojs.aaai.org/index.php/AAAI/article/view/29454/30740).

Since 2022, I have also delved into the research of Generative AI, particularly Diffusion Generative Models. I have led several intriguing research projects in this area, including post-training and Reinforcement Learning with Human Feedback (RLHF) for diffusion models, as detailed in [Tang et al. ICLR 2024](https://openreview.net/pdf/120f6a88f789639b88a7a1d19b56c2c13c15d81a.pdf) and [Tang et al. 2024 Preprint](https://arxiv.org/abs/2405.18881). Additionally, I have explored advanced techniques from solving nonlinear equations to expedite the sampling of diffusion models, as presented in [Tang et al. ICML 2024](https://arxiv.org/abs/2402.09970).

Recently, I have been shifting part of my research focus to the post-training of multi-modal large language models (LLMs) and their intersection with diffusion models.

<!-- **(1) Optimization with Imperfect Function Feedback.** In many settings, obtaining perfect function feedback, like gradient or value, can be challenging. For example, distributed optimization requires compressing function feedback to improve communication efficiency between devices [Tang et al. AAAI 2024](https://ojs.aaai.org/index.php/AAAI/article/view/29454/30740), or optimizing with human ranking feedback for AI-generated content [Tang et al. ICLR 2024](https://openreview.net/pdf/120f6a88f789639b88a7a1d19b56c2c13c15d81a.pdf). The high-level idea behind these studies is to accurately estimate the ground-truth gradient from imperfect feedback using statistical techniques, then applying this estimation in optimization.

**(2) Learning Your Optimization Problem from Data.** Many engineering problems are solved by formulating optimization with manually-constructed models of the target world, including the objective function and constraints. However, these hand-crafted models can be difficult to create and often provide only a crude approximation of the real world due to simplified assumptions. With the rise of generative models like LLMs and Diffusion Models, an exciting approach is to use the learned distribution as world models for optimization, effectively learning constraints for the optimization problem. Similarly, the optimization's objective function can also be learned from data, such as learning a reward model from human preferences [Ouyang et al.](https://proceedings.neurips.cc/paper_files/paper/2022/file/b1efde53be364a73914f58805a001731-Paper-Conference.pdf). With this approach, it becomes possible to tackle complex and abstract engineering problems such as "generate a beautiful image" by learning an image generative model (acting as the feasible region) and a reward model for evaluating the image's aesthetic (acting as the objective function) [Tang et al. 2024 Preprint](https://arxiv.org/abs/2405.18881).

**(3) Useful Optimization Tricks.** Proper optimization tricks can lead to unreasonable effectivness in some machine learning applications. For example, entropy-regularized optimal transport can be used for smoothing optimization over permutations [Tang et al. UAI 2023](https://proceedings.mlr.press/v216/tang23a.html), and techniques from solving nonlinear equations can expedite the sampling of diffusion models [Tang et al. ICML 2024](https://arxiv.org/abs/2402.09970). -->


<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


# 🔥 News
- *2024.05*: &nbsp;🎉🎉 Hello there! I've just launched my homepage to share my journey in Machine Learning.
 

# 📝 Featured Publications
<span class='anchor' id='-publications'></span>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->
- "Tuning-Free Alignment of Diffusion Models with Direct Noise Optimization", **Preprint (A short version in 2nd SPIGM workshop @ ICML 2024)**

  <u>Zhiwei Tang</u>, Jiangweizhi Peng, Jiasheng Tang, Mingyi Hong, Fan Wang, Tsung-Hui Chang

  <a href="https://arxiv.org/abs/2405.18881" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #007BFF; color: white; border-radius: 5px; text-decoration: none;">Paper</a> <a href="https://github.com/TZW1998/Direct-Noise-Optimization" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #FFD700; color: white; border-radius: 5px; text-decoration: none;">Code</a>


- "Accelerating Parallel Sampling of Diffusion Models", **ICML 2024**

  <u>Zhiwei Tang</u>, Jiasheng Tang, Hao Luo, Fan Wang, Tsung-Hui Chang

  <a href="https://arxiv.org/abs/2402.09970" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #007BFF; color: white; border-radius: 5px; text-decoration: none;">Paper</a> <a href="https://github.com/TZW1998/ParaTAA-Diffusion" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #FFD700; color: white; border-radius: 5px; text-decoration: none;">Code</a>
  
  <!-- <a href="https://github.com/TZW1998/ParaTAA-Diffusion" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #FFD700; color: white; border-radius: 5px; text-decoration: none;">Code</a> -->


- "Zeroth-Order Optimization Meets Human Feedback: Provable Learning via Ranking Oracles", **ICLR 2024**

  <u>Zhiwei Tang</u>, Dmitry Rybin, Tsung-Hui Chang

  <a href="https://openreview.net/pdf/120f6a88f789639b88a7a1d19b56c2c13c15d81a.pdf" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #007BFF; color: white; border-radius: 5px; text-decoration: none;">Paper</a> <a href="https://github.com/TZW1998/Taming-Stable-Diffusion-with-Human-Ranking-Feedback" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #FFD700; color: white; border-radius: 5px; text-decoration: none;">Code</a>


- "$z$-SignFedAvg: A Unified Stochastic Sign-based Compression for Federated Learning", **AAAI 2024**

  <u>Zhiwei Tang</u>, Yanmeng Wang, Tsung-Hui Chang

  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/29454/30740" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #007BFF; color: white; border-radius: 5px; text-decoration: none;">Paper</a>


- "Low-Rank Matrix Recovery With Unknown Correspondence", **UAI 2023**

  <u>Zhiwei Tang</u>, Tsung-Hui Chang, Xiaojing Ye, Hongyuan Zha

  <a href="https://proceedings.mlr.press/v216/tang23a.html" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #007BFF; color: white; border-radius: 5px; text-decoration: none;">Paper</a>

For my full publication list, please see my [google scholar](https://scholar.google.com/citations?user=GN-N9c8AAAAJ&hl=en) or my [CV](assets/resume.pdf).

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
<span class='anchor' id='-educations'></span>
- *2020.09 - Present*, PhD in Computer Science, The Chinese University of Hong Kong, Shenzhen, China
- *2016.09 - 2020.07*, BS in Statistics, Sun Yat-sen University, Guangzhou, China

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->


# 🔍 Review Service
<span class='anchor' id='-review'></span>
- NeurIPS 2021-2024
- ICLR 2024
- ICML 2022-2024
- ICASSP 2022-2023
