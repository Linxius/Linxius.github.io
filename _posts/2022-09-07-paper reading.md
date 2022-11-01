---
layout: article
title: Paper Reading
tags: Daily_Paper_Reading 2022-09 
mathjax: true
mathjax_autoNumber: true
---

## Iterative Poisson Surface Reconstruction (iPSR) for Unoriented Points [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3528223.3530096) [[code]](https://github.com/houfei0801/ipsr)
![](/blog/figs/2022-09-07-iPSR.png)
迭代泊松重建和调整输入点的法线

## SimpleRecon: 3D Reconstruction Without 3D Convolutions [[PDF]](https://arxiv.org/pdf/2208.14743.pdf) [[code]](https://nianticlabs.github.io/simplerecon)
对带位姿的图片估计深度来三维重建，cost volume中除了图片特征，还引入位姿和方向等。
```allows for online real-time low-memory reconstruction```

## Deconstructing Self-Supervised Monocular Reconstruction: The Design Decisions that Matter [[PDF]](https://arxiv.org/pdf/2208.01489.pdf)
提出修正的单目深度估计数据集并对之前的方法重新评估对比

## NICE-SLAM: Neural Implicit Scalable Encoding for SLAM [[PDF]](https://arxiv.org/pdf/2112.12130.pdf) [[Project]](https://pengsongyou.github.io/nice-slam)
![](/blog/figs/2022-09-nice%20slam.png)
以渲染的深度图、颜色图来优化场景表示, 同时优化相机位姿。

## Learning to Generate Realistic LiDAR Point Clouds [[ECCV22]](https://arxiv.org/pdf/2209.03954.pdf)
竟然还有这种研究怎么生成lidar点云的文章。。
还有[IROS22](https://arxiv.org/abs/2209.10986)

## Polarimetric Inverse Rendering for Transparent Shapes Reconstruction [[code]](https://github.com/shaomq2187/TransPIR)

## Neural 3D Reconstruction in the Wild [[SIGGRAPH 2022]](https://zju3dv.github.io/neuralrecon-w/)
隐式场重建的工作还有：[UNISURF ICCV21](https://openaccess.thecvf.com/content/ICCV2021/papers/Oechsle_UNISURF_Unifying_Neural_Implicit_Surfaces_and_Radiance_Fields_for_Multi-View_ICCV_2021_paper.pdf), [NeuS](https://github.com/Totoro97/NeuS), [VolSDF NIPS21](https://proceedings.neurips.cc/paper/2021/hash/25e2a30f44898b9f3e978b1786dcd85c-Abstract.html)

## Mega-NeRF: Scalable Construction of Large-Scale NeRFs for Virtual Fly-Throughs [CVPR22](https://meganerf.cmusatyalab.org/)
NeRF的分块

## BungeeNeRF: Progressive Neural Radiance Field for Extreme Multi-scale Scene Rendering [ECCV22](https://neuralfields.cs.brown.edu/paper_280.html)
![](/blog/figs/BungeeNeRF.png)

## Multi-View Reconstruction using Signed Ray Distance Functions [[PDF]](https://arxiv.org/pdf/2209.00082.pdf)
![](/blog/figs/SRDF.png)

## ZeroMesh: Zero-shot Single-view 3D Mesh Reconstruction [[PDF]](https://arxiv.org/pdf/2208.02676.pdf)
![](/blog/figs/zeromesh.png)

## MobileNeRF: Exploiting the Polygon Rasterization Pipeline for Efficient Neural Field Rendering on Mobile Architectures 
利用传统渲染管线快速渲染NeRF [[Project Page]](https://mobile-nerf.github.io/)

同样地：Baking Neural Radiance Fields for Real-Time View Synthesis [[ICCV21]](https://phog.github.io/snerg/)


## Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time [[CVPR22]](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Fourier_PlenOctrees_for_Dynamic_Radiance_Field_Rendering_in_Real-Time_CVPR_2022_paper.pdf)


## Urban Radiance Fields [[CVPR22]](https://urban-radiance-fields.github.io/)

## NPBG++: Accelerating Neural Point-Based Graphics [[CVPR22]](https://openaccess.thecvf.com/content/CVPR2022/papers/Rakhimov_NPBG_Accelerating_Neural_Point-Based_Graphics_CVPR_2022_paper.pdf)

## Instant Neural Graphics Primitives [](https://github.com/NVlabs/instant-ngp)
[](https://github.com/NVlabs/tiny-cuda-nn)

## PlenOctrees for Real-time Rendering of Neural Radiance Fields

## Stochastic Poisson Surface Reconstruction (https://arxiv.org/abs/2206.15236v2)
