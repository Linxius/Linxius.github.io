---
layout: article
title: Paper Reading
tags: Daily_Paper_Reading
mathjax: true
mathjax_autoNumber: true
---

## AdaNeRF: Adaptive Sampling for Real-time Rendering of Neural Radiance Fields [[ECCV22]](https://arxiv.org/abs/2207.10312)

## NeuMesh: Learning Disentangled Neural Mesh-based Implicit Field for Geometry and Texture Editing [[ECCV22 Oral]](https://github.com/zju3dv/neumesh)

![](/blog/figs/2022-07-31-NeuMesh.png)

1. 训练NeuS用来重建mesh

2. 用来网络蒸馏来训练NeuMesh：
>
Although such vertex-bounded and geometry-texture
disentangled representation merits good flexibility on editing purpose, it does
not preserve spatial continuity as MLP-based methods [27,55,65] and thus easily
suffers from unstable training. To mitigate this problem, we employ a distillation
and fine-tuning training scheme, which leverages a pre-trained implicit field to
guide the optimization of our representation.

3. 训练之后，颜色code和纹理code都在mesh的顶点上

**NeuS** NeurIPS 2021 Spotlight:
[[PDF]](https://arxiv.org/pdf/2106.10689.pdf)
[[Project Page]](https://github.com/Totoro97/NeuS)


## TopoSeg: Topology-aware Segmentation for Point Clouds [[IJCAI-22]](https://www.ijcai.org/proceedings/2022/0168.pdf)
在点云上定义了一个拓扑loss

## NeuralBF: Neural Bilateral Filtering for Top-down Instance Segmentation on Point Clouds [[Arxiv]](https://neuralbf.github.io/)
用语义分割+convex hulls来实例分割。
![](/blog/figs/2022-07-31-NeuralBF.png)