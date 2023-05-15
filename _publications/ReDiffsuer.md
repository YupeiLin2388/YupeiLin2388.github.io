---
title: "ReGeneration Learning of Diffusion Models with Rich Prompts for Zero-Shot Image Translation"
collection: publications
permalink: /publication/ReDiffuser
---

<p align='center'> <a href="https://yupeilin2388.github.io/">Yupei Lin</a> $^{1}$, <a href="https://github.com/SenZHANG-GitHub">Sen Zhang</a> $^2$,  <a href="https://yzw.gdut.edu.cn/info/1118/2032.htm">Xiaojun Yang</a> $^1$,  <a href="https://wangxiao5791509.github.io">Xiao Wang</a> $^3$,   <a href="https://ykshi.github.io/">Yukai Shi</a> $^{1*}$  </p> 
<p align='center'> ${}^1$ Guangdong University of Technology, ${}^2$ The University of Sydney, ${ }^3$ Anhui University </p>
  
![show_res](/images/poject/ReDiffuser/show_res.jpg)
  
## Abstract

<p>Large-scale text-to-image models have demonstrated amazing ability to synthesize diverse and high-fidelity images. However, these models are often violated by several limitations. Firstly, they require the user to provide precise and contextually relevant descriptions for the desired image modifications. Secondly, current models can impose significant changes to the original image content during the editing process. In this paper, we explore ReGeneration learning in an image-to-image Diffusion model (ReDiffuser), that preserves the content of the original image without human prompting and the requisite editing direction is automatically discovered within the text embedding space. To ensure consistent preservation of the shape during image editing, we propose cross-attention guidance based on regeneration learning. This novel approach allows for enhanced expression of the target domain features, while preserving the original shape of the image. In addition, we introduce a cooperative update strategy, which allows for efficient preservation of the original shape of an image, thereby improving the quality and consistency of shape preservation throughout the editing process. Our proposed method leverages an existing pre-trained text-image diffusion model without any additional training. Extensive experiments show that the proposed method outperforms existing work in both real and synthetic image editing.</p>

## Pipeline
![framework](/images/poject/ReDiffuser/framework.svg)

## Dataset
- **Cat(C2D-F and C2G-F)**: [*Google drive*](https://drive.google.com/file/d/1q9PEfJYxYWhOdJloto0QuUg-bLUICh3_/view?usp=share_link)
- **Horse(H2Z-F)**: [*Google drive*](https://drive.google.com/file/d/1LbAvRr1CvTu1GLXuk0Y2chYEsq0E3IQs/view?usp=share_link)
- **Sketch(S2O-F)**: [*Google drive*](https://drive.google.com/file/d/1iw440bF-G0NZjOTrew1KjbS-SYkE1Wce/view?usp=share_link)

## Generated  Results
![exp_res](/images/poject/ReDiffuser/exp_res.jpg)
## Qualitative Results
![exp_table](/images/poject/ReDiffuser/exp_table.PNG)

## Additional results
### Cat to Dog-Free
![add_cat](/images/poject/ReDiffuser/add_cat.jpg)
### Horse to Zebra-Free
![add_horse](/images/poject/ReDiffuser/add_horse.jpg)
### Cat Add Glasses
![add_cat_wg](/images/poject/ReDiffuser/cat_wg.jpg)
### Sketch to Oil-Free
![add_sketch](/images/poject/ReDiffuser/add_sketch.jpg)
