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

I am an undergraduate student at **[Turing Class](http://www.cs.zju.edu.cn/turingclass_en/)**, **[Chu Kochen Honors College](http://ckc.zju.edu.cn/ckcen/)**, **[Zhejiang University](https://www.zju.edu.cn/english/)**, majoring in Artificial Intelligence. Currently, I work in the **Audio Research Team** at Zhejiang University, under the supervision of **[Prof. Zhou Zhao](https://person.zju.edu.cn/en/zhaozhou)**.

My research interest lies on **Multi-Modal Generative AI**, with a particular focus on **Speech Synthesis** and **Spatial Audio Generation**. My work aims to build immersive auditory experiences through advanced generative modeling (e.g., Flow Matching). Currently, I have several papers published or under review at top-tier venues including **NeurIPS,** **ACM MM**, and **ACL**.

I am always open to potential collaborations and seeking opportunities to push the boundaries of AI. Contact me for any exciting projects or discussions!

# 🔥 News
- *2026.1* &nbsp;🎉🎉 Started my internship at Luna Lab（宇生月伴）as a text-to-speech model researcher!
- *2025.12*: &nbsp;🎉🎉 Submitted two papers to **[ACL 2026](https://2026.aclweb.org/)**


# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026(Under Review)</div><img src='images/vocoder.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CSAVocoder: A Causal Spatial Audio Vocoder Towards Real-Time Spatial Audio Generation](images/article_csavocoder.pdf)

#Zhiyuan Zhu, **#Han Wang**, et al.

- We introduce **CSAVocoder**, a strictly causal streaming neural vocoder. It features a Spatial Adaptor to fuse pose information and a Spatial Consistency Discriminator to explicitly supervise inter-channel phase and level differences.
- The model achieves high-fidelity waveform reconstruction while preserving precise spatial rendering, all within a constant memory overhead suitable for real-time streaming.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026(Under Review)</div><img src='images/aoe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Comprehensive Benchmarking of Long-Form Speech Generation in Diverse Scenarios](images/article_aoe.pdf)

#Changhao Pan, #Rui Yang, **#Han Wang**, et al.

- We propose **LFS-Bench**, a standardized benchmark decomposing "long-form quality" into acoustics, semantics, and expressiveness. It includes 1,101 samples spanning 17 diverse scenarios (e.g., dialogues, audiobooks).
- Our extensive experiments reveal that current SOTA models still struggle significantly with consistency and hierarchy in highly expressive scenarios compared to real recordings.
</div>
</div>

- [A Multimodal Evaluation Framework for Spatial Audio Playback Systems: From Localization to Listener Preference] Changhao Pan, Wenxiang Guo, Yu Zhang, Zhiyuan Zhu, Zhetao Chen, **Han Wang**, Zhou Zhao **ACM MM 2025**
- [MRSAudio: A Large-Scale Multimodal Recorded Spatial Audio Dataset with Refined Annotations] Wenxiang Guo, Changhao Pan, Zhiyuan Zhu, Xintong Hu, Yu Zhang, Li Tang, Rui Yang, **Han Wang**, et al. **NeurIPS 2025**

# 🎖 Honors and Awards
- *2024* First-class Scholarship in Zhejiang University
- *2025* Second-class Scholarship in Zhejiang University
- *2025* National Student Research Training Program

# 📖 Educations
- *2023.8 - now* Undergraduate, Chu Kochen Honors College, Zhejiang Univeristy


# 💻 Internships
- *2024.4 - 2025.12* Research Assisant in Audio Research Team at Zhejiang University . **Advisor: Prof. Zhou Zhao [赵洲](https://person.zju.edu.cn/en/zhaozhou)**.
- *2026.1 - now* MLE Intern Algorithm Luna Lab, Hangzhou(https://vuilabs.cn/)