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

Hi！I am a second year Master student at University of Electronic Science and Technology of China. My advisor is <a href='https://scholar.google.com/citations?user=-kSTt40AAAAJ&hl=zh-CN'>Shuhang Gu</a>. I received the B.S. degree from the Artificial Intelligence School, Xidian University in 2023.  

My research interest is low-level vision, such as image/video restoration, image enhancement and so on. Specifically, I'm excited about how to build more efficient models, including training and inference, in the field of low-level vision. In addition, I believe that this will ultimately impact the development of the AI community.

**If you have any suggestions for cooperation in the low-level vision, please feel free to contact me.**

# 🔥 News
- *2025.02*: &nbsp;🎉🎉 Our work "Progressive Focused Transformer for Single Image Super-Resolution"(**PFT-SR**) is accepted to CVPR 2025. 
- *2025.02*: &nbsp;🎉🎉 Our work "Learned Image Compression with Dictionary-based Entropy Model"(**DCAE**) is accepted to CVPR 2025. 
- *2024.03*: &nbsp;🎉🎉 Our work "[Video Super-Resolution Transformer with Masked Inter&Intra-Frame Attention](https://arxiv.org/abs/2401.06312)"(**MIA-VSR**) is accepted to CVPR 2024. 
- *2024.03*: &nbsp;🎉🎉 Our work "[Improved Implicit Neural Representation with Fourier Reparameterized Training](https://arxiv.org/abs/2401.07402)"(**FR-INR**) is accepted to CVPR 2024. 
- *2024.03*: &nbsp;🎉🎉 Our work "[Transcending the Limit of Local Window: Advanced Super-Resolution Transformer with Adaptive Token Dictionary](https://arxiv.org/abs/2401.08209)"(**ATD-SR**) is accepted to CVPR 2024. 

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/PFT-arch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Progressive Focused Transformer for Single Image Super-Resolution]()

Wei Long, **Xingyu Zhou**, Leheng Zhang, Shuhang Gu

[**arXiv**]()/[**code**]()/[**bibtex**]()

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/DCAE-arch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learned Image Compression with Dictionary-based Entropy Model]()

Jingbo Lu, Leheng Zhang, **Xingyu Zhou**, Mu Li, Wen Li, Shuhang Gu

[**arXiv**]()/[**code**]()/[**bibtex**]()

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/MIAVSR-arch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video Super-Resolution Transformer with Masked Inter&Intra-Frame Attention](https://arxiv.org/abs/2401.06312)

**Xingyu Zhou**, Leheng Zhang, Xiaorui Zhao, Keze Wang, Leida Li, Shuhang Gu

[**arXiv**](https://arxiv.org/abs/2401.06312)/[**code**](https://github.com/LabShuHangGU/MIA-VSR)/[**bibtex**](https://scholar.googleusercontent.com/scholar.bib?q=info:GDqSW8m7jnEJ:scholar.google.com/&output=citation&scisdr=ClHYdTguEL6GoCAWHiI:AFWwaeYAAAAAZoAQBiJ54W1WSk-Xcc5obth-En0&scisig=AFWwaeYAAAAAZoAQBlqRmjmXhhx2ZZALyJezyrs&scisf=4&ct=citation&cd=-1&hl=zh-CN)

- Focus on the heavy computational burden as well as the large memory footprint hinder the deployment of Transformer-based VSR models. With our proposed masked intra-frame and inter-frame attention block, our MIA-VSR improves the memory and computation efffciency over state-of-the-art methods, without trading off PSNR accuracy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/structure.png' alt="sym" width="65%"></div></div>
<div class='paper-box-text' markdown="1">

[Improved Implicit Neural Representation with Fourier Reparameterized Training](https://arxiv.org/abs/2401.07402)

Kexuan Shi, **Xingyu Zhou**, Shuhang Gu

[**arXiv**](https://arxiv.org/abs/2401.07402)/[**code**](https://github.com/LabShuHangGU/FR-INR)/[**bibtex**](https://scholar.googleusercontent.com/scholar.bib?q=info:cWx-xJ5bQZ4J:scholar.google.com/&output=citation&scisdr=ClHYdTguEL6GoCAJ3hg:AFWwaeYAAAAAZoAPxhjlMTB1Z_90dZ8Q4TdIbD0&scisig=AFWwaeYAAAAAZoAPxkpJWWFG61BY0fTX70JRRl0&scisf=4&ct=citation&cd=-1&hl=zh-CN&scfhb=1)

- Focus on the low-frequency bias issue of vanilla multi-layer perceptron (MLP) in the Implicit Neural Representation (INR). Armed with our Fourier reparameterization method, better INR with more textures and less artifacts can be learned from the training data.  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/arch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Transcending the Limit of Local Window: Advanced Super-Resolution Transformer with Adaptive Token Dictionary](https://arxiv.org/abs/2401.08209)

Leheng Zhang, Yawei Li, **Xingyu Zhou**, Xiaorui Zhao, Shuhang Gu

[**arXiv**](https://arxiv.org/abs/2401.08209)/[**code**](https://github.com/LabShuHangGU/Adaptive-Token-Dictionary)/[**bibtex**](https://scholar.googleusercontent.com/scholar.bib?q=info:WlFazXa9BA8J:scholar.google.com/&output=citation&scisdr=ClHYdTguEL6GoCAWKn0:AFWwaeYAAAAAZoAQMn1YFzmNrUuDsNz-NLV01E0&scisig=AFWwaeYAAAAAZoAQMkyIdMZnb3WhfKykBtqFL_Y&scisf=4&ct=citation&cd=-1&hl=zh-CN)

- Focus on the limited receptive field caused by window-based self-attention in image super-resolution. With introducing a group of auxiliary adaptive token dictionary, our method achieves the best performance on various single image super-resolution benchmarks.
</div>
</div>
