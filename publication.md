---
layout: page
title: 
subtitle: Publications
---

<style>
  /* Custom style for highlighted font (for your name) */
  .highlight-author {
/*     font-family: 'Arial', sans-serif; /* Example font, you can change it to any font */ */
    font-weight: bold;
    color: #9E7BB5; /* Set your highlight color (you can choose any color) */
    font-size: 16px; /* Set the font size */
  }

  /* Custom styles for publications */
  .publication {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
    padding: 20px;
    border-bottom: 1px solid #ddd;
    width: 90%;
    margin: 0 auto;
  }

  .publication .left-column {
    width: 30%;
    margin-right: 20px;
  }

  .publication .right-column {
    width: 70%;
  }

  .publication img {
    max-width: 100%;
    border-radius: 8px;
  }

  /* Custom font size and style for h2 */
  .publication h2 {
    font-size: 18px;
/*     font-family: 'Arial', sans-serif; */
    font-weight: bold;
    color: #333;
  }

  /* Custom font size and style for p */
  .publication p {
    font-size: 16px;
/*     font-family: 'Georgia', serif; */
    line-height: 1.6;
    color: #666;
  }

  /* Optional: You can add specific styles for links */
  .publication a {
    text-decoration: none;
    color: #0066cc;
  }

  .publication a:hover {
    text-decoration: underline;
  }
</style>

<div class="publication">
  <div class="left-column">
    <img src="https://markomih.github.io/assets/SplatFormer_ood_overview.png" alt="SplatFormer" class="publication-image">
  </div>
  <div class="right-column">
    <h2><strong>SplatFormer: Point Transformer for Robust 3D Gaussian Splatting</strong></h2>
    <p><a class="highlight-author">Yutong Chen</a>, Marko Mihajlovic, Xiyi Chen, Yiming Wang, Sergey Prokudin, and Siyu Tang.</p>
    <p>ICLR 2025 Spotlight.</p>
    <p>
      <a href="https://sergeyprokudin.github.io/splatformer/" target="_blank">Project page</a> | 
      <a href="https://arxiv.org/abs/2411.06390" target="_blank">arXiv</a> | 
      <a href="https://github.com/ChenYutongTHU/SplatFormer" target="_blank">Code</a>
    </p>
  </div>
</div>
