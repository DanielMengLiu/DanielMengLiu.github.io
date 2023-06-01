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

Hi, I am a Ph.D. candidate with <b>6-year</b> research experience on <b>speech signal processing / speaker recognition / multimodal learning</b>. I received joint guidance from Prof. <a href='http://cic.tju.edu.cn/faculty/wanglongbiao/wang.html'>Longbiao Wang</a>, <a href='http://www.jaist.ac.jp/~jdang/index-e.htm'>Jianwu Dang</a> (TJU) and Senior Scientist Dr. <a href='https://sites.google.com/view/kongaiklee'>Kong Aik Lee</a> (A\*STAR).

My research interest includes multimodal processing, anti-spoofing and speaker recognition. I have published over 20 papers at the top international speech conferences and Journals such as ICASSP, Interspeech and Computer speech \& language with total <a href='https://scholar.google.com/citations?user=8iSH77EAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FDanielMengLiu%2FDanielMengLiu.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

# 🏫 Education
- *2021.12 - 2022.12*, Research Assistant in Audio-Visual Speaker Verification, Agency for Science, Technology and Research (A\*STAR), Singapore.
- *2019.09 - 2023.12*, Ph.D. in Applied Computer Technology, Tianjin University (TJU), China.
- *2017.09 - 2019.06*, M.Sc. in Computer Technology, Tianjin University (TJU), China.
- *2013.09 - 2017.06*, B.Eng. in Computer Science and Technology, Changchun University of Science and Technology (CUST), China.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2023</div><img src='images/icassp23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[**AVLip**] [Cross-Modal Audio-Visual Co-Learning for Text-Independent Speaker Verification](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10095883)
  
**Meng Liu**, Kong Aik Lee, Longbiao Wang, Hanyi Zhang, Chang Zeng, Jianwu Dang
  
[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10095883)[[Code]](https://github.com/DanielMengLiu/AudioVisualLip)[[AVLip Datasets]](https://github.com/DanielMengLiu/AudioVisualLip)
  
- Keywords: frame-level correlation, cross-modal booster, MaxFormer, cross-attention, co-learn from scratch and with pretrained models.
- Highlights: visual speech (lip motion), temporal alignment, modality transfer, quality-aware fusion.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASRU 2021</div><img src='images/asru21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[**DeepLip**][DeepLip: A Benchmark for Deep Learning-Based Audio-Visual Lip Biometrics](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9688240)
  
**Meng Liu**, Longbiao Wang, Kong Aik Lee, Hanyi Zhang, Chang Zeng, Jianwu Dang
  
[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9688240)[[Code]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9688240)

- Keywords: audio-visual speaker verification, complementary biometric information, 3D+2D+1D convolution, late fusion, intermediate fusion.
- Highlights: lip biometrics, deep temporal dynamics, transfer learning, benchmark, over 50% improvement.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2021</div><img src='images/icassp21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Replay-Attack Detection Using Features with Adaptive Spectro-Temporal Resolution](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9414250)
  
**Meng Liu**, Longbiao Wang, Kong Aik Lee, Xuanda Chen, Jianwu Dang
  
[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9414250)
  
- Keywords: replay distortion, spectro-temporal artifacts, device mismatch.
- Highlights: F-ratio, attentive filtes, phonetic discrimination, adaptive phase features.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CSL 2021</div><img src='images/csl21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Replay Attack Detection Using Variable-Frequency Resolution Phase and Magnitude Features](https://www.sciencedirect.com/science/article/abs/pii/S0885230820300942)
  
**Meng Liu**, Longbiao Wang, Kong Aik Lee, Jianwu Dang
  
[[PDF]](https://www.sciencedirect.com/science/article/abs/pii/S0885230820300942)
  
- Keywords: replay attack, linear attentive filters, fully attentive filters, dynamic bandwidth filters.
- Highlights: attention mechanism, F-ratio, frequency subbands, phase feature.
</div>
</div>

- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 
- [Self-Supervised Training of Speaker Encoder with Multi-Modal Diverse Positive Pairs](https://arxiv.org/pdf/2210.15385.pdf), **Ruijie Tao**, Kong Aik Lee, Rohan Kumar Das, Ville Hautamäki and Haizhou Li, **TASLP**, 2023. 

# 💻 Open Source Code
- *Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/ECAPATDNN?style=social&label=ECAPA-TDNN)](https://github.com/TaoRuijie/ECAPATDNN)
- *Active Speaker Detection Framework* [![](https://img.shields.io/github/stars/TaoRuijie/TalkNet_ASD?style=social&label=TalkNet-ASD)](https://github.com/TaoRuijie/TalkNet_ASD)
- *Self-supervised Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/Loss-Gated-Learning?style=social&label=LGL)](https://github.com/TaoRuijie/Loss-Gated-Learning)
- *Audio-visual Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/AVCleanse?style=social&label=AVCleanse)](https://github.com/TaoRuijie/AVCleanse)
- *Ego4d Benchmark* [![](https://img.shields.io/github/stars/facebookresearch/Ego4d?style=social&label=Ego4d)](https://github.com/facebookresearch/Ego4d)

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

