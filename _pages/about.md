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

Hi! I am a fourth-year Ph.D. student at School of Computer Science and Technology, Shanghai Jiao Tong University, supervised by Prof. [Li Niu](https://www.ustcnewly.com/). Prior to this, I earned my Bachelor’s degree from School of Computer Science and Technology, University of Electronic Science and Technology of China in 2023.

My research interest includes interactive video generation and embodied intelligence. I expect to graduate in Summer 2028 and am actively seeking internship opportunities (remote or onsite). Please feel free to contact me at whynothaha@sjtu.edu.cn.


# 🔥 News
- *2026.10*: &nbsp;🎉🎉 Three papers accepted to NeurIPS 2026 (including two co-first-author papers), thanks to all co-authors!!
- *2026.06*: &nbsp;🎉🎉 We release DreamX World and PermaVid, marking progress in building interactive and consistent video world models!!
- *2026.06*: &nbsp;🎉🎉 One paper accepted to ECCV 2026, thanks to all co-authors!!
- *2026.05*: &nbsp;🎉🎉 One paper accepted to ICML 2026, thanks to all co-authors!!
- *2026.04*: &nbsp;🎉🎉 One paper accepted to ACL Findings 2026, thanks to all co-authors!!
- *2026.03*: &nbsp;🎉🎉 One paper accepted to ICME 2026, thanks to all co-authors!!
- *2026.01*: &nbsp;🎉🎉 One paper accepted to WWW 2026, thanks to all co-authors!!
- *2026.01*: &nbsp;🎉🎉 One paper accepted to ICLR 2026, thanks to all co-authors!!
- *2026.01*: &nbsp;🎉🎉 One co-first-author paper accepted to ICASSP 2026, thanks to all co-authors!!
- *2025.03*: &nbsp;🎉🎉 One first-author paper accepted to ICME 2025, thanks to all co-authors!!
- *2025.02*: &nbsp;🎉🎉 One first-author paper accepted to CVPR 2025, thanks to all co-authors!!
- *2024.02*: &nbsp;🎉🎉 One first-author paper accepted to Pattern Recognition 2024, thanks to all co-authors!!
- *2022.08*: &nbsp;🎉🎉 One first-author paper accepted to Information Sciences 2022, thanks to all co-authors!!

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Arxiv 2026</div>
      <img src='images/overview_dreamx_world.jpg' alt="sym" width="100%">
    </div>
  </div>

  <div class='paper-box-text'>
    <p>
      <a href="https://arxiv.org/abs/2606.16993">
      DreamX-World: A General-Purpose Interactive World Model
      </a>
    </p>
    <p>
      DreamX Team
    </p>
    <p>
      Arxiv 2026
    </p>
    <p>
      <a href="https://arxiv.org/abs/2606.16993"
         style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
         Paper
      </a>
      <a href="https://amap-ml.github.io/DreamX_World"
         style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
         Project
      </a>
      <a href="https://huggingface.co/GD-ML/DreamX-World-5B"
         style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
         Model
      </a>
    </p>

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Arxiv 2026</div>
      <img src='images/overview_r2m_bench.png' alt="R2M-Bench overview" width="100%">
    </div>
  </div>

<div class='paper-box-text'>

<p>
  <a href="https://arxiv.org/abs/2608.27328">R2M-Bench: Evaluating Revisit Memory via Relative Consistency in Interactive Video World Models</a>
</p>

<p>
Qiwen Gu*, <b>Bingjie Gao*</b>, Rui Chen, Geng Li, Jifan Li, Qishuai Wen, Li Niu, Jing Tang, Xiangxiang Chu, Junqiao Zhao
</p>

<p><sup>*</sup>Equal contribution</p>

<p>Arxiv 2026</p>

<p>
  <a href="https://arxiv.org/abs/2608.27328"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
  <a href="https://github.com/AMAP-ML/R2MBench"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
      Code
  </a>
</p>

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2026</div>
      <img src='images/overview_permavid.jpg' alt="sym" width="100%">
    </div>
  </div>

  <div class='paper-box-text'>
    <p>
      <a href="https://arxiv.org/abs/2606.16449">
      PermaVid: Consistent Video Generation Across Edits via Disentangled Context Memory
      </a>
    </p>
    <p>
      Shuai Yang*, <b>Bingjie Gao*</b>, Ziwei Liu, Jiaqi Wang, Dahua Lin, Tong Wu
    </p>
    <p><sup>*</sup>Equal contribution</p>
    <p>
      Neural Information Processing Systems (NeurIPS) 2026
    </p>
    <p>
      <a href="https://arxiv.org/abs/2606.16449"
         style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
         Paper
      </a>
      <a href="https://ys-imtech.github.io/projects/PermaVid/"
         style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
         Project
      </a>
      <a href="https://github.com/YS-IMTech/PermaVid"
         style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
         Code
      </a>
      <a href="https://huggingface.co/datasets/ysmikey/PermaVid_datasets"
         style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
         Dataset
      </a>
    </p>

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Arxiv 2026</div>
      <img src='images/overview_arps.png' alt="ARPS overview" width="100%">
    </div>
  </div>

<div class='paper-box-text'>

<p>
  <a href="https://arxiv.org/abs/2609.23369">The Right Future for Action: Learning Action-Relevant Predictive States in World Action Models</a>
</p>

<p>
Qiwen Gu, Jifan Li, <b>Bingjie Gao</b>, Rui Chen, Jing Tang, Xiangxiang Chu, Junqiao Zhao
</p>

<p>Arxiv 2026</p>

<p>
  <a href="https://arxiv.org/abs/2609.23369"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
</p>

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2026</div>
      <img src='images/overview_dlr.png' alt="Discrete Latent Reasoning overview" width="100%">
    </div>
  </div>

<div class='paper-box-text'>

<p>
  <a href="https://arxiv.org/abs/2606.29712">Why Struggle with Continuous Latents? Interpretable Discrete Latent Reasoning via Rendered Compression</a>
</p>

<p>
Shuochen Chang, Qingyang Liu, Shaobo Wang, <b>Bingjie Gao</b>, Qianli Ma, Haonan Zhao, Yibo Miao, Yulin Sun, Zelin Peng, Jiangtong Li, Li Niu
</p>

<p>Neural Information Processing Systems (NeurIPS) 2026</p>

<p>
  <a href="https://arxiv.org/abs/2606.29712"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
  <a href="https://github.com/Miraclecsc/Discrete-Latent-Reasoning"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
      Code
  </a>
</p>

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ECCV 2026</div>
      <img src='images/overview_icrdrag.jpg' alt="ICRDrag qualitative results" width="100%">
    </div>
  </div>

<div class='paper-box-text'>

<p>
  <a href="https://link.springer.com/chapter/10.1007/978-3-032-37490-5_26">In-Context Region-Based Drag: Drag Any Region to Any Shape</a>
</p>

<p>
Jiacheng Sui*, Tianyu Hao*, <b>Bingjie Gao</b>, Li Niu, Guangtao Zhai
</p>

<p><sup>*</sup>Equal contribution</p>

<p>European Conference on Computer Vision (ECCV) 2026</p>

<p>
  <a href="https://link.springer.com/chapter/10.1007/978-3-032-37490-5_26"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
  <a href="https://github.com/bcmi/ICRDrag-Region-Drag-Editing"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
      Code
  </a>
</p>

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2025</div>
      <img src='images/overview_rapo.png' alt="sym" width="100%">
    </div>
  </div>

  <div class='paper-box-text'>
    <p>
      <a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Gao_The_Devil_is_in_the_Prompts_Retrieval-Augmented_Prompt_Optimization_for_CVPR_2025_paper.pdf">
      The Devil is in the Prompts: Retrieval-Augmented Prompt Optimization for Text-to-Video Generation
      </a>
    </p>
    <p>
      <b>Bingjie Gao</b>, Xinyu Gao, Xiaoxue Wu, Yujie Zhou, Yu Qiao, Li Niu, Xinyuan Chen, Yaohui Wang
    </p>
    <p>
      Conference on Computer Vision and Pattern Recognition (CVPR) 2025
    </p>
    <p>
      <a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Gao_The_Devil_is_in_the_Prompts_Retrieval-Augmented_Prompt_Optimization_for_CVPR_2025_paper.pdf"
         style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
         Paper
      </a>
      <a href="https://github.com/Vchitect/RAPO"
         style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
         Code
      </a>
    </p>

  </div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/overview_rapo_plus.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RAPO++: Cross-Stage Prompt Optimization for Text-to-Video Generation via Data Alignment and Test-Time Scaling](https://arxiv.org/abs/2510.20206)

**Bingjie Gao**, Qianli Ma, Xiaoxue Wu, Shuai Yang, Guanzhou Lan, Haonan Zhao, Jiaxuan Chen, Qingyang Liu, Yu Qiao, Xinyuan Chen, Yaohui Wang, Li Niu

<p>Arxiv 2025</p>
<p>
  <a href="https://arxiv.org/abs/2510.20206"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
  <a href="https://github.com/Vchitect/RAPO"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
      Code
  </a>
</p>

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">ICASSP 2026</div>
<img src='images/overview_animatescene.png' alt="sym" width="100%">
</div>
</div>
<div class='paper-box-text'>

<a href="https://arxiv.org/abs/2508.05982">AnimateScene: Camera-controllable Animation in Any Scene</a>

<p>
<b>Qingyang Liu*</b>, <b>Bingjie Gao*</b>, Weiheng Huang, Jun Zhang, Zhongqian Sun, 
Yang Wei, Fengrui Liu, Zelin Peng, Qianli Ma, Shuai Yang, Zhaohe Liao, Haonan Zhao, Li Niu
</p>

<p><sup>*</sup>Equal contribution</p>

<p>International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2026</p>

<p>
  <a href="https://arxiv.org/abs/2508.05982"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
  <a href="https://whynothaha.github.io/AnimateScene/AnimateScene.html"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
      Project
  </a>
</p>

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">ICME 2025</div>
<img src='images/framework_icme.png' alt="sym" width="100%">
</div>
</div>
<div class='paper-box-text'>

<a href="https://arxiv.org/abs/2504.12029">Object Placement for Anything</a>

<p>
<b>Bingjie Gao</b>, Bo Zhang, Li Niu
</p>

<p>International Conference on Multimedia and Expo (ICME) 2025</p>

<p>
  <a href="https://arxiv.org/abs/2504.12029"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
</p>

</div>
</div>


<div class='paper-box'>
<div class='paper-box-text'>

<a href="https://arxiv.org/abs/2508.11484">Cinetrans: Learning to generate videos with cinematic transitions via masked diffusion models</a>

<p>
Xiaoxue Wu, <b>Bingjie Gao</b>, Yu Qiao, Yaohui Wang, Xinyuan Chen
</p>

<p>International Conference on Learning Representations (ICLR) 2026</p>

<p>
  <a href="https://arxiv.org/abs/2508.11484"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
  <a href="https://github.com/Vchitect/CineTrans"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
      Code
  </a>
  <a href="https://uknowsth.github.io/CineTrans/"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
      Project
  </a>
</p>

</div>
</div>


<div class='paper-box'>
<div class='paper-box-text'>

<a href="https://openreview.net/forum?id=Fkwvsf7U8N&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DACM.org%2FTheWebConf%2F2026%2FIndustry%2FAuthors%23your-submissions)">Bridging Visual Dynamics and Narrative Reasoning: Multimodal Large Language Models for Short Drama Quality Assessment</a>

<p>
Qingyang Liu, Jiangtong Li, Zelin Peng, Shaobo Wang, Zhaohe Liao, Shuochen Chang, <b>Bingjie Gao</b>, Haonan Zhao, Mu Liu, Jidong Jiang, Li Niu
</p>

<p>The ACM Web Conference (WWW) 2026 Industry Track</p>

<p>
  <a href="https://openreview.net/forum?id=Fkwvsf7U8N&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DACM.org%2FTheWebConf%2F2026%2FIndustry%2FAuthors%23your-submissions"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
</p>

</div>
</div>


<div class='paper-box'>
<div class='paper-box-text'>

<a href="https://arxiv.org/abs/2510.19600">Human-Agent Collaborative Paper-to-Page Crafting for Under $0.1</a>

<p>
Qianli Ma, Siyu Wang, Yilin Chen, Yinhao Tang, Yixiang Yang, Chang Guo, <b>Bingjie Gao</b>, Zhening Xing, Yanan Sun, Zhipeng Zhang
</p>

<p>Arxiv 2025</p>

<p>
  <a href="https://arxiv.org/abs/2510.19600"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
  <a href="https://github.com/AutoLab-SAI-SJTU/AutoPage"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
      Code
  </a>
  <a href="https://mqleet.github.io/AutoPage_ProjectPage/"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none;">
      Project
  </a>
</p>

</div>
</div>



<div class='paper-box'>
<div class='paper-box-text'>

<a href="https://www.sciencedirect.com/science/article/pii/S0031320323007379">HIE-EDT: Hierarchical interval estimation-based evidential decision tree</a>

<p>
<b>Bingjie Gao</b>, Qianli Zhou, Yong Deng
</p>

<p>Pattern Recognition (PR) 2024</p>

<p>
  <a href="https://www.sciencedirect.com/science/article/pii/S0031320323007379"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
</p>

</div>
</div>


<div class='paper-box'>
<div class='paper-box-text'>

<a href="https://www.sciencedirect.com/science/article/pii/S0020025522007150">BIM-AFA: Belief information measure-based attribute fusion approach in improving the quality of uncertain data</a>

<p>
<b>Bingjie Gao</b>, Qianli Zhou, Yong Deng
</p>

<p>Information Sciences (INS) 2022</p>

<p>
  <a href="https://www.sciencedirect.com/science/article/pii/S0020025522007150"
      style="padding:4px 10px; border:1px solid #aaa; border-radius:4px; text-decoration:none; margin-right:6px;">
      Paper
  </a>
</p>

</div>
</div>




# 🎖 Honors and Awards
- Outstanding Graduate of Sichuan Province, 2023
- Outstanding Graduate of University of Electronic Science and Technology of China, 2023
- Second Prize (National) in the Contemporary Undergraduate Mathematical Contest in Modeling (CUMCM), 2021


# 📖 Educations
<div style="display: flex; align-items: center;">
  <div style="margin-right: 12px;">
    <img src="images/sjtu_logo.png" alt="SJTU logo" width="80">
  </div>

  <div>
    <div><strong>2023.09 - 2028.06</strong>, Ph.D. Student.</div>
    <div>School of Computer Science and Engineering.</div>
    <div>Shanghai Jiao Tong University, Shanghai.</div>
  </div>
</div>


<div style="display: flex; align-items: center;">
  <div style="margin-right: 12px;">
    <img src="images/uestc_logo.png" alt="UESTC logo" width="80">
  </div>

  <div>
    <div><strong>2019.09 - 2023.06</strong>, Undergraduate.</div>
    <div>School of Computer Science and Engineering.</div>
    <div>University of Electronic Science and Technology of China, Chengdu, Sichuan.</div>
  </div>
</div>

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <div style="margin-right: 12px;">
    <a href="https://github.com/AMAP-ML">
      <img src="images/dreamx_team_logo.png" alt="DreamX Team logo" width="80">
    </a>
  </div>

  <div>
    <div><strong>2026.05 - Present</strong></div>
    <div><a href="https://www.amap.com/">Alibaba AMAP</a>, <a href="https://github.com/AMAP-ML">DreamX Team</a>.</div>
  </div>
</div>


<div style="display: flex; align-items: center;">
  <div style="margin-right: 12px;">
    <a href="https://github.com/Vchitect">
      <img src="images/vchitect_logo.jpg" alt="Vchitect Team logo" width="80">
    </a>
  </div>

  <div>
    <div><strong>2024.03 - 2025.09</strong></div>
    <div><a href="https://www.shlab.org.cn/">Shanghai AI Laboratory</a>, <a href="https://github.com/Vchitect">Vchitect Team</a>, China.</div>
  </div>
</div>
