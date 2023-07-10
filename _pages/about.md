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

My research interest includes multimodal processing, anti-spoofing and speech recognition. I have published over 20 papers at the top international speech conferences and Journals such as ICASSP, Interspeech and Computer speech \& language with total <a href='https://scholar.google.com/citations?user=8iSH77EAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FDanielMengLiu%2FDanielMengLiu.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

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

- **Liu, M.**, Wang, L., Lee, K.A., & Dang, J. Text-Independent and Text-Dependent Audio-Visual Speaker Verification Using Lip Biometrics. IEEE/ACM Transactions on Audio, Speech, and Language Processing. (Under Review)
- Zhang, H., Wang, L., Lee, K. A.,  **Liu, M.**, Dang, J., and Meng, H. Meta-Generalization for Domain-Invariant Speaker Verification. IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 31, pp. 1024-1036, 2023, doi: 10.1109/TASLP.2023.3244518.                                                   
- Oo, Z., Wang, L., Phapatanaburi, K., **Liu, M.**, Nakagawa, S., Iwahashi, M., & Dang, J. (2019). Replay Attack Detection with Auditory Filter-based Relative Phase Features. EURASIP journal on audio, speech, and music processing, 2019(1), 1-11. 
- **Liu, M.** Wang, L., Dang, J., Nakagawa, S., Guan, H., & Li, X. (2019, May). Replay Attack Detection Using Magnitude and Phase Information with Attention-based Adaptive Filters. In 2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 6201-6205). 
- **Liu, M.**, Wang, L., Oo, Z., Dang, J., Li, D., & Nakagawa, S. (2018, November). Replay Attacks Detection Using Phase and Magnitude Features with Various Frequency Resolutions. In 2018 11th International Symposium on Chinese Spoken Language Processing (ISCSLP) (pp. 329-333). 
- Liu, X., **Liu, M.**, Wang, L., Lee, K. A., Zhang, H., & Dang, J. (2023, June). Leveraging Positional-related Local-global Dependency for Synthetic Speech Detection. In 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (Accepted). 
- Liu, X., **Liu, M.**, Zhang, L., Zhang, L., Zeng, C., Li, K., Li, N., Lee, K.A., Wang, L., & Dang, J. (2022, October). Deep Spectro-temporal Artifacts for Detecting Synthesized Speech. In Proceedings of the 1st International Workshop on Deepfake Detection for Audio Multimedia (pp. 69-75) (ACM MM Workshop). 
- Hui, C., Zhang, H., Wang, L., Lee, K. A., **Liu, M.**, & Dang, J. (2023, June). Self-Supervised Audio-Visual Speaker Representation with Co-Meta Learning. In 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (Accepted).
- Sun, Y., Zhang, H., Wang, L., Lee, K. A., **Liu, M.**, & Dang, J. (2023, June). Noise-Disentanglement Metric Learning for Robust Speaker Verification. In 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (Accepted).
- Zhang, H., Wang, L., Lee, K.A., **Liu, M.**, Dang, J., & Chen, H. (2022). Learning Domain-Invariant Transformation for Speaker Verification. In 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 7177-7181).
- Zeng, C., Zhang, L., **Liu, M.**, & Yamagishi, J. Spoofing-aware Attention Back-end with Multiple Enrollment and Novel Trials Sampling Strategy for SASVC 2022. In Proc. Interspeech 2022 (pp.2883-2887).
- Li, K., Li, S., Lu, X., Akagi, M., **Liu, M.**, Zhang, L., Zeng, C., Wang, L., Dang, J. & Unoki, M. (2022). Data Augmentation Using McAdams-Coefficient-Based Speaker Anonymization for Fake Audio Detection. In Proc. Interspeech 2022 (pp.664-668). 
- Zhang, H., Wang, L., Lee, K. A., **Liu, M.**, Dang, J., & Chen, H. (2021, June). Meta-Learning for Cross-Channel Speaker Verification. In 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 5839-5843). 
- Wu, Y., Wang, L., Lee, K.A., **Liu, M.**, & Dang, J. (2021). Joint Feature Enhancement and Speaker Recognition with Multi-Objective Task-Oriented Network. In Proc. Interspeech 2021 (pp. 1089-1093).
- Zhang, H., Wang, L., Zhang, Y., **Liu, M.**, Lee, K. A., & Wei, J. (2020). Adversarial Separation Network for Speaker Recognition. In Proc. Interspeech 2020 (951-955). 
- Zhou, D., Wang, L., Lee, K. A., Wu, Y., **Liu, M.**, Dang, J., & Wei, J. (2020). Dynamic Margin Softmax Loss for Speaker Verification. In Proc. Interspeech 2020 (3800-3804).  
- Zhang, R., Wei, J., Lu, W., Wang, L., **Liu, M.**, Zhang, L., & Xu, J. (2020). ARET: Aggregated Residual Extended Time-delay Neural Networks for Speaker Verification. In Proc. Interspeech 2020 (946-950).  
- Zhou, D., Wang, L., Lee, K. A., **Liu, M.**, & Dang, J. (2020, November). Deep Discriminative Embedding with Ranked Weight for Speaker Verification. In International Conference on Neural Information Processing (ICONIP) (pp. 79-86).   
- Li, D., Wang, L., Dang, J., **Liu, M.**, Oo, Z., Nakagawa, S., & Li, X. (2018). Multiple Phase Information Combination for Replay Attacks Detection. In Proc. Interspeech 2018 (pp. 656-660).

# 🎖 Honors and Awards
- SPS Travel Grants Scholarship (2023)
- Chinese Government-sponsored Scholarship (2021-2022)
- The 4th and 5th places in Audio Deep Synthesis Detection (track1 and track 2) (2021).
- The 2nd place in the SRE CTS Challenge, member of the I4U team (2021).
- The 4th place in VoxCeleb Speaker Recognition Competition (fixed channel) (2019).
- The second place in National Future Cup College AI speech challenge (2019).
- National scholarship (2016), Outstanding graduates (2017).
- National second prize in National University Mathematical Modeling Competition (2015).
- National special prize in National English Competition for College Students (2015).
- Provincial first prize in LanQiao Cup Programming Competition (2014).

# 💻 Academic Activities
- Assistant researcher at A*STAR, conducted in-depth research on multimodal technology (Singapore)
- Reviewer for international conferences: ICASSP (2021, 2022, 2023), Interspeech (2021, 2022), APSIPA (2021), ISCSLP(2022)
- Volunteer for international conferences: ISSP (Tianjin, 2017), ICASSP (Singapore, 2022)
- Presented at international conferences in Tianjin (2017), Taipei (2018), the UK (2019), and Singapore (2022)
- Organized research team members to participate in international competitions and workshops: ASVSpoof (2019,2021), VoxCeleb (2019,2022), ADD (2021), SDSVC(2020), SRE CTS (2021), SASV(2022) Challenges.
- Participated in other speech community activities such as the KALDI seminar in Beijing (2018), the national speech recognition seminar at Duke University in Kunshan (2019), the NCMMSC conference in Xining (2019), and the multilingual speaker recognition seminar at Tsinghua University (2020).

# 👔 Projects
- *2019.06 - 2022.05*, National Key Research and Development Program (No. 2018YFB1305201), Multi-mode fusion of natural robot interaction
- *2022.01 - 2025.12*, National Natural Science Foundation of China (No. 62176182), Speaker recognition and speaker recognition anti-spoofing under complex scenes
- *2018.01 - 2021.12*, National Natural Science Foundation of China (No. 61771333), Multi-accent speech recognition under a reverberant environment
- *2018.10 - 2021.09*, Tianjin Municipal Science and Technology Project (No. 18ZXZNGX00330), Key technologies and system implementation of spoken dialogue in complex environments for robots
- *2021.08 - 2023.07*, Projects sponsored by Ministries and Provinces (No. 2021120005001743), Research on voiceprint recognition and speech recognition system
  
# 📜 Book Chapter & Patent
1. Chapter 5: Speaker and Language Recognition, Advances in Speech Information Processing.
2. Chapter 6: Speaker Recognition Principles and Technology, Speech Information Processing and Practice.
3. Patent: A Method for Detecting Recording Fraud based on Feature Extraction of Amplitude and Phase using Adaptive Filters (ZL 2019 1 0087795.7)
