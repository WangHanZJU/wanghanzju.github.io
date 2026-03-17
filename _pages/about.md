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

<div id="typewriter-slogan">
<blockquote><p>Building multimodal generative audio systems for more immersive listening experiences.</p></blockquote>
</div>

**Focus:** `Multi-Modal Generative AI` · `Speech Synthesis` · `Spatial Audio`

I am an undergraduate student at **[Turing Class](http://www.cs.zju.edu.cn/turingclass_en/)**, **[Chu Kochen Honors College](http://ckc.zju.edu.cn/ckcen/)**, **[Zhejiang University](https://www.zju.edu.cn/english/)**, majoring in Artificial Intelligence. I currently work in the **Audio Research Team** at Zhejiang University, under the supervision of **[Prof. Zhou Zhao](https://person.zju.edu.cn/en/zhaozhou)**.

My research interest lies in **Multi-Modal Generative AI**, with a particular focus on **Speech Synthesis** and **Spatial Audio Generation**. My work aims to build immersive auditory experiences through advanced generative modeling (e.g., Flow Matching). I have papers published or under review at top-tier venues including **NeurIPS**, **ACM MM**, and **ACL**.

I am always open to potential collaborations and opportunities. Feel free to reach out.

# 🔥 News
<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2026.01</div>
    <div class="timeline-content">🎉 Started my internship at <a href="https://vuilabs.cn/">Luna Lab（宇生月伴）</a> as a text-to-speech model researcher.</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2025.12</div>
    <div class="timeline-content">🎉 Submitted two papers to <strong><a href="https://2026.aclweb.org/">ACL 2026</a></strong>.</div>
  </div>
</div>

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 (Under Review)</div><img src='images/vocoder.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CSAVocoder: A Causal Spatial Audio Vocoder Towards Real-Time Spatial Audio Generation](images/article_csavocoder.pdf)

#Zhiyuan Zhu, **#Han Wang**, et al.

- We introduce **CSAVocoder**, a strictly causal streaming neural vocoder. It features a Spatial Adaptor to fuse pose information and a Spatial Consistency Discriminator to explicitly supervise inter-channel phase and level differences.
- The model achieves high-fidelity waveform reconstruction while preserving precise spatial rendering, all within a constant memory overhead suitable for real-time streaming.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 (Under Review)</div><img src='images/aoe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Comprehensive Benchmarking of Long-Form Speech Generation in Diverse Scenarios](images/article_aoe.pdf)

#Changhao Pan, #Rui Yang, **#Han Wang**, et al.

- We propose **LFS-Bench**, a standardized benchmark decomposing "long-form quality" into acoustics, semantics, and expressiveness. It includes 1,101 samples spanning 17 diverse scenarios (e.g., dialogues, audiobooks).
- Our extensive experiments reveal that current SOTA models still struggle significantly with consistency and hierarchy in highly expressive scenarios compared to real recordings.
</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">
[A Multimodal Evaluation Framework for Spatial Audio Playback Systems: From Localization to Listener Preference]

Changhao Pan, Wenxiang Guo, Yu Zhang, Zhiyuan Zhu, Zhetao Chen, **Han Wang**, Zhou Zhao **ACM MM 2025**
</div></div>

<div class='paper-box'><div class='paper-box-text' markdown="1">
[MRSAudio: A Large-Scale Multimodal Recorded Spatial Audio Dataset with Refined Annotations]

Wenxiang Guo, Changhao Pan, Zhiyuan Zhu, Xintong Hu, Yu Zhang, Li Tang, Rui Yang, **Han Wang**, et al. **NeurIPS 2025**
</div></div>

# 🎖 Honors and Awards
- *2024* First-class Scholarship in Zhejiang University
- *2025* Second-class Scholarship in Zhejiang University
- *2025* National Student Research Training Program

# 📖 Education
- *2023.08 - Present* Undergraduate, Chu Kochen Honors College, Zhejiang University

# 💻 Internships
- *2024.04 – 2025.12* Research Assistant, Audio Research Team, Zhejiang University.<br>Under the supervision of **[Prof. Zhou Zhao](https://scholar.google.com/citations?user=IIoFY90AAAAJ&hl=zh-CN&oi=ao)**.
- *2026.01 – Present* MLE Intern (TTS), VUI Lab, Hangzhou.<br>Mentored by **[Mengxiao Bi](https://scholar.google.com/citations?hl=en&user=BIU0dm4AAAAJ)**; under the supervision of **[Prof. Yanmin Qian](https://scholar.google.com/citations?hl=en&user=guG9lxgAAAAJ)**.
