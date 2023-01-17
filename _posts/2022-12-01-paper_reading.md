---
layout: article
title: Paper Index
tags: 
mathjax: true
mathjax_autoNumber: true
---

# Indoor Scene Reconstruction
Approximating shapes in images with low-complexity polygons [[CVPR20]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Approximating_shapes_in_images_with_low-complexity_polygons_CVPR_2020_paper.pdf)
Floorplan generation from 3D point clouds: A space partitioning approach [[ISPRS21]](https://www.sciencedirect.com/science/article/pii/S0924271621000538?ref=pdf_download&fr=RR-2&rr=778c7157dc818095)
Plan2Scene: Converting Floorplans to 3D Scenes [[CVPR21]](https://openaccess.thecvf.com/content/CVPR2021/papers/Vidanapathirana_Plan2Scene_Converting_Floorplans_to_3D_Scenes_CVPR_2021_paper.pdf)
MonteFloor: Extending MCTS for Reconstructing Accurate Large-Scale Floor Plans [[ICCV21]](https://openaccess.thecvf.com/content/ICCV2021/papers/Stekovic_MonteFloor_Extending_MCTS_for_Reconstructing_Accurate_Large-Scale_Floor_Plans_ICCV_2021_paper.pdf)
HEAT: Holistic Edge Attention Transformer for Structured Reconstruction [[CVPR22]](https://github.com/woodfrog/heat)
Connecting the Dots: Floorplan Reconstruction Using Two-Level Queries [[code]](https://github.com/ywyue/RoomFormer)


# Instant-NGP based methods
[instant-ngp](https://github.com/NVlabs/instant-ngp)
[HashNeRF-pytorch](https://github.com/yashbhalgat/HashNeRF-pytorch) This project is a pure PyTorch implementation of Instant-NGP.
[torch-ngp](https://github.com/ashawkey/torch-ngp)
[ngp_pl](https://github.com/kwea123/ngp_pl) Instant-ngp (only NeRF) in pytorch+cuda trained with pytorch-lightning. 比上面的快，比原版的慢。
[JNeRF](https://github.com/Jittor/JNeRF) JNeRF is an NeRF benchmark based on Jittor. JNeRF supports Instant-NGP capable of training NeRF in 5 seconds and achieves similar performance and speed to the paper.
[nerfstudio](https://github.com/nerfstudio-project/nerfstudio)

## OReX: Object Reconstruction from Planner Cross-sections Using Neural Fields [paper](https://arxiv.org/abs/2211.12886)
OReX reconstructs smooth 3D shapes (right) from input planar cross-sections (left).
看着有点意思 不知道有什么用
![](/blog/figs/OReX.png)

## LoopDraw: a Loop-Based Autoregressive Model for Shape Synthesis and Editing [paper](https://arxiv.org/pdf/2212.04981.pdf)
与上面类似

## ActiveRMAP: Radiance Field for Active Mapping And Planning [paper](https://arxiv.org/pdf/2211.12656.pdf)
NeRF做路径规划

## ActiveNeRF: Learning where to See with Uncertainty Estimation [[ECCV22]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930225.pdf)

## NOPE-SAC: Neural One-Plane RANSAC for Sparse-View Planar 3D Reconstruction [code](https://github.com/IceTTTb/NopeSAC)
两张图片检测平面匹配以估计相机位姿

## NeAF: Learning Neural Angle Fields for Point Normal Estimation [paper](https://arxiv.org/pdf/2211.16869.pdf)
预测某个点法向与一些固定方向的query vectors之间的angle offset

## GeoUDF: Surface Reconstruction from 3D Point Clouds via Geometry-guided Distance Representation [code](https://github.com/rsy6318/GeoUDF)

## NeuralUDF: Learning Unsigned Distance Fields for Multi-view Reconstruction of Surfaces with Arbitrary Topologies [[ECCV22]](https://github.com/xxlong0/NeuralUDF)

## Weakly Supervised Semantic Segmentation for Large-Scale Point Cloud [paper](https://arxiv.org/pdf/2212.04744.pdf)
弱监督点云上色做语义分割

## NeuS2: Fast Learning of Neural Implicit Surfaces for Multi-view Reconstruction [[Code (coming soon)]](https://vcai.mpi-inf.mpg.de/projects/NeuS2/)
Instant-NGP 加速了NeuS。做了动态场景的表示，
For every subsequent frame, 
we predict its global transformation with respect to the previous frame and accumulate the transformation to convert it into the
canonical space.

## Real-Time Neural Light Field on Mobile Devices [[page]](https://snap-research.github.io/MobileR2L/)

## VolRecon: Volume Rendering of Signed Ray Distance Functions for Generalizable Multi-View Reconstruction [[page]](https://fangjinhuawang.github.io/VolRecon)
与SparseNeuS对比，训练的数据集上效果好的，泛化性差不多，方法上一般

## Flattening-Net: Deep Regular 2D Representation for 3D Point Cloud Analysis [[Code(comingd)]](https://github.com/keeganhk/Flattening-Net)
an unsupervised deep neural architecture called Flattening-Net to represent irregular 3D point clouds of arbitrary geometry and topology as a completely regular 2D point geometry image (PGI) structure

## Point-E: A System for Generating 3D Point Clouds from Complex Prompts [code](https://github.com/openai/point-e)