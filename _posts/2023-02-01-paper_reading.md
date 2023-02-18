---
layout: article
title: Paper Index
tags: 
mathjax: true
mathjax_autoNumber: true
---

## PPGeo: Policy Pre-training for Autonomous Driving via Self-supervised Geometric Modeling [[ICLR23]](https://github.com/OpenDriveLab/PPGeo)

## A Survey and Benchmark of Automatic Surface Reconstruction from Point Clouds [[arxiv]](https://arxiv.org/pdf/2301.13656.pdf)

## Switch-NeRF: Learning Scene Decomposition with Mixture of Experts for Large-scale Neural Radiance Fields [[ICLR23]](https://openreview.net/pdf?id=PQ2zoIZqvm)
训练大场景NeRF，使用可微的方式分割场景
![](/blog/figs/Switch-NeRF.png)

## SE(3)-EQUIVARIANT ATTENTION NETWORKS FOR SHAPE RECONSTRUCTION IN FUNCTION SPACE [[ICLR23]](https://openreview.net/pdf?id=RDy3IbvjMqT)
We show that by training only on single, aligned objects
and without any pre-segmentation, we can reconstruct novel scenes containing
arbitrarily many objects in random poses without any performance loss.

## NEURAL RADIANCE FIELD CODEBOOKS
引入一个Variation Module得到codebook中code的变化
$$CODE_{new} = CODE_{old} + \epsilon \frac{MLP(CODE_{old},Feature)}{||MLP(CODE_{old},Feature)||_2}$$
![](/blog/figs/neural%20radiance%20field%20codebooks.png)

## VOXURF: VOXEL-BASED EFFICIENT AND ACCURATE NEURAL SURFACE RECONSTRUCTION [[ICLR23]](https://openreview.net/pdf?id=DSy8tP4WctmZ)
the straightforward combination of DVGO
and NeuS produces continuous but noisy surfaces; our method achieves around 20x speedup than NeuS and
recovers high-quality surfaces and images with fine details.

## Factor Fields: A Unified Framework for Neural Fields and Beyond [[arxiv]](https://arxiv.org/pdf/2302.01226.pdf)

## vMAP: Vectorised Object Mapping for Neural Field SLAM [[arxiv]](https://arxiv.org/pdf/2302.01838.pdf)

## Moving Level-of-Detail Surfaces [[SIG22]](https://github.com/CorentinMercier/MlodSurfaces)

## NeuRIS: Neural Reconstruction of Indoor Scenes Using Normal Priors [[code]](https://github.com/jiepengwang/NeuRIS)
>Only those normal priors whose resulting corresponding geometry passes the photometric-consistency
test will be considered reliable and are used for supervision in the following optimization steps. 

>A key observation is that the above volume rendering scheme can generate not only appearance, but also geometric properties
such as depth and normal vectors. That is, we can approximate the surface normal and depth observed from a viewpoint using the volume accumulation.