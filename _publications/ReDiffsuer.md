---
title: "ReGeneration Learning of Diffusion Models with Rich Prompts for Zero-Shot Image Translation"
collection: publications
permalink: /publication/ReDiffuser
---

<p align="center"> $\text{Yupei Lin}^{1}$, $\text{Sen Zhang}^2$, $\text{Xiaojun Yang}^1$, $\text{Xiao Wang}^3$,  $\text{Yukai Shi}^{1*}$ 
 
<p align="center"> ${}^1$ Guangdong University of Technology, ${}^2$ The University of Sydney, ${ }^3$ Anhui University
 <p align="center"> *: Corresponding author
 <p>
  

![show_res](/images/poject/ReDiffuser/show_res.jpg)
## Abstract

<p>Large-scale text-to-image models have demonstrated amazing ability to synthesize diverse and high-fidelity images. However, these models are often violated by several limitations. Firstly, they require the user to provide precise and contextually relevant descriptions for the desired image modifications. Secondly, current models can impose significant changes to the original image content during the editing process. In this paper, we explore ReGeneration learning in an image-to-image Diffusion model (ReDiffuser), that preserves the content of the original image without human prompting and the requisite editing direction is automatically discovered within the text embedding space. To ensure consistent preservation of the shape during image editing, we propose cross-attention guidance based on regeneration learning. This novel approach allows for enhanced expression of the target domain features, while preserving the original shape of the image. In addition, we introduce a cooperative update strategy, which allows for efficient preservation of the original shape of an image, thereby improving the quality and consistency of shape preservation throughout the editing process. Our proposed method leverages an existing pre-trained text-image diffusion model without any additional training. Extensive experiments show that the proposed method outperforms existing work in both real and synthetic image editing.</p>

## Pipeline
![framework](/images/poject/ReDiffuser/framework.svg)

## Dataset
- **Cat(C2D-F and C2G-F)**: [*Coming Soon*]()
- **Horse(H2Z-F)**: [*Coming Soon*]()
- **Sketch(S2O-F)**: [*Coming Soon*]()

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
