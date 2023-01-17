---
layout: article
title: Paper Index
tags: 
mathjax: true
mathjax_autoNumber: true
---

[[UrbanScene3D ECCV22]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/3218_ECCV_2022_paper.php)

## Semi-Supervised Single-View 3D Reconstruction via Prototype Shape Priors [[ECCV22]](https://arxiv.org/pdf/2209.15383.pdf)

## Point Normal Orientation and Surface Reconstruction by Incorporating Isovalue Constraints to Poisson Equation (https://arxiv.org/pdf/2209.15619.pdf)

## City-scale Incremental Neural Mapping with Three-layer Sampling and Panoptic Representation (https://arxiv.org/pdf/2209.14072.pdf)

## NeuralMeshing: Differentiable Meshing of Implicit Neural Representations (https://arxiv.org/pdf/2210.02382.pdf)

## SHINE-Mapping: Large-Scale 3D Mapping Using Sparse Hierarchical Implicit Neural Representations (https://arxiv.org/pdf/2210.02299.pdf)

## Learning A Unified 3D Point Cloud for View Synthesis (https://arxiv.org/pdf/2209.05013.pdf)
深度图得到点云来生成新视角，可以参考PointNeRF

## *Neural Density-Distance Fields* [[ECCV22]](https://github.com/ueda0319/neddf)
enable explicit conversion from distance field to density field

## *HF-NeuS: Improved Surface Reconstruction Using High-Frequency Details* [[NeurIPS 2022]](https://arxiv.org/pdf/2206.07850.pdf)
we offer a derivation to analyze the relationship between the SDF, the volume density, the transparency function, and the weighting function used in the volume rendering equation and propose to model transparency as transformed SDF

## Is Attention All NeRF Needs? (https://vita-group.github.io/GNT/)
successfully reconstruct NeRF without explicit rendering formula

## NEUFORM: Adaptive Overfitting for Neural Shape Editing (https://arxiv.org/abs/2207.08890)
blends between a generalizable neural shape representation and an overfitted neural shape representation by interpolating their network weights and some feature layers.

## Aug-NeRF: Training Stronger Neural Radiance Fields with Triple-Level Physically-Grounded Augmentations [[CVPR22]](https://arxiv.org/pdf/2207.01164.pdf)
NeRF的数据增强

## Learning Consistency-Aware Unsigned Distance Functions Progressively from Raw Point Clouds [[NeurIPS 2022]](https://junshengzhou.github.io/CAP-UDF/)

## Latent Partition Implicit with Surface Codes for 3D Representation [[ECCV 2022]](https://github.com/chenchao15/LPI)

## PU-Flow: a Point Cloud Upsampling Network with Normalizing Flows [[TVCG22]](https://github.com/unknownue/puflow)
在特征空间中加权得到新的点特征，通过网络回传得到欧氏空间中的点，从而实现上采样。

## NeRF-Editing: Geometry Editing of Neural Radiance Fields [[CVPR22]](https://openaccess.thecvf.com/content/CVPR2022/papers/Yuan_NeRF-Editing_Geometry_Editing_of_Neural_Radiance_Fields_CVPR_2022_paper.pdf)
通过修改x点的映射得到变形的NeRF

## 3D Neurals Sculpting (3DNS): Editing Neural Distance Functions (https://github.com/pettza/3DNS)
通过修改采样点后重新训练？来变形SDF场 方法似乎trivial

## Deformed Implicit Field: Modeling 3D Shapes with Learned Dense Correspondence [[CVPR21](https://openaccess.thecvf.com/content/CVPR2021/papers/Deng_Deformed_Implicit_Field_Modeling_3D_Shapes_With_Learned_Dense_Correspondence_CVPR_2021_paper.pdf)
一个形状的SDF场由这个类别的SDF场模板和一个形变场得到

## ZeroMesh: Zero-shot Single-view 3D Mesh Reconstruction (https://arxiv.org/pdf/2208.02676.pdf)
图片->点云->mesh->微分渲染剪影

## Surface Reconstruction from Point Clouds without Normals by Parametrizing the Gauss Formula [[TOG22]](https://github.com/jsnln/ParametricGaussRecon)

## *VOXURF: VOXEL-BASED EFFICIENT AND ACCURATE NEURAL SURFACE RECONSTRUCTION* (https://wutong16.github.io/publication/10_arxiv_voxurf/)

## *Vox-Surf: Voxel-based Implicit Surface Representation* (https://arxiv.org/pdf/2208.10925.pdf)

## NEURAL VOLUMETRIC MESH GENERATOR (https://arxiv.org/pdf/2210.03158.pdf)
用diffusion model生成体素模型

## 3D Reconstruction of Sculptures from Single Images via Unsupervised Domain Adaptation on Implicit Models (https://arxiv.org/pdf/2210.04265.pdf)
propose our unsupervised 3D domain adaptation method for adapting a single-view 3D implicit reconstruction model from the source (real-world humans) to the target (sculptures) domain.

## Neural Mesh Flow: 3D Manifold Mesh Generation via Diffeomorphic Flows [[NIPS20]](https://kunalmgupta.github.io/projects/NeuralMeshflow.html)

## POCO: Point Convolution for Surface Reconstruction [[CVPR22]](https://github.com/valeoai/POCO)
把输入点云特征通过学习的权重插值到网格顶点上

## DiGS: Divergence guided shape implicit neural representation for unoriented point clouds [[CVPR22]](https://chumbyte.github.io/DiGS-Site/)

## Neural Fields as Learnable Kernels for 3D Reconstruction [[CVPR22]](https://nv-tlabs.github.io/nkf)
点云重建

## X-NeRF: Explicit Neural Radiance Field for Multi-Scene 360° Insufficient RGB-D Views (https://github.com/HaoyiZhu/XNeRF)
从RGB-D点云直接拟合补全之后的NeRF

## MonoSDF Exploring Monocular Geometric Cues for Neural Implicit Surface Reconstruction [[NeurIPS 2022]](https://niujinshuchong.github.io/monosdf/)

## DSAC – Differentiable RANSAC for Camera Localization[[CVPR17]](https://github.com/cvlab-dresden/dsac)

## Eikonal Fields for Refractive Novel-View Synthesis [[SIG22]](https://arxiv.org/pdf/2202.00948.pdf)

## PointNeXt: Revisiting PointNet++ with Improved Training and Scaling Strategies [[NeurIPS'22]](https://github.com/guochengqian/PointNeXt)

## Neural 3D Scene Reconstruction with the Manhattan-world Assumption [[CVPR 2022]](https://github.com/zju3dv/manhattan_sdf)

## Fusion 360 Gallery Dataset (https://github.com/AutodeskAILab/Fusion360GalleryDataset)

## Neural Points: Point Cloud Representation with Neural Fields for Arbitrary Upsampling [[CVPR22]](https://github.com/WanquanF/NeuralPoints)

## NeuralRoom: Geometry-Constrained Neural Implicit Surfaces for Indoor Scene Reconstruction (https://arxiv.org/pdf/2210.06853.pdf)

## MonoNeuralFusion: Online Monocular Neural 3D Reconstruction with Geometric Priors (https://arxiv.org/pdf/2209.15153.pdf)

## *MVSNeRF: Fast Generalizable Radiance Field Reconstruction from Multi-View Stereo* [[ICCV21]](https://github.com/apchenstu/mvsnerf)

## Zero-shot Point Cloud Segmentation by Transferring Geometric Primitives (https://arxiv.org/pdf/2210.09923.pdf)

## *Direct Voxel Grid Optimization: Super-fast Convergence for Radiance Fields Reconstruction* [[]]

## Efficient Point Cloud Analysis Using Hilbert Curve [[ECCV22]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136620717.pdf)

## Learning Neural Radiance Fields from Multi-View Geometry (https://arxiv.org/pdf/2210.13041.pdf)
同时加上MVS的几何作为NeRF几何的约束

## Learning to Train a Point Cloud Reconstruction Network without Matching [[ECCV22]](https://github.com/Tianxinhuang/PCLossNet)

## Box2Mask: Weakly Supervised 3D Semantic Instance Segmentation Using Bounding Boxes [[ECCV22]](https://virtualhumans.mpi-inf.mpg.de/box2mask/)

## Compressing Explicit Voxel Grid Representations: fast NeRFs become also small [[WACV22]](https://arxiv.org/pdf/2210.12782.pdf)
测试删除参数对网络结果的影响来减小网络

## NeRF-SLAM: Real-Time Dense Monocular SLAM with Neural Radiance Fields (https://arxiv.org/pdf/2210.13641.pdf)
用NeRF做SLAM 没啥意思

## Reconstructing Training Data from Trained Neural Networks [[NeuIPS22]](https://github.com/nivha/dataset_reconstruction)
in some cases a significant fraction of the training data can in fact be reconstructed from the parameters of a trained neural network classifier.

## Directed Ray Distance Functions for 3D Scene Reconstruction [[ECCV22]](https://nileshkulkarni.github.io/scene_drdf/)

## PlaneFormers: From Sparse View Planes to 3D Reconstruction [[ECCV22]](https://github.com/samiragarwala/PlaneFormers)

## Surface Reconstruction from Point Clouds by Learning Predictive Context Priors [[CVPR22]](https://github.com/mabaorui/PredictableContextPrior)

## Reconstructing Surfaces for Sparse Point Clouds with On-Surface Priors [[CVPR 2022]](https://github.com/mabaorui/OnSurfacePrior)

## State of the Art in Dense Monocular Non-Rigid 3D Reconstruction (https://arxiv.org/pdf/2210.15664.pdf)

## NeRFusion: Fusing Radiance Fields for Large-Scale Scene Reconstruction [[CVPR22]](https://jetd1.github.io/NeRFusion-Web/)
前面有点像NeuralRecon。图片生成局部体素混合进全局体素

## SDFDiff: Differentiable Rendering of Signed Distance Fields for 3D Shape Optimization [[CVPR22]](https://github.com/YueJiang-nj/CVPR2020-SDFDiff)

## Differentiable Signed Distance Function Rendering [[SIGGRAPH22]](https://github.com/rgl-epfl/differentiable-sdf-rendering)

## Differentiable Transient Rendering [[SIGGRAPH22]](https://dl.acm.org/doi/pdf/10.1145/3478513.3480498)

## DeepCurrents: Learning Implicit Representations of Shapes with Boundaries [[CVPR22]](https://openaccess.thecvf.com/content/CVPR2022/papers/Palmer_DeepCurrents_Learning_Implicit_Representations_of_Shapes_With_Boundaries_CVPR_2022_paper.pdf)
一种显式边界曲线和隐式内部曲面的表示，不知道有什么用。。

