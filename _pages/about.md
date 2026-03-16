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

I am Chengyou Jia (贾成铕), a final-year Ph.D. student in Computer Science at Xi’an Jiaotong University. I am going to be a researcher in the **Hunyuan team** of Tencent (Qingyun Project). My Ph.D. advisor is [Prof. Minnan Luo](https://scholar.google.com/citations?user=C3ujEF0AAAAJ&hl), and I am also working closely with [Prof. Xiaojun Chang](https://scholar.google.com/citations?user=8suupocAAAAJ&hl).  Previously, I was a visiting student in Singapore under the supervision of [Prof. Ivor](https://www.a-star.edu.sg/cfar/about-cfar/management/prof-ivor-tsang), and a research intern at Shanghai AI LAB, supervised by [Dr. Zhiyong Wu](https://lividwo.github.io/zywu.github.io/). I received my B.E. degree from Xi’an Jiaotong University in 2021.


I have authored several publications in top-tier conferences and journals, including CVPR, AAAI, ACL, IEEE TIP, among others. I also serve as a reviewer for esteemed conferences and journals like NIPS, ICML, CVPR, ECCV.

## Research Interests

I am working in the field of CV 
&amp; Multi-modal. My current research interests and past experience can be summarized as follows:

- Controllable Image Generation: Text-to-image; Layout-to-image; Consistent Generation
- Multimodal Agent: GUIAgent, Agentic Vision Generation
- Object Detection 
&amp; Identification: Person Search, Person Re-Identification
UIA
<span class='anchor' id='-news'></span>

# 🔥 News

- *2026.02*: &nbsp; Our paper PaCo-RL is accepted by CVPR 2026. 🎉🎉 
- *2025.12*: &nbsp; Our paper PaCo-RL is recently released. 🎉🎉 
- *2025.11*: &nbsp; One paper is accepted by AAAI 2026. 🎉🎉 
- *2025.10*: &nbsp; CoFFT is accepted by NeurIPS 2025. 🎉🎉 
- *2025.06*: &nbsp; Our papers [T2IS, DenseDiT, AutoGPS] are recently released. 🎉🎉 
- *2025.05*: &nbsp; Three papers are accepeted by ACL 2025. 🎉🎉 
- *2025.02*: &nbsp; ChatGen is accepeted by CVPR 2025. 🎉🎉 
- *2025.01*: &nbsp; OS-Atlas is accepeted by ICLR 2025 (Spotlight). 🎉🎉 
- *2024.12*: &nbsp; One paper is accepted by IEEE TCSVT. 🎉🎉 
- *2024.11*: &nbsp; Our papers [ChatGen, OS-Atlas, AgentStore, OS-Genesis] are recently released. 🎉🎉 
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
- *2026.03 - Present*, Researcher @ Tencent Hunyuan Team.
- *2024.11 - 2025.11*, Research Intern @ CFAR, A*STAR. Focus on Multimodal Agents for Image Generation.
- *2024.03 - 2024.10*, Research Intern @ Shanghai AI LAB. Focus on Multimodal Agents for OS (Operating System).
- *2022.12 - 2024.03*, Research Intern @ SGIT AI Lab, State Grid Corporation of China. Focus on Controllable Image Generation.


<span class='anchor' id='-publications'></span>

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/paco.png' alt="PaCo-RL" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[PaCo-RL: Advancing Reinforcement Learning for Consistent Image Generation with Pairwise Reward Modeling](https://arxiv.org/abs/2512.04784) <span style="color:red">[CCF-A]</span>  
Bowen Ping\*, **Chengyou Jia\***, Minnan Luo, Changliang Xia, Xin Shen, Zhuohang Dang, Hangwei Qian

(\* means equal contributions)

[**Project Page**](https://x-gengroup.github.io/HomePage_PaCo-RL/) &nbsp; 
[**Datasets**](https://huggingface.co/collections/X-GenGroup/paco-rl) &nbsp;
[**Code**](https://github.com/X-GenGroup/PaCo-RL) &nbsp;
[![](https://img.shields.io/badge/hf_downloads-%3E100-steelblue.svg)](https://huggingface.co/collections/X-GenGroup/paco-rl) &nbsp;
[![](https://img.shields.io/github/stars/X-GenGroup/PaCo-RL?style=social&label=Code+Stars)](https://github.com/X-GenGroup/PaCo-RL)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 Workshop</div><img src='images/flowfactory.png' alt="Flow-Factory" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Flow-Factory: A Unified Framework for Reinforcement Learning in Flow-Matching Models](https://arxiv.org/abs/2602.12529) <span style="color:red">[Workshop]</span> \\
Bowen Ping, **Chengyou Jia**, Minnan Luo, Hangwei Qian, Ivor Tsang

[**Code**](https://github.com/X-GenGroup/Flow-Factory) &nbsp;
[![](https://img.shields.io/github/stars/X-GenGroup/Flow-Factory?style=social&label=Code+Stars)](https://github.com/X-GenGroup/Flow-Factory)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/t2is.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[Why Settle for One? Text-to-ImageSet Generation and Evaluation 🔥](https://arxiv.org/abs/2506.23275) <span style="color:red">[Preprint]</span> \\
**Chengyou Jia**, Xin Shen, Zhuohang Dang, Changliang Xia, Weijia Wu, Xinyu Zhang, Huangwei Qian, Ivor Tsang, Minnan Luo


[**Project Page**](https://chengyou-jia.github.io/T2IS-Home/) &nbsp; 
[**Datasets**](https://huggingface.co/datasets/ChengyouJia/T2IS-Bench) &nbsp;
[**Code**](https://github.com/chengyou-jia/T2IS) &nbsp;
[![](https://img.shields.io/badge/hf_downloads-%3E100-steelblue.svg)](https://huggingface.co/datasets/ChengyouJia/T2IS-Bench) &nbsp;
[![](https://img.shields.io/github/stars/chengyou-jia/T2IS?style=social&label=Code+Stars)](https://github.com/chengyou-jia/T2IS)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/densedit.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[From Ideal to Real: Unified and Data-Efficient Dense Prediction for Real-World Scenarios 🔥](https://arxiv.org/abs/2506.20279) <span style="color:red">[Preprint]</span> \\
Changliang Xia\*, **Chengyou Jia\***, Zhuohang Dang, Minnan Luo

(\* means equal contributions)

[**Code**](https://github.com/xcltql666/DenseDiT) &nbsp;
[**Project Page**](https://xcltql666.github.io/DenseDiTProj/) &nbsp;
[**Models**](https://huggingface.co/xcll/DenseDiT_Model) &nbsp;
[**Datasets**](https://huggingface.co/datasets/xcll/DenseWorld_Benchmark) &nbsp;
[![](https://img.shields.io/github/stars/xcltql666/DenseDiT?style=social&label=Code+Stars)](https://github.com/xcltql666/DenseDiT)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/ChatGen.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[ChatGen: Automatic Text-to-Image Generation From FreeStyle Chatting 🔥🔥](https://arxiv.org/abs/2411.17176) <span style="color:red">[CCF-A]</span> \\
**Chengyou Jia\***, Changliang Xia\*, Zhuohang Dang, Weijia Wu, Hangwei Qian, Minnan Luo

(\* means equal contributions)

[**Code**](https://github.com/chengyou-jia/ChatGen) &nbsp;
[**Project Page**](https://chengyou-jia.github.io/ChatGen-Home/) &nbsp;
[**Datasets**](https://huggingface.co/datasets/ChengyouJia/ChatGenBench) &nbsp;
[**Models**](https://huggingface.co/collections/ChengyouJia/chatgen-6744724ae834402b5b69037b) &nbsp;
[![](https://img.shields.io/badge/hf_downloads-%3E200-steelblue.svg)](https://huggingface.co/datasets/ChengyouJia/ChatGenBench) &nbsp;
[![](https://img.shields.io/github/stars/chengyou-jia/ChatGen?style=social&label=Code+Stars)](https://github.com/chengyou-jia/ChatGen)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 Findings</div><img src='images/AgentStore.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[AgentStore: Scalable Integration of Heterogeneous Agents As Specialized Generalist Computer Assistant 🔥🔥](https://arxiv.org/abs/2410.18603) <span style="color:red"></span> \\
**Chengyou Jia**, Minnan Luo, Zhuohang Dang, Qiushi Sun, Fangzhi Xu, Junlin Hu, Tianbao Xie, Zhiyong Wu

[**Code**](https://github.com/chengyou-jia/AgentStore) &nbsp;
[**Project Page**](https://chengyou-jia.github.io/AgentStore-Home/) &nbsp;
[![](https://img.shields.io/github/stars/chengyou-jia/AgentStore?style=social&label=Code+Stars)](https://github.com/chengyou-jia/AgentStore)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/OSAtlas.png' alt="sym" width="98%"></div></div>
<div class='paper-box-text' markdown="1">

[OS-ATLAS: A Foundation Action Model for Generalist GUI Agents 🔥🔥](https://arxiv.org/abs/2410.23218) <span style="color:red">[CAAI-A]</span> \\
Zhiyong Wu, Zhenyu Wu, Fangzhi Xu, Yian Wang, Qiushi Sun, **Chengyou Jia**, Kanzhi Cheng, Zichen Ding, Liheng Chen, Paul Pu Liang, Yu Qiao

[**Code**](https://github.com/OS-Copilot/OS-Atlas) &nbsp;
[**Project Page**](https://osatlas.github.io) &nbsp;
[**Demo**](https://huggingface.co/spaces/maxiw/OS-ATLAS) &nbsp;
[![](https://img.shields.io/github/stars/OS-Copilot/OS-Atlas?style=social&label=Code+Stars)](https://github.com/OS-Copilot/OS-Atlas)

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



- ``Preprint`` [Autogps: Automated geometry problem solving via multimodal formalization and deductive reasoning](https://arxiv.org/abs/2505.23381) <br>
Bowen Ping, Minnan Luo, Zhuohang Dang, Chenxi Wang, **Chengyou Jia**

- ``Preprint`` [Multi-Modal Dataset Distillation in the Wild](https://arxiv.org/abs/2506.01586) <br>
Zhuohang Dang, Minnan Luo, **Chengyou Jia**, Hangwei Qian, Xiaojun Chang, Ivor W Tsang


- ``AAAI 2026`` [Correspondence Coverage Matters for Multi-Modal Dataset Distillation](#) <span style="color:red">[CCF-A]</span> <br>
  Zhuohang Dang, Minnan Luo, **Chengyou Jia**, Hangwei Qian, Xinyu Zhang, Xiaojun Chang, Ivor Tsang



- ``NeurIPS 2025`` [CoFFT: Chain of Foresight-Focus Thought for Visual Language Models](https://arxiv.org/abs/2509.22010) <span style="color:red">[CCF-A]</span> <br>
Xinyu Zhang, Yuxuan Dong, Lingling Zhang, **Chengyou Jia**, Zhuohang Dang, Basura Fernando, Jun Liu, Mike Zheng Shou


- ``ACL 2025`` [PhysReason: A Comprehensive Benchmark towards Physics-Based Reasoning](http://arxiv.org/abs/2502.12054) <span style="color:red">[CCF-A]</span> <br>
Xinyu Zhang, Yuxuan Dong, Yanrui Wu, Jiaxing Huang, **Chengyou Jia**, Basura Fernando, Mike Zheng Shou, Lingling Zhang, Jun Liu

- ``ACL 2025`` [OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis](https://arxiv.org/abs/2412.19723) <span style="color:red">[CCF-A]</span> <br>
Qiushi Sun, Kanzhi Cheng, Zichen Ding, Chuanyang Jin, Yian Wang, Fangzhi Xu, Zhenyu Wu, **Chengyou Jia**, Liheng Chen, Zhoumianze Liu, \\
Ben Kao, Guohao Li, Junxian He, Yu Qiao, Zhiyong Wu

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

- ``IEEE TIP`` [Disentangled Noisy Correspondence Learning](https://arxiv.org/abs/2408.05503) <span style="color:red"></span> <br>
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
- *2025.09* &emsp; National Scholarship (国家奖学金)
- *2023.09* &emsp; Freshman First Prize Scholarship (PhD)
- *2022.09* &emsp; First-Class Fellowships for Graduate Students at Xi’an Jiaotong University, Fellowships.
- *2020.09* &emsp; Computer Science Special Scholarship at Xi’an Jiaotong University, Fellowships.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<span class='anchor' id='-academic-services'></span>
# 💬 Academic Services
- Reviewer: NIPS, ECCV, AAAI, ICASSP, IEEE TIP, IEEE TCSVT and IEEE TNNLS.