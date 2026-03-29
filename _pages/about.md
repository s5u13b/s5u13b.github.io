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

<!--
bundle exec jekyll serve --force_polling --livereload
-->

<div class="section-card" markdown="1">
<span class='anchor' id='biography'></span>

# Biao Sun (孙彪)

<div class="author-info-inline">
  <span><i class="fas fa-fw fa-map-marker-alt"></i> Hangzhou, China</span>
  <span><i class="fas fa-fw fa-envelope"></i> sunbiao0824@163.com</span>
  <span><i class="fas fa-fw fa-phone"></i> 18319714119</span>
  <span><i class="fab fa-fw fa-weixin"></i> 18319714119 (ID: s5u13b)</span>
  <span><a href="https://scholar.google.com/citations?hl=zh-CN&user=k7BhaxQAAAAJ"><i class="fas fa-fw fa-graduation-cap"></i> Google Scholar</a></span>
  <span><a href="https://github.com/s5u13b"><i class="fab fa-fw fa-github"></i> GitHub</a></span>
  <span><a href="https://www.zhihu.com/people/xbnlzzl"><i class="fab fa-fw fa-zhihu"></i> 知乎</a></span>
</div>

I am an AI infrastructure R&D engineer at [Platform of Artificial Intelligence (PAI)](https://www.aliyun.com/product/pai), [Alibaba Cloud](https://cn.aliyun.com/) - I dive into wherever the evolving demands of LLM call for better infrastructure. Currently, I am working on building [Llumnix](https://github.com/llumnix-project/llumnix), a full-stack solution for distributed LLM inference serving, deployed on [PAI-EAS](https://www.aliyun.com/product/bigdata/learn/eas?spm=a2c4g.11186623.J_XmGx2FZCDAeIy2ZCWL7sW.23.171e1991wxQ2bW&scm=20140722.S_product@@%E4%BA%91%E4%BA%A7%E5%93%81@@2722372._.RL_EAS-LOC_2024NSProductLink-OR_ser-PAR1_213e366217577430627196800e98a7-V_4-RE_productNew-P0_0-P1_0-PAR2_descAbNew) (Alibaba Cloud's online model service platform). Previously, I contributed to and maintained [EasyCkpt](https://help.aliyun.com/zh/pai/user-guide/easyckpt), a high-performance asynchronous checkpointing framework for LLM pre-training, accelerating the pre-training of [Qwen2.5](https://arxiv.org/pdf/2412.15115) and [Qwen3](https://arxiv.org/pdf/2505.09388).

Prior to that, I received my M.Eng. degree from the [School of Computer Science and Engineering](https://scse.buaa.edu.cn/) at [Beihang University](https://www.buaa.edu.cn/) in June 2024, advised by [Prof. Hailong Yang](https://thomas-yang.github.io/). I received my B.Eng. degree from the [School of Software Engineering](https://www2.scut.edu.cn/sse/) at [South China University of Technology](https://www.scut.edu.cn/new/) in June 2021.


</div>

<div class="section-card" markdown="1">
<span class='anchor' id='-education'></span>

# <i class="fas fa-graduation-cap"></i> Education

<div class='paper-box-text' markdown="1">
- M.Eng., Computer Science, **Beihang University**, Beijing. (09/2021 - 06/2024)
  - Supervisor: [Prof. Hailong Yang](https://thomas-yang.github.io/)
  - Research Interests: Machine Learning System, Heterogeneous Computing
</div>

<div class='paper-box-text' markdown="1">
- B.Eng., Software Engineering, **South China University of Technology**, Guangzhou. (09/2017 - 06/2021)
</div>


</div>

<div class="section-card" markdown="1">
<span class='anchor' id='-work-experience'></span>

# <i class="fas fa-briefcase"></i> Work Experience

<div class='paper-box-text' markdown="1">
- Platform of Artificial Intelligence, **Alibaba Cloud**, Hangzhou. (07/2024 - Present)

  *R&D Engineer*
  - Core contributor of **Llumnix**, a full-stack solution for distributed LLM inference serving, deployed on [PAI-EAS](https://www.aliyun.com/product/bigdata/learn/eas?spm=a2c4g.11186623.J_XmGx2FZCDAeIy2ZCWL7sW.23.171e1991wxQ2bW&scm=20140722.S_product@@%E4%BA%91%E4%BA%A7%E5%93%81@@2722372._.RL_EAS-LOC_2024NSProductLink-OR_ser-PAR1_213e366217577430627196800e98a7-V_4-RE_productNew-P0_0-P1_0-PAR2_descAbNew) (Alibaba Cloud's online model service platform). [<i class="fab fa-github"></i> Repo](https://github.com/llumnix-project/llumnix) <a href="https://github.com/llumnix-project/llumnix/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/llumnix-project/llumnix?style=social" style="display:inline; vertical-align:middle;"></a>
    - Enhancing system design and implementation. Developing [instant and accurate load](https://docs.llumnix.ai/design/scheduler/instant_accurate_load), [cache-aware scheduling](https://docs.llumnix.ai/design/scheduler/cache_aware_scheduling), [predictor-enhanced scheduling](https://docs.llumnix.ai/design/scheduler/predictor_enhanced_scheduling), multi-domain instance failover mechanism, etc.
  - Core contributor of **Llumnix-ray**, a Ray-native dynamic scheduling system for LLM serving. [<i class="fab fa-github"></i> Repo](https://github.com/AlibabaPAI/llumnix) <a href="https://github.com/AlibabaPAI/llumnix/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/AlibabaPAI/llumnix?style=social" style="display:inline; vertical-align:middle;"></a>
    - Designing architecture, building Ray-based service orchestration and scaling capabilities to enable prefill-decode disaggregation and MoE model deployment, improving system stability and scalability.
  - Contributor and core maintainer of **EasyCkpt**, a high-performance asynchronous checkpointing framework for LLM pre-training, accelerating the pre-training of Qwen2.5 and Qwen3. [<i class="fas fa-book-open"></i> Doc](https://help.aliyun.com/zh/pai/user-guide/easyckpt)
    - Integrating the framework into Qwen2.5 and Qwen3 pre-training system, refactoring asynchronous checkpointing synchronization mode, mitigating checkpointing I/O instability in pre-training tasks at 10,000-GPU scale
</div>


</div>

<div class="section-card" markdown="1">
<span class='anchor' id='-intern-experience'></span>

# <i class="fas fa-building"></i> Intern Experience

<div class='paper-box-text' markdown="1">
- Platform of Artificial Intelligence, **Alibaba Cloud**, Beijing. (06/2023 - 06/2024)

  *Intern Engineer*
  - Designed and developed the prototype system of Llumnix, which proposes a dynamic scheduling policy that reschedules requests and their in-memory states with an efficient and scalable live migration mechanism, improving load balancing and isolation, mitigating resource fragmentation, and differentiating request priorities and SLOs.
  - Llumnix: Dynamic Scheduling for Large Language Model Serving (*OSDI'24*, co-first author) [<i class="fas fa-file-alt"></i> Paper/Slides/Talk](https://www.usenix.org/conference/osdi24/presentation/sun-biao)
</div>

<div class='paper-box-text' markdown="1">
- Model-ToolChain Team, **SenseTime**, Beijing. *Intern System Researcher*. (03/2023 - 05/2023) 
</div>

<div class='paper-box-text' markdown="1">
- Platform of Artificial Intelligence, **Alibaba Cloud**, Beijing. *Intern System Researcher*. (07/2021 - 12/2021)
</div>


</div>

<div class="section-card" markdown="1">
<span class='anchor' id='-publications'></span>

# <i class="fas fa-book"></i> Publications


- **Qwen3 Technical Report**. *Qwen Team* (contributor). arXiv preprint 2025 (arXiv:2505.09388). [<i class="fas fa-file-pdf"></i> PDF](https://arxiv.org/pdf/2505.09388)

- **Qwen2.5 Technical Report**. *Qwen Team* (contributor). arXiv preprint 2024 (arXiv:2412.15115). [<i class="fas fa-file-pdf"></i> PDF](https://arxiv.org/pdf/2412.15115)


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">OSDI’24</div><img src='images/llumnix_arch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- **Llumnix: Dynamic Scheduling for Large Language Model Serving**

  ***Biao Sun**\*, Ziming Huang\*, Hanyu Zhao\*, Wencong Xiao, Xinyi Zhang, Yong Li, Wei Lin* (\*co-first authors)

  18th USENIX Symposium on Operating Systems Design and Implementation (***OSDI’24***)

  [<i class="fas fa-file-alt"></i> Paper/Slides/Talk](https://www.usenix.org/conference/osdi24/presentation/sun-biao) [<i class="fab fa-github"></i> Code](https://github.com/AlibabaPAI/llumnix)
</div>
</div>


<div class='paper-box-text' markdown="1">
- **Exploiting Input Tensor Dynamics in Activation Checkpointing for Efficient Training on GPU** 
  
  *Jianjin Liao, Mingzhen Li, Hailong Yang, Qingxiao Sun, **Biao Sun**, Jiwei Hao, Tianyu Feng, Fengwei Yu, Shengdong Chen, Ye Tao, Zicheng Zhang, Zhongzhi Luan, Depei Qian*

   2023 IEEE International Parallel and Distributed Processing Symposium (***IPDPS’23***)

  [<i class="fas fa-file-pdf"></i> PDF](/pdf/Exploiting_Input_Tensor_Dynamics_in_Activation_Checkpointing_for_Efficient_Training_on_GPU.pdf)
</div>


<div class='paper-box-text' markdown="1">
- **EasyScale: Elastic Training with Consistent Accuracy and Improved Utilization on GPUs**

  *Mingzhen Li, Wencong Xiao, Hailong Yang, **Biao Sun**, Hanyu Zhao, Shiru Ren, Zhongzhi Luan, Xianyan Jia, Yi Liu, Yong Li, Depei Qian, Wei Lin*

  International Conference for High Performance Computing, Networking, Storage, and Analysis 2023 (***SC'23***)

  [<i class="fas fa-file-alt"></i> Paper](https://arxiv.org/pdf/2208.14228) [<i class="fas fa-video"></i> Talk](https://www.youtube.com/watch?v=a63MWTKcSbM)
</div>


<div class='paper-box-text' markdown="1">
- **Adapting Combined Tiling to Stencil Optimizations on Sunway Processor**

  ***Biao Sun**, Mingzhen Li, Hailong Yang, Jun Xu, Huaitao Zhang, Zhongzhi Luan, Depei Qian*

  CCF Transactions on High Performance Computing 2023 (***THPC’23***)

  [<i class="fas fa-file-pdf"></i> PDF](/pdf/Adapting_Combined_Tiling_to_Stencil_Optimizations_on_Sunway_Processor.pdf)
</div>


</div>

<div class="section-card" markdown="1">
<span class='anchor' id='-awards'></span>

# <i class="fas fa-trophy"></i> Awards
- **Top 10 Patents of Alibaba Cloud & Tongyi(Qwen) Lab**, Alibaba Cloud, 2025
- **CCF HPCChina Outstanding Paper Award**, Beihang University, 2022
- **4th Place, the 5th "Sunway Cup" National Domestic CPU Parallel Application Challenge**, Beihang University, 2021
- **National Scholarship**, South China University of Technology, 2018
</div>
