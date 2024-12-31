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

# 😎 About Me

I am Chengyou Jia (贾成铕), a Ph.D candidate in Xi’an Jiaotong University, major in Computer Science, under the supervision of [Prof. Minnan Luo](https://scholar.google.com/citations?user=C3ujEF0AAAAJ&hl). I am also working closely with [Prof. Xiaojun Chang](https://scholar.google.com/citations?user=8suupocAAAAJ&hl). I am currently a visiting student in Singapore under the supervision of [Pro. Ivor](https://www.a-star.edu.sg/cfar/about-cfar/management/prof-ivor-tsang). Previously, I was a research intern at Shanghai AI LAB, supervised by [Dr. Zhiyong Wu](https://lividwo.github.io/zywu.github.io/). Before starting my doctoral studies, I received my B.E. degree from Xi’an Jiaotong University in 2021.


I have authored several publications in top-tier conferences and journals, including AAAI, ACM-MM, IEEE TIP, IEEE TCSVT, among others. I also serve as a reviewer for esteemed conferences and journals like ECCV, AAAI, ICASSP, IEEE TIP and IEEE TNNLS.

## Research Interests

I am working in the field of CV 
&amp; Multi-modal. My current research interests and past experience can be summarized as follows:

- Controllable Image Generation: Text-to-image; Layout-to-image; Complex Scene Generation
- Multimodal learning: Multimodal for Open-set Recognition;
Multimodal for Automated Agents
- Object Detection 
&amp; Identification: Person Search, Person Re-Identification

<span class='anchor' id='-news'></span>

# 🔥 News
- *2024.12*: &nbsp; Our paper [OS-Genesis] is recently released 🚀🚀!
- *2024.12*: &nbsp; One paper is accepted by IEEE TCSVT. 🎉🎉 
- *2024.11*: &nbsp; Our papers [ChatGen, OS-Atlas, AgentStore] are recently released. 🎉🎉 
- *2024.10*: &nbsp; Ended a fulfilling internship at Shanghai AI Lab and started as a visiting student in Singapore.
- *2024.07*: &nbsp; One paper is accepted by ACM-MM 2024. See you in Melbourne, Australia. 🎉🎉 
- *2023.11*: &nbsp; Two papers are accepted by AAAI 2024. 🎉🎉 
- *2023.09*: &nbsp; One paper is accepted by IEEE TIP. 🎉🎉 


<span class='anchor' id='-educations'></span>

# 📖 Educations
- *2021.09 - 2026.06 (expected)*, M.S. + Ph.D Student, Computer Science, Xi'an Jiaotong University. &emsp;
- *2017.09 - 2021.06*, B.S. in Computer Science, Xi'an Jiaotong University. 

<span class='anchor' id='-internships'></span>

# 💻 Internships
- *2024.11 - Present*, Research Intern @ CFAR, A*STAR. Focus on Multimodal Agents for Image Generation.
- *2024.03 - 2024.10*, Research Intern @ Shanghai AI LAB. Focus on Multimodal Agents for OS (Operating System).
- *2022.12 - 2024.03*, Research Intern @ SGIT AI Lab, State Grid Corporation of China. Focus on Controllable Image Generation.


<span class='anchor' id='-publications'></span>

# 📝 Selected Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/ChatGen.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[ChatGen: Automatic Text-to-Image Generation From FreeStyle Chatting 🔥🔥](https://arxiv.org/abs/2411.17176) <span style="color:red">[Preprint]</span> \\
**Chengyou Jia\***, Changliang Xia\*, Zhuohang Dang, Weijia Wu, Hangwei Qian, Minnan Luo

(\* means equal contributions)

[**Code**](https://github.com/chengyou-jia/ChatGen) &nbsp;
[**Project Page**](https://chengyou-jia.github.io/ChatGen-Home/) &nbsp;
[**Datasets**](https://huggingface.co/datasets/ChengyouJia/ChatGenBench) &nbsp;
[**Models**](https://huggingface.co/collections/ChengyouJia/chatgen-6744724ae834402b5b69037b) &nbsp;
[![](https://img.shields.io/github/stars/chengyou-jia/ChatGen?style=social&label=Code+Stars)](https://github.com/chengyou-jia/ChatGen)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/OSAtlas.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[OS-ATLAS: A Foundation Action Model for Generalist GUI Agents 🔥🔥](https://arxiv.org/abs/2410.23218) <span style="color:red">[Preprint]</span> \\
Zhiyong Wu, Zhenyu Wu, Fangzhi Xu, Yian Wang, Qiushi Sun, **Chengyou Jia**, Kanzhi Cheng, Zichen Ding, Liheng Chen, Paul Pu Liang, Yu Qiao

[**Code**](https://github.com/OS-Copilot/OS-Atlas) &nbsp;
[**Project Page**](https://osatlas.github.io) &nbsp;
[**Demo**](https://huggingface.co/spaces/maxiw/OS-ATLAS) &nbsp;
[![](https://img.shields.io/github/stars/OS-Copilot/OS-Atlas?style=social&label=Code+Stars)](https://github.com/OS-Copilot/OS-Atlas)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/AgentStore.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[AgentStore: Scalable Integration of Heterogeneous Agents As Specialized Generalist Computer Assistant 🔥🔥](https://arxiv.org/abs/2410.18603) <span style="color:red">[Preprint]</span> \\
**Chengyou Jia**, Minnan Luo, Zhuohang Dang, Qiushi Sun, Fangzhi Xu, Junlin Hu, Tianbao Xie, Zhiyong Wu

[**Code**](https://github.com/chengyou-jia/AgentStore) &nbsp;
[**Project Page**](https://chengyou-jia.github.io/AgentStore-Home/) &nbsp;
[![](https://img.shields.io/github/stars/chengyou-jia/AgentStore?style=social&label=Code+Stars)](https://github.com/chengyou-jia/AgentStore)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM-MM 2024</div><img src='images/apclip.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Generating Action-conditioned Prompts for Open-vocabulary Video Action Recognition](https://arxiv.org/abs/2312.02226) <span style="color:red">[CCF-A]</span>

**Chengyou Jia**, Minnan Luo, Xiaojun Chang, Zhuohang Dang, Mingfei Han, Mengmeng Wang, Guang Dai, Sizhe Dang, Jingdong Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/ssmg.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[SSMG: Spatial-semantic map guided diffusion model for free-form layout-to-image generation](https://ojs.aaai.org/index.php/AAAI/article/view/28024) <span style="color:red">[CCF-A]</span>

**Chengyou Jia**, Minnan Luo, Zhuohang Dang, Guang Dai, Xiaojun Chang, Mengmeng Wang, Jingdong Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIP</div><img src='images/ccr.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Collaborative Contrastive Refining for Weakly Supervised Person Search](https://ieeexplore.ieee.org/abstract/document/10234225) <span style="color:red">[CCF-A]</span>

**Chengyou Jia**, Minnan Luo, Caixia Yan, Linchao Zhu, Xiaojun Chang, Qinghua Zheng

</div>
</div>

#### 🧑‍ Other Paper


Preprint 
Qiushi Sun, Kanzhi Cheng, Zichen Ding, Chuanyang Jin, Yian Wang, Fangzhi Xu, Zhenyu Wu, Chengyou Jia, Liheng Chen, Zhoumianze Liu, Ben Kao, Guohao Li, Junxian He, Yu Qiao, Zhiyong Wu

- ``Preprint`` [OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis](https://arxiv.org/abs/2412.19723) <span style="color:red"></span> <br>
Qiushi Sun, Kanzhi Cheng, Zichen Ding, Chuanyang Jin, Yian Wang, Fangzhi Xu, Zhenyu Wu, **Chengyou Jia**, Liheng Chen, Zhoumianze Liu, Ben Kao, Guohao Li, Junxian He, Yu Qiao, Zhiyong Wu

- ``IEEE TCSVT`` [PSDiff: Diffusion Model for Person Search with Iterative and Collaborative Refinement](https://arxiv.org/abs/2309.11125) <span style="color:red">[CCF-B]</span> <br>
  **Chengyou Jia**, Minnan Luo, Zhuohang Dang, Guang Dai, Xiaojun Chang, Jingdong Wang, Qinghua Zheng

- ``ICASSP 2023`` [Towards Real-time Person Search with Invariant Feature Learning](https://ieeexplore.ieee.org/abstract/document/10095679/) <span style="color:red">[CCF-B]</span> <br>
  **Chengyou Jia**, Minnan Luo, Zhuohang Dang, Xiaojun Chang, Qinghua Zheng


- ``AAAI 2024`` [Noisy Correspondence Learning with Self-Reinforcing Errors Mitigation](https://ojs.aaai.org/index.php/AAAI/article/view/27911) <span style="color:red">[CCF-A]</span> <br>
  Zhuohang Dang, Minnan Luo, **Chengyou Jia**, Guang Dai, Xiaojun Chang, Jingdong Wang

- ``IEEE TCSVT`` [Disentangled representation learning with transmitted information bottleneck](https://ieeexplore.ieee.org/abstract/document/10637999) <span style="color:red">[CCF-B]</span> <br>
  Zhuohang Dang, Minnan Luo, **Chengyou Jia**, Guang Dai, Jihong Wang, Xiaojun Chang, Jingdong Wang

- ``IEEE TIP`` [Disentangled Generation with Information Bottleneck for Enhanced Few-Shot Learning](https://ieeexplore.ieee.org/abstract/document/10542660) <span style="color:red">[CCF-A]</span> <br>
  Zhuohang Dang, Minnan Luo, Jihong Wang, **Chengyou Jia**, Caixia Yan, Guang Dai, Xiaojun Chang, Qinghua Zheng

- ``IEEE TCSVT`` [Counterfactual Generation Framework for Few-Shot Learning](https://ieeexplore.ieee.org/abstract/document/10035001/) <span style="color:red">[CCF-B]</span> <br>
  Zhuohang Dang, Minnan Luo, **Chengyou Jia**, Caixia Yan, Xiaojun Chang, Qinghua Zheng

- ``Preprint`` [Disentangled Noisy Correspondence Learning](https://arxiv.org/abs/2408.05503) <span style="color:red"></span> <br>
  Zhuohang Dang, Minnan Luo, Jihong Wang, **Chengyou Jia**, Haochen Han, Herun Wan, Guang Dai, Xiaojun Chang, Jingdong Wang

<span class='anchor' id='-honors-and-awards'></span>

# 🎖 Honors and Awards
**Honors**
- *Oct.2022* &emsp; Outstanding Graduate Student of Xi’an Jiaotong University, Award.
- *Jun.2021* &emsp; Excellent bachelor degree thesis award (Top 1%), Award.
- *Jun.2021* &emsp; Outstanding Graduate Student of Xi’an Jiaotong University, Award.
- *Sep.2019* &emsp; Outstanding Student in Xi’an Jiaotong University
- *Sep.2018* &emsp; Outstanding Student in Xi’an Jiaotong University

**Competition Awards**
- *Jun.2021* &emsp; **Top 1%** in the TianChi Global Video Cloud Innovation Challenge, Video Object Segmentation Algorithm Challenge (**8/2904**).


<span class='anchor' id='-scholarships'></span>
# 🎖 Scholarships
- *2023.09* &emsp; Freshman First Prize Scholarship (PhD)
- *2022.09* &emsp; First-Class Fellowships for Graduate Students at Xi’an Jiaotong University, Fellowships.
- *2020.09* &emsp; Computer Science Special Scholarship at Xi’an Jiaotong University, Fellowships.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<span class='anchor' id='-academic-services'></span>
# 💬 Academic Services
- Reviewer: ECCV, AAAI, ICASSP, IEEE TIP, IEEE TCSVT and IEEE TNNLS.