---
layout: article
title: Paper Reading
tags: Daily_Paper_Reading Reconstuction View-Selection
mathjax: true
mathjax_autoNumber: true
---

[Efficient View Clustering and Selection for City-Scale 3D Reconstruction](https://arxiv.org/pdf/2207.08434v1.pdf), International Conference on Image Analysis and Processing. Springer, Cham, 2022.

![](/blog/figs/1.png)

View clustering: 在针对大规模场景的MVS重建中，视角被有重叠地聚类并分别重建和合并为一个场景。

View selection: 已经拍好的照片中选出重要的用于重建。
[[ref]](http://varcity.ethz.ch/paper/bmvc2014_mauro_nextbestview.pdf)

这篇文章采用的Selection中：
>
*optimal* means the smallest subset of cameras that guarantees that each point in the cluster is seen by at least $N_{vis}$ cameras and each camera have at least $N_{match}$ other cameras to be successfully matched with.

其中：
>
Two cameras are considered to be matchable if they see a sufficient number of
common points. This differs from previous literature, where the typical similarity
measure is the average Gaussian-weighted triangulation angle between the two
camera centers and the common keypoints[[5](https://www.microsoft.com/en-us/research/wp-content/uploads/2010/06/Furukawa-CVPR10.pdf), [9](https://varcity.hayko.at/paper/3dv2014_mauro_joint_selection_clustering.pdf)]

然后解一个Integer Linear Programming (ILP) 整数线性规划问题。

这个CVPR10 [Towards Internet-scale Multi-view Stereo](https://www.microsoft.com/en-us/research/wp-content/uploads/2010/06/Furukawa-CVPR10.pdf)
中给了一个两个图片MVS重建一个点准确度的衡量：
![](/blog/figs/2022-07-31-acc.png)