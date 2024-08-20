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

# 🌱 About Me

Currently I am an incoming M.Sc student at [Imperial College London](https://www.imperial.ac.uk/), majoring in Applied Computational Science and Engineering. I hold a B.Eng degree in Software Engineering from [Tongji University](https://www.tongji.edu.cn/). During my undergraduate studies, I had the opportunity to work as a research intern in the [Representation Learning Lab](https://github.com/westlake-repl) at Westlake University, supervised by Prof. [Fajie Yuan](https://fajieyuan.github.io/). My research interest includes Large Language Model and Computer Vision.

I am actively seeking a PhD position starting in Fall 2025, please feel free to send me an email! Please find my CV [here]().

<!--

# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->



# 📝 Publications 

## [SaprotHub: Making Protein Modeling Accessible to All Biologists](https://www.biorxiv.org/content/10.1101/2024.05.24.595648v3)
*Jin Su, **Zhikai Li**, Chenchen Han, Yuyang Zhou, Yan He, Junjie Shan, Xibin Zhou, Xing Chang, Dacheng Ma, The OPMC, Martin Steinegger, Sergey Ovchinnikov, Fajie Yuan*

- Developed ColabSaprot and SaprotHub to support scientific research, allowing biologists to easily train and use Protein Language Models. SaprotHub is widely used for protein-related tasks, with wet lab experiments validating its results.




# 🖥️ Project

## Zero-Shot Sketch-based 3D Model Retrieval based on CLIP
*Undergraduate thesis at Tongji University, supervised by Prof. [Shuang Liang](https://sse.tongji.edu.cn/info/1211/3213.htm)*

- Using a sketch to retrieve the most relevant 3D model is both intuitive and efficient. However, traditional methods are limited by model performance and dataset quality, making it difficult to generalize to unseen categories. To address this, this work proposes leveraging CLIP's strong generalization capabilities in the field of 3D model sketch retrieval and further enhances the model's zero-shot retrieval performance through improvements in fine-tuning methods and loss functions.



## Protein Search base on ESM Protein Language Model

*Developer, supervised by Prof. [Fajie Yuan](https://fajieyuan.github.io/)*

- In biological studies, when a certain class of proteins is found to have desirable properties, we seek to identify other proteins within the same class. Due to the high cost of validating protein properties through wet lab experiments, we intend to first use ESM (a Transformer-based protein language model) to retrieve the most likely target proteins.



## Protein-Molecule Pair Prediction base on pre-trained LLMs

*Developer, supervised by Prof. [Fajie Yuan](https://fajieyuan.github.io/)*

- Proteins and molecules may have valuable relationships, such as enzymes and substrates in catalytic reactions. The goal of this work is to identify potential protein-molecule pairs with possible relationships by leveraging the representation extraction capabilities of protein(ESM) and molecule(ChemBERTa) language models.




# 🎖 Honors and Awards
- Third-class Scholarship for Outstanding Student at Tongji University (2020)



# 📖 Educations
- *2024.09 - 2025.09*, M.Sc in Applied Computational Science and Engineering, **Imperial College London**, London, UK. 
- *2020.09 - 2024.07*, B.Eng in Software Engineering (Machine Intelligence Track), **Tongji University**, Shanghai, China. 



<!--

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->



# 💻 Internships
- *2023.10 - 2024.09*, Undergraduate Visiting Student, [Representation Learning Lab at Westlake University](https://github.com/westlake-repl), Hangzhou, China.