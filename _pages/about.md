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

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat. -->

Hello🤗, I am a 2nd-year Direct PhD student in Research Center for Social Computing and Interactive Robotics (SCIR), at Harbin Institute of Technology (HIT, China), supervised by Professor [Wanxiang Che](https://chewanxiang.com/en/).
My main research interests are efficient inference in large language models and optimization of long context. 
Recently, my research interests have shifted primarily to agent memory. 
If you are interested in my research or potential collaborations, please feel free to contact me at ✉️[yijunliu@ir.hit.edu.cn](mailto:yijunliu@ir.hit.edu.cn).

If you like the template of this homepage, welcome to star and fork Yi Ren’s open-sourced template version [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io).



# 🔥 News
- *2025.11*: &nbsp;🎉🎉 Our [Judge Q](https://ojs.aaai.org/index.php/AAAI/article/view/40497) and [CAMERA](https://ojs.aaai.org/index.php/AAAI/article/view/39957) are accepted by AAAI 2026. 
- *2025.08*: &nbsp;🎉🎉 Our [LookAhead Q-Cache](https://aclanthology.org/2025.emnlp-main.1732/) is accepted by EMNLP 2025(main).
- *2025.03*: &nbsp;🎉🎉 Our [Long Context Survey](https://arxiv.org/abs/2503.13299) has been released.
- *2024.09*: &nbsp;🎉🎉 Our [Make-Some-Noise](https://aclanthology.org/2024.emnlp-main.718/) is accepted by EMNLP 2024(main).
- *2024.05*: &nbsp;🎉🎉 Our [LM-Combiner](https://aclanthology.org/2024.lrec-main.934/) is accepted by LREC-COLING 2024.



# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/judgeq-framework.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Judge Q: Trainable Queries for Optimized Information Retention in KV Cache Eviction](https://ojs.aaai.org/index.php/AAAI/article/view/40497)

**Yijun Liu**, Yixuan Wang, Yuzhuang Xu, Shiyu Ji, Yang Xu, Qingfu Zhu, Wanxiang Che

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/survey_framework.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey on Transformer Context Extension: Approaches and Evaluation](https://arxiv.org/abs/2503.13299)

**Yijun Liu**, Jinzheng Yu, Yang Xu, Zhongyang Li, Qingfu Zhu
</div>
</div>

## 🧑🏻‍💻 Collaborative Papers

### 🚄 Efficient LLMs
[Lookahead Q-Cache: Achieving More Consistent KV Cache Eviction via Pseudo Query](https://aclanthology.org/2025.emnlp-main.1732/), Yixuan Wang\*, Shiyu Ji\*, **Yijun Liu**, Yuzhuang Xu, Yang Xu, Qingfu Zhu, Wanxiang Che. **[EMNLP 2025]** [[Code]](https://github.com/noforit/Lookahead_Q-Cache)

[Make Some Noise: Unlocking Language Model Parallel Inference Capability through Noisy Training](https://aclanthology.org/2024.emnlp-main.718/), Yixuan Wang, Xianzhen Luo, Fuxuan Wei, **Yijun Liu**, Qingfu Zhu, Xuanyu Zhang, Qing Yang, Dongliang Xu, Wanxiang Che. **[EMNLP 2024]** 

[Think Before You Accept: Semantic Reflective Verification for Faster Speculative Decoding](https://arxiv.org/abs/2505.18629), Yixuan Wang, **Yijun Liu**, Shiyu ji, Yuzhuang Xu, Yang Xu, Qingfu Zhu, Wanxiang Che. 


### 🌎 Multimodal Understanding
[CVLUE: A New Benchmark Dataset for Chinese Vision-Language Understanding Evaluation](https://ojs.aaai.org/index.php/AAAI/article/view/32884), Yuxuan Wang, **Yijun Liu**, Fei Yu, Chen Huang, Kexin Li, Zhiguo Wan, Wanxiang Che, Hongyang Chen. **[AAAI 2025]** [[Code]](https://github.com/WangYuxuan93/CVLUE)

### ✍🏻 Grammatical Error Correction(GEC)

[Improving Grammatical Error Correction via Contextual Data Augmentation](https://aclanthology.org/2024.findings-acl.647/), Yixuan Wang, Baoxin Wang, **Yijun Liu**, Qingfu Zhu, Dayong Wu, Wanxiang Che. **[ACL 2024 findings]** 

[LM-Combiner: A Contextual Rewriting Model for Chinese Grammatical Error Correction](https://aclanthology.org/2024.lrec-main.934/), Yixuan Wang, Baoxin Wang, **Yijun Liu**, Dayong Wu, Wanxiang Che. **[LREC-COLING 2024]**



# 🎖 Honors and Awards
- *2022.11* **National First Prize** in China Undergraduate Mathematical Contest in Modelling (CUMCM). 
- *2022.05* **Meritorious Winner** in Mathematical Contest in Modeling (MCM).
- *2021.12* **Provincial Second Prize** in Mathematics competition of Chinese (CMC).
- *2023.08* **First place** in Chinese Essay Fluency Evaluation in the CCL 2023 evaluation competition.
- *2024.08* **Task Contact** of Chinese Vision-Language Understanding Evaluation(CVLUE) in the CCL 2024 evaluation competition.
- *2024.06* **Outstanding Graduates Awards of Heilongjiang Province**.
- *2023.12* **Merit Student of Heilongjiang Province**.
- *2021.05* **Excellent Student Cadre of Harbin Institute of Technology**.
- *2022.05* **Excellent League Member of Harbin Institute of Technology**.
- *2023.05* **Excellent League Cadre of Harbin Institute of Technology**.
- *2026.05* **Excellent League Member of Harbin Institute of Technology**.
- *2021, 2022, 2023* **First-class People's Scholarship**.



# 📖 Educations
- *2024.09 - Now*, Direct Phd Student, Harbin Institute of Technology, Harbin. 
- *2020.09 - 2024.06*, Undergraduate, Harbin Institute of Technology, Harbin. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2025.01 - 2025.03*, HUAWEI, Business Group, Dongguan