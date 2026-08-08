---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hello! I'm **Peng Zheng** (郑鹏 in Chinese), a Ph.D. student at the **School of Artificial Intelligence, Jilin University**, advised by Associate Professor [Rui Ma](https://ruim-jlu.github.io). I am also jointly trained at the **Shanghai Innovation Institute**, under the supervision of Professor [Zuxuan Wu](https://zxwu.azurewebsites.net/).

My research primarily focuses on **AIGC**, with a particular emphasis on **controllable visual content generation**. I am interested in developing efficient, controllable, and scalable generative models for high-fidelity visual content creation.

More recently, I have become increasingly interested in **video generation** and **world models**, and I am excited to explore these emerging directions in future research.

Feel free to reach out if you are interested in research discussions or potential collaborations! 😊


# 🔥 News
- *2025.06*: One paper is accepted by ICCV 2025.
- *2024.08*: One paper is accepted by PG 2024. Thanks to Ruiqi Liu!
- *2024.07*: One paper is accepted by ECCV 2024.
- *2024.03*: Create my homepage. 

# 📝 Publications 

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/copycat.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

[CopyCat: Improving Fine-Grained Subject Consistency in Subject-to-Image Models within Seconds](https://arxiv.org/pdf/2608.00674v1)

**Peng Zheng**, Ruiqi Liu, Rui Ma, Zuxuan Wu

- We propose CopyCat, a lightweight post-training refinement framework that substantially improves fine-grained subject consistency within only a few seconds. By introducing a lightweight Fine-grained Consistency LoRA and an exact self-reconstruction objective, CopyCat consistently enhances subject fidelity while generalizing to unseen subjects without any subject-specific optimization.

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/omnistyle2.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

[OmniStyle2: Scalable and High Quality Artistic Style Transfer Data Generation via Destylization](https://arxiv.org/pdf/2509.05970)

Ye Wang, Zili Yi, Yibo Zhang, **Peng Zheng**, Xuping Xie, Linlian Jiang, Yilin Wang<span class="co-corresponding-author"></span>, Rui Ma<span class="co-corresponding-author"></span>

- OmniStyle2 presents a scalable framework for generating high-quality artistic style transfer datasets through destylization, enabling large-scale data synthesis and significantly improving artistic image generation across diverse styles.

</div>
</div>



<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/discon.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

[Rethinking Discrete Tokens: Treating Them as Conditions for Continuous Autoregressive Image Synthesis](https://pengzheng0707.github.io/DisCon)

<style>
  .co-first-author::after {
    content: '*';
    color: red;
  }
</style>

<style>
  .co-corresponding-author::after {
    content: '#';
    color: red;
  }
</style>

**Peng Zheng**, Junke Wang, Yi Chang, Yizhou Yu, Rui Ma<span class="co-corresponding-author"></span>, Zuxuan Wu<span class="co-corresponding-author"></span>

- This paper introduces DisCon (Discrete-Conditioned Continuous Autoregressive Model), a novel framework that reinterprets discrete tokens as conditional signals rather than generation targets. By modeling the conditional probability of continuous representations conditioned on discrete tokens, DisCon circumvents the optimization challenges of continuous token modeling while avoiding the information loss caused by quantization.
</div>
</div>

<div class='paper-box'>

  <div class='paper-box-image'>
    <div><div class="badge">ECCV 2024</div><img src='images/semantichumanhd.png' alt="sym" width="500"></div>
  </div>
  <div class='paper-box-text' markdown="1">

  [SemanticHuman-HD: High-Resolution Semantic Disentangled 3D Human Generation](https://pengzheng0707.github.io/SemanticHuman-HD/)

  **Peng Zheng**, Tao Liu, Zili Yi, Rui Ma

  - We introduce SemanticHuman-HD, the first method to achieve semantic disentangled human image synthesis. Notably, SemanticHuman-HD is also the first method to achieve 3D-aware image synthesis at 10242 resolution, benefiting from our proposed 3D-aware super-resolution module.
  </div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">PG 2024</div><img src='images/3dssg.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

[3D-SSGAN: Lifting 2D Semantics for 3D-Aware Compositional Portrait Synthesis](https://arxiv.org/abs/2401.03764)

<style>
  .co-first-author::after {
    content: '*';
    color: red;
  }
</style>

<style>
  .co-corresponding-author::after {
    content: '#';
    color: red;
  }
</style>

Ruiqi Liu<span class="co-first-author"></span>, **Peng Zheng**<span class="co-first-author"></span>, Ye Wang, Rui Ma

- We propose 3D-SSGAN, a novel framework for 3D-aware compositional portrait image synthesis. First, a simple yet effective depth-guided 2D-to-3D lifting module maps the generated 2D part features and semantics to 3D. Then, a volume renderer with a novel 3D-aware semantic mask renderer is utilized to produce the composed face features and corresponding masks. 
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">arXiv2025</div><img src='images/freelora.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

[FreeLoRA: Enabling Training-Free LoRA Fusion for Autoregressive Multi-Subject Personalization](https://pengzheng0707.github.io/FreeLoRA)

 **Peng Zheng**, Ye Wang, Rui Ma, Zuxuan Wu

- We present FreeLoRA, a simple and generalizable framework that enables training-free fusion of subject-specific LoRA modules for multi-subject personalization. It achieves high-quality composition without additional finetuning, and supports flexible combinations of diverse subjects at inference time.
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">CVM 2026(recommended to JCST)</div><img src='images/supernerf-gan.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

[A 3D-Consistent Super-Resolution Framework for Efficient and Enhanced 3D-Aware Image Synthesis](https://iccvm.org/2026/files/papers/233.pdf)

 **Peng Zheng**, Yi Chang, Yilin Wang, Rui Ma

- We propose SuperNeRF-GAN, a universal framework for 3D-consistent super-resolution. A key highlight of SuperNeRF-GAN
is its seamless integration with NeRF-based 3D-aware image synthesis methods and it can simultaneously enhance the resolution
of generated images while preserving 3D-consistency and reducing computational cost. 
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">arXiv2024</div><img src='images/taylor.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

[TaylorGrid: Towards Fast and High-Quality Implicit Field Learning via Direct Taylor-based Grid Optimization](https://arxiv.org/abs/2402.14415)

Renyi Mao, Qingshan Xu, **Peng Zheng**, Ye Wang, Tieru Wu, Rui Ma

- In this paper, we aim for both fast and high-quality implicit field learning, and propose TaylorGrid, a novel implicit field representation which can be efficiently computed via direct Taylor expansion optimization on 2D or 3D grids. 
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">arXiv2024</div><img src='images/D-Aug.png' alt="sym" width="500"></div></div>
<div class='paper-box-text' markdown="1">

[D-Aug: Enhancing Data Augmentation for Dynamic LiDAR Scenes](https://arxiv.org/abs/2404.11127)

Jiaxing Zhao, **Peng Zheng**<span class="co-corresponding-author"></span>, Rui Ma<span class="co-corresponding-author"></span>

- We propose D-Aug, a LiDAR data augmentation method tailored for augmenting dynamic scenes. D-Aug extracts objects and inserts them into dynamic scenes, considering the continuity of these objects across consecutive frames.
</div>
</div>

# 🎖 Honors and Awards
- *2023:* Received a third prize in the Second Jittor Artificial Intelligence Competition. 

# 📖 Educations
- *2024.09 – Present*, Ph.D. Student, Jilin University, Artificial Intelligence  
- *2022.09 – 2024.06*, M.E. Student (transferred to Ph.D. program), Jilin University, Artificial Intelligence  
- *2018.09 – 2022.06*, B.E., Jilin University, Agricultural Mechanization and Automation

# 🔍 Reviewing Activities
- *2025:* Reviewer for NeurIPS 2025  
- *2025:* Reviewer for CAD/Graphics 2025