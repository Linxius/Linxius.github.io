---
layout: article
title: Paper Reading
tags: Daily_Paper_Reading
mathjax: true
mathjax_autoNumber: true
---

## Vis2Mesh: Efficient Mesh Reconstruction from Unstructured Point Clouds of Large Scenes with Learned Virtual View Visibility [[ICCV21]](https://openaccess.thecvf.com/content/ICCV2021/papers/Song_Vis2Mesh_Efficient_Mesh_Reconstruction_From_Unstructured_Point_Clouds_of_Large_ICCV_2021_paper.pdf)

![](/blog/figs/2022-07-30-vis2mesh.png)

用gt深度图作为监督，学习随机生成的虚拟视角到输入点云的可见性（先以深度图的形式），以此来进行点云重建。

## Next-Best View Policy for 3D Reconstruction [[ECCV20]](https://www.researchgate.net/profile/Rowel-Atienza/publication/343986769_Next-Best_View_Policy_for_3D_Reconstruction/links/60a8c49aa6fdcc6d6266d74c/Next-Best-View-Policy-for-3D-Reconstruction.pdf)
强化学习的NBV

## ShAPO: Implicit Representations for Multi-Object Shape, Appearance, and Pose Optimization [[ECCV22]](https://arxiv.org/pdf/2207.13691.pdf)


## Gradient-based Point Cloud Denoising with Uniformity [[arxiv]](https://arxiv.org/pdf/2207.10279.pdf)
沿预测的法向移动点来去噪。引入均匀性的用法解释不合理

## SeedFormer: Patch Seeds based Point Cloud Completion with Upsample Transformer [[ECCV22]](https://arxiv.org/pdf/2207.10315.pdf)

## Cross-Modal 3D Shape Generation and Manipulation [[ECCV]](https://arxiv.org/pdf/2207.11795.pdf)
一个latent space后连接不同模态，通过改变共同latent space中的latent code实现跨模态操作和生成

## Rethinking Sim2Real: Lower Fidelity Simulation Leads to Higher Sim2Real Transfer in Navigation [[arxiv]](https://arxiv.org/abs/2207.10821)