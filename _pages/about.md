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

<span class='anchor' id='biography'></span>

# Biography

I am a R&D engineer (started from 07/2024) at [Platform of Artificial Intelligence (PAI)](https://www.aliyun.com/product/pai), [Alibaba Cloud](https://cn.aliyun.com/). Currently, I am mainly working on building [Llumnix](https://github.com/AlibabaPAI/llumnix), a dynamic scheduling system for large language model serving (still a long way to go :)). Besides, I am maintaining [EasyCkpt](https://help.aliyun.com/zh/pai/user-guide/easyckpt), a high performance asynchronous checkpointing framework for large language model training, accelerating [Qwen2.5](https://arxiv.org/pdf/2412.15115) and [Qwen3](https://github.com/QwenLM/Qwen3/blob/main/Qwen3_Technical_Report.pdf) training.

Prior to that, I received my M.Eng. degree from the [School of Computer Science and Engineering](https://scse.buaa.edu.cn/) at [Beihang University](https://www.buaa.edu.cn/) in June 2024, advised by [Prof. Hailong Yang](https://thomas-yang.github.io/). And I received my B.Eng. degree from the [School of Software Engineering](https://www2.scut.edu.cn/sse/) at [South China University of Technology](https://www.scut.edu.cn/new/) in June 2021.


<span class='anchor' id='-education'></span>

# Education

<div class='paper-box-text' markdown="1">
- M.Eng., Computer Science, **Beihang University**, Beijing. (09/2021 - 06/2024)
  - Supervisor: [Prof. Hailong Yang](https://thomas-yang.github.io/)
  - Research Interests: Machine Learning System, Heterogeneous Computing
</div>

<div class='paper-box-text' markdown="1">
- B.Eng., Software Engineering, **South China University of Technology**, Guangzhou. (09/2017 - 06/2021)
  - GPA: 3.83/4.0, Rank: 13/267
</div>

 
<span class='anchor' id='-work-experience'></span>

# Work Experience

<div class='paper-box-text' markdown="1">
- Platform of Artificial Intelligence, **Alibaba Cloud**, Hangzhou. (07/2024 - Now)

  *R&D Engineer*
  - Core contributor of **Llumnix**, a dynamic scheduling system for large language model serving. [[Code]](https://github.com/AlibabaPAI/llumnix)
  - Core maintainer of **EasyCkpt**, a high performance asynchronous checkpointing framework for large language model training, accelerating Qwen2.5 and Qwen3 training. [[Doc]](https://help.aliyun.com/zh/pai/user-guide/easyckpt)
</div>


<span class='anchor' id='-intern-experience'></span>

# Intern Experience

<div class='paper-box-text' markdown="1">
- Platform of Artificial Intelligence, **Alibaba Cloud**, Beijing. (06/2023 - 06/2024)
  
  *Intern R&D Engineer*
  - Design and develop the prototype system of Llumnix. Llumnix proposes a dynamic scheduling policy that reschedules requests and their in-memory states with an efficient and scalable live migration mechanism, improving load balancing and isolation, mitigating resource fragmentation, and differentiating request priorities and SLOs.
  - Llumnix: Dynamic Scheduling for Large Language Model Serving (*OSDI’24*, co-first author) [[Paper/Slides/Talk]](https://www.usenix.org/conference/osdi24/presentation/sun-biao)
</div>

<div class='paper-box-text' markdown="1">
- Model-ToolChain Team, **Sensetime**, Beijing. (03/2023 - 05/2023)

  *Intern System Researcher*
  - Contribute to the training and inference optimization of the stable diffusion models on SenseMirage platform.
  - Reproduce the training activation memory compression optimization proposed in Gist.
<!--
implement packed-relu-pool and compressed-relu-conv operators.
-->
</div>

<div class='paper-box-text' markdown="1">
- PaddlePaddle Team, **Baidu**, Beijing. (06/2022 - 09/2022)

  *Intern R&D Engineer*
  - Participate in the CCF-GLCC Open Source Programming Summer Camp, optimize the max_pool3d and
 depthwise_conv2d_grad operators in the Paddle framework.
  - Achieve performance improvements of 224% and 36% respectively, surpassing PyTorch performance
 by 14% and 48%, submitt a total of 4 PRs to both Paddle and PyTorch.
</div>

<div class='paper-box-text' markdown="1">
- Platform of Artificial Intelligence, **Alibaba Cloud**, Beijing. (07/2021 - 12/2021)

  *Intern System Researcher*
  - Contribute to EasyScale, an elastic training system that achieves consistent model accuracy under resource
 elasticity for both homogeneous and heterogeneous GPUs.
  - EasyScale: Elastic Training with Consistent Accuracy and Improved Utilization on GPUs (*SC’23*, fourth author) [[Paper]](https://arxiv.org/pdf/2208.14228)[[Talk]](https://www.youtube.com/watch?v=a63MWTKcSbM)
</div>


<span class='anchor' id='-publications'></span>

# Publications


- **Qwen3 Technical Report**. *Qwen Team* (contributor). arXiv preprint 2025 (arXiv:2505.09388). [[PDF]](https://arxiv.org/pdf/2505.09388)

- **Qwen2.5 Technical Report**. *Qwen Team* (contributor). arXiv preprint 2024 (arXiv:2412.15115). [[PDF]](https://arxiv.org/pdf/2412.15115)


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">OSDI’24</div><img src='images/llumnix_arch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- **Llumnix: Dynamic Scheduling for Large Language Model Serving**

  ***Biao Sun**\*, Ziming Huang\*, Hanyu Zhao\*, Wencong Xiao, Xinyi Zhang, Yong Li, Wei Lin* (\*co-first authors)

  18th USENIX Symposium on Operating Systems Design and Implementation (***OSDI’24***)

  [[Paper/Slides/Talk]](https://www.usenix.org/conference/osdi24/presentation/sun-biao)[[Code]](https://github.com/AlibabaPAI/llumnix)
</div>
</div>


<div class='paper-box-text' markdown="1">
- **Exploiting Input Tensor Dynamics in Activation Checkpointing for Efficient Training on GPU** 
  
  *Jianjin Liao, Mingzhen Li, Hailong Yang, Qingxiao Sun, **Biao Sun**, Jiwei Hao, Tianyu Feng, Fengwei Yu, Shengdong Chen, Ye Tao, Zicheng Zhang, Zhongzhi Luan, Depei Qian*

   2023 IEEE International Parallel and Distributed Processing Symposium (***IPDPS’23***)

  [[PDF]](/pdf/Adapting_Combined_Tiling_to_Stencil_Optimizations_on_Sunway_Processor.pdf)
</div>


<div class='paper-box-text' markdown="1">
- **EasyScale: Elastic Training with Consistent Accuracy and Improved Utilization on GPUs**

  *Mingzhen Li, Wencong Xiao, Hailong Yang, **Biao Sun**, Hanyu Zhao, Shiru Ren, Zhongzhi Luan, Xianyan Jia, Yi Liu, Yong Li, Depei Qian, Wei Lin*

  International Conference for High Performance Computing, Networking, Storage, and Analysis 2023 (***SC’23***)

  [[Paper]](https://arxiv.org/pdf/2208.14228)[[Talk]](https://www.youtube.com/watch?v=a63MWTKcSbM)
</div>


<div class='paper-box-text' markdown="1">
- **Adapting Combined Tiling to Stencil Optimizations on Sunway Processor**

  ***Biao Sun**, Mingzhen Li, Hailong Yang, Jun Xu, Huaitao Zhang, Zhongzhi Luan, Depei Qian*

  CCF Transactions on High Performance Computing 2023 (***THPC’23***)

  [[PDF]](/pdf/Exploiting_Input_Tensor_Dynamics_in_Activation_Checkpointing_for_Efficient_Training_on_GPU.pdf)
</div>


<span class='anchor' id='-awards'></span>

# Awards
- **Top 10 Parents of Alibaba Cloud & Tongyi(Qwen) Lab**, Alibaba Cloud, 2025
- **CCF HPCChina Outstanding Paper Award**, Beihang University, 2022
- **National Encouragement Scholarship**, South China University of Technology, 2019
- **National Scholarship**, South China University of Technology, 2018
