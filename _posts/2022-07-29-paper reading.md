---
layout: article
title: Paper Reading
tags: Daily_Paper_Reading
mathjax: true
mathjax_autoNumber: true
---


## pixelNeRF: pixelNeRF: Neural Radiance Fields from One or Few Images [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yu_pixelNeRF_Neural_Radiance_Fields_From_One_or_Few_Images_CVPR_2021_paper.pdf)
学习场景先验信息的NeRF
![](/blog/figs/2022-07-29-pixelnerf.png)

将输入图片也作为新视角合成的推断条件，而非仅仅是新视角的位姿，解决使用cost volume只能针对单个场景且需要优化的问题。

## Depth Field Networks for Generalizable Multi-view Scene Representation [[ECCV22]](https://arxiv.org/pdf/2207.14287.pdf)
这篇文章把相机位姿傅里叶变换之后作为网络的输入，可以参考。

[Perceiver IO](http://proceedings.mlr.press/v139/jaegle21a.html) 解决Transformer: the quadratic scaling of self-attention with input size.

## GAUDI: A Neural Architect for Immersive 3D Scene Generation [[Arxiv]](https://arxiv.org/pdf/2207.13751.pdf)
[[Porjecte page]](https://github.com/apple/ml-gaudi)
采样场景和轨迹两个latents来生成一段漫游场景的视频。
