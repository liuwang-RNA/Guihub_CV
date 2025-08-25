---
permalink: /
title: "Welcome to my RNA world!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a postdoctoral researcher at <a href="https://www.hxkq.org/" target="_blank">West China Hospital of Stomatology</a> and 
<a href="http://www.sklod.org/" target="_blank">the State Key Laboratory of Stomatology</a>, as well as 
<a href="https://www.wchscu.cn/Home.html" target="_blank">West China Hospital</a> and 
<a href="https://sklb.scu.edu.cn/" target="_blank">the State Key Laboratory of Biotherapy</a>, 
<a href="https://en.scu.edu.cn/" target="_blank">Sichuan University</a>.
During my doctoral studies, I was jointly supervised by 
<a href="https://zsulab.com/" target="_blank">Prof. Zhaoming Su</a> and <a href="https://www.hxkq.org/Html/News/Articles/10880.html" target="_blank">Prof. Dingming Huang</a>, 
under whose guidance I published several research articles in leading journals such as 
<a href="https://liuwang-rna.github.io/Guihub_CV/publication/2025-05-01_Science" target="_blank"><strong><em>Science</em></strong></a>, 
<a href="https://liuwang-rna.github.io/Guihub_CV/publication/2025-06-15_NSMB" target="_blank"><strong><em>Nature Structural & Molecular Biology</em></strong></a>, 
and <a href="https://liuwang-rna.github.io/Guihub_CV/publication/2025-05-15" target="_blank"><strong><em>Nature Protocols</em></strong></a>.

<!-- 四个视频 2×2 网格布局 -->
<style>
  .video-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* 两列 */
    gap: 20px; /* 视频之间的间距 */
    justify-items: center;
    margin: 20px auto;
    max-width: 1200px; /* 整体最大宽度 */
  }
  .video-item {
    text-align: center;
  }
  .video-item video {
    width: 100%;
    max-width: 500px;  /* 每个视频最大宽度 */
    border-radius: 10px;
    border: 1px solid #e5e7eb;
  }
  .video-caption {
    margin-top: 8px;
    font-size: 0.95rem;
    color: #444;
  }
  @media (max-width: 900px) {
    .video-grid {
      grid-template-columns: 1fr; /* 小屏幕下变成一列 */
    }
  }
</style>

<div class="video-grid">
  <!-- 视频 1 -->
  <div class="video-item">
    <video autoplay loop muted playsinline>
      <source src="{{ '/images/homepage/Lsa.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <div class="video-caption">CryoEM structure of <em>Lactobacillus salivarius</em> ROOL RNA hexamer.</div>
  </div>

  <!-- 视频 2 -->
  <div class="video-item">
    <video autoplay loop muted playsinline>
      <source src="{{ '/images/homepage/Efa.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <div class="video-caption">CryoEM structure of <em>Enterococcus faecalis</em> ROOL RNA octamer</div>
  </div>

  <!-- 视频 3 -->
  <div class="video-item">
    <video autoplay loop muted playsinline>
      <source src="{{ '/images/homepage/Cte.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <div class="video-caption">CryoEM structure of <em>Comamonas testosteroni</em> circularly permuted group II intron</div>
  </div>

  <!-- 视频 4 -->
  <div class="video-item">
    <video autoplay loop muted playsinline>
      <source src="{{ '/images/homepage/GOLLD.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <div class="video-caption">CryoEM structure of <em>Streptococcus agalactiae</em> GOLLD RNA dodecamer</div>
  </div>
</div>

Research interests
======

<div class="research-card">
  <h3><a href="{{ '/research/' | relative_url }}">Resolving the 3D structures of bacterial ncRNAs via cryo-EM</a></h3>
  <img src="{{ '/images/homepage/image1.png' | relative_url }}" alt="Resolving the 3D structures of bacteria ncRNAs via cryo-EM">
  <p><strong>RNA structures, multivalency, and catalysis.</strong><br>
  We resolve the three-dimensional structures of bacterial noncoding RNAs via cryo-EM and related biochemical methods:</p>

  <ul class="custom-list">
    <li><strong>Self-splicing ribozymes</strong> —— uncovering the molecular basis of their two-step splicing reaction that produces circular RNAs.</li>
    <li><strong>RNA-only oligomeric assemblies</strong> —— elucidating the structural principles that drive higher-order homo-oligomerization of RNAs.</li>
  </ul>
</div>

<!-- 自定义列表样式 -->
<style>
  .custom-list {
    list-style: none;         /* 去掉默认圆点 */
    padding-left: 1em;        /* 左缩进，避免贴边 */
  }
  .custom-list li {
    position: relative;
    margin: 6px 0;
    padding-left: 1.2em;      /* 给自定义符号留空间 */
  }
  .custom-list li::before {
    content: "·";             /* 自定义符号 */
    position: absolute;
    left: 0;
    color: #444;              /* 符号颜色 */
    font-size: 1.4rem;        /* 符号大小 */
    line-height: 1;
  }
</style>

<div class="research-card">
  <h3><a href="{{ '/research/' | relative_url }}">Discovery of conserved structural RNA elements</a></h3>
  <img src="{{ '/images/homepage/image2.png' | relative_url }}" alt="Discovery of conserved structural RNA elements">
  <p>Comparative genomics, structural RNA elements mining, and experimental validation.</p>
</div>

