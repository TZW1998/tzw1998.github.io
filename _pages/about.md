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

I was born and raised in Shenzhen, one of the largest cities in China, on December 5, 1998. Currently, I am a final-year PhD student in Computer Science at The Chinese University of Hong Kong, Shenzhen. Before pursuing my PhD degree, I obtained my bachelor's degree in Statistics from Sun Yat-sen University, Guangzhou, China, in 2020. I love math, coding, and sports.

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 💬 About My Research
<span class='anchor' id='-research'></span>
Throughout my PhD studies, I've focused on creating new optimization theories and algorithms to tackle challenges in modern machine learning applications, including privacy-preserving machine learning, distributed optimization, and most recently, generative models such as LLMs and Diffusion Models. I'd like to share with you three key mindsets that have guided my research.

**(1) Optimization with Imperfect Function Feedback** In many settings, obtaining perfect function feedback, like gradient or value, can be challenging. For example, distributed optimization requires compressing function feedback to improve communication efficiency between devices [Tang et al. AAAI 2024](https://ojs.aaai.org/index.php/AAAI/article/view/29454/30740), or optimizing with human ranking feedback for AI-generated content [Tang et al. ICLR 2024](https://openreview.net/pdf/120f6a88f789639b88a7a1d19b56c2c13c15d81a.pdf). The high-level idea behind these studies is to accurately estimate the ground-truth gradient from imperfect feedback using statistical techniques, then applying this estimation in optimization.

**(2) Learning Your Optimization Problem from Data** 

**(3) Useful Optimization Tricks** Proper optimization tricks can lead to unreasonable effectivness in some machine learning applicataions. For eaxmple, one can leverage entropic-regularzied optimal transport for smooting the optimization over permutation [Tang et al. UAI 2023](https://proceedings.mlr.press/v216/tang23a.html), and also one can speedup the sampling of diffusion models by using techniques from speeding up solving nonlinear equations.

Proper optimization tricks can lead to surprisingly effective results in some machine learning applications. For example, entropic-regularized optimal transport can be used for smoothing optimization over permutations [Tang et al. UAI 2023](https://proceedings.mlr.press/v216/tang23a.html), and techniques from solving nonlinear equations can expedite the sampling of diffusion models [Tang et al. ICML 2024](https://arxiv.org/abs/2402.09970).

<span style="color: red;">I am open to research collaborations and discussions, as well as opportunities in industry. Please don't hesitate to contact me!</span>

<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


# 🔥 News
<span class='anchor' id='-news'></span>
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
- "Tuning-Free Alignment of Diffusion Models with Direct Noise Optimization", **Preprint**

  <u>Zhiwei Tang</u>, Jiangweizhi Peng, Jiasheng Tang, Mingyi Hong, Fan Wang, Tsung-Hui Chang

  <a href="https://arxiv.org/abs/2405.18881" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #007BFF; color: white; border-radius: 5px; text-decoration: none;">Paper</a>


- "Accelerating Parallel Sampling of Diffusion Models", **ICML 2024**

  <u>Zhiwei Tang</u>, Jiasheng Tang, Hao Luo, Fan Wang, Tsung-Hui Chang

  <a href="https://arxiv.org/abs/2402.09970" style="display: inline-block; padding: 8px 15px; margin: 5px; background-color: #007BFF; color: white; border-radius: 5px; text-decoration: none;">Paper</a> 
  
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

# 💻 Internships
<span class='anchor' id='-internships'></span>
- *2023.10 - 2024.06*, Research Intern, Damo Academy, Alibaba Group, Hangzhou, China.
- *2019.10 - 2020.07*, Research Intern, SenseTime Group, Shenzhen, China.

# 🔍 Review Service
<span class='anchor' id='-review'></span>
- NeurIPS 2021-2024
- ICLR 2024
- ICML 2022-2024
- ICASSP 2022-2023