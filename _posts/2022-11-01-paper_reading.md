---
layout: article
title: Paper Index
tags: 
mathjax: true
mathjax_autoNumber: true
---

# Survey

## Advances in Neural Rendering [[link]](https://onlinelibrary.wiley.com/doi/epdf/10.1111/cgf.14507)

## Neural Fields in Visual Computing and Beyond [[link]](https://onlinelibrary.wiley.com/doi/epdf/10.1111/cgf.14506)

# SDF的不同替代

## Neural unsigned distance fields for implicit function learning [[NIPS20]](https://proceedings.neurips.cc/paper/2020/file/f69e505b08403ad2298b9f262659929a-Paper.pdf)

## Neural-Pull: Learning Signed Distance Functions from Point Clouds by Learning to Pull Space onto Surfaces [[ICML21]](https://github.com/mabaorui/NeuralPull-Pytorch)
学query点到点云最近点的距离

## Deep Implicit Surface Point Prediction Networks [[ICCV21]](https://sites.google.com/view/cspnet)
SDF，UDF的替代，学习输入点在surface上的最近点

## Representing 3D Shapes with Probabilistic Directed Distance Fields [[CVPR22]](https://openaccess.thecvf.com/content/CVPR2022/papers/Aumentado-Armstrong_Representing_3D_Shapes_With_Probabilistic_Directed_Distance_Fields_CVPR_2022_paper.pdf)
给定点和方向，直接预测可见性和到surface的距离，没给代码

## Learning Consistency-Aware Unsigned Distance Functions Progressively from Raw Point Clouds [[NIPS22]](https://junshengzhou.github.io/CAP-UDF)
Neural-Pull改了个loss

## 3PSDF: Three-Pole Signed Distance Function for Learning Surfaces with Arbitrary Topologies [[CVPR22]](http://chenweikai.github.io/projects/proj_cvpr22_3psdf.html)
八叉树结构，没有surface的体素距离为NAN，有的则在体素内部用SDF表示

## GIFS: Neural Implicit Function for General Shape Representation [[CVPR22]](https://jianglongye.com/gifs)
用空间中两个query点之间是否穿过surface来表达，怀疑效果

#

## Differentiable Point-Based Radiance Fields for Efficient View Synthesis [[SIGGRAPHaisa22]](https://arxiv.org/pdf/2205.14330.pdf)

## ADOP: Approximate Differentiable One-Pixel Point Rendering [[TOG22]](https://github.com/darglein/ADOP)

# 

## A Level Set Theory for Neural Implicit Evolution under Explicit Flows [[ECCV22]](https://arxiv.org/pdf/2204.07159.pdf)

## ParticleNeRF: Particle Based Encoding for Online Neural Radiance Fields in Dynamic Scenes [](https://arxiv.org/pdf/2211.04041.pdf)
用带有特征的运动粒子来做动态场景NeRF

## Differentiable Surface Rendering via Non-Differentiable Sampling [[ICCV21]](https://openaccess.thecvf.com/content/ICCV2021/papers/Cole_Differentiable_Surface_Rendering_via_Non-Differentiable_Sampling_ICCV_2021_paper.pdf)
a method for differentiable rendering of 3D surfaces that supports both explicit and implicit representations.

## Recovering Fine Details for Neural Implicit Surface Reconstruction [[link]](https://arxiv.org/pdf/2211.11320.pdf)

