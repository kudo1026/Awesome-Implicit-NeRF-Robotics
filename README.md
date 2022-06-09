# Awesome-Implicit-NeRF-Robotics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repo contains a curative list of **Implicit Representations and NeRF papers relating to Robotics/RL domain**, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) <br>

#### Please feel free to send me [pull requests](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics/blob/main/how-to-PR.md) or [email](mailto:muhammadzubairirshad@gmail.com) to add papers! <br>


If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

---
## Overview

- [Object Pose Estimation](#object-pose--estimation)
- [SLAM](#slam)
- [Manipulation/RL](#manipulation-rl)
- [Planning/Navigation](#dynamics-navigation)
- [Citation](#citation)
 
---
## Object Pose Estimation
* **iNeRF**: "Inverting Neural Radiance Fields for Pose Estimation", *IROS, 2021*. [[Paper](https://arxiv.org/pdf/2012.05877.pdf)] [[Pytorch Code](https://github.com/yenchenlin/iNeRF-public)] [[Website](https://yenchenlin.me/inerf/)] [Dataset](https://github.com/BerkeleyAutomation/dex-nerf-datasets)

* **NeRF-Pose**: " A First-Reconstruct-Then-Regress Approach for Weakly-supervised 6D Object Pose Estimation", *arXiv*. [[Paper](https://arxiv.org/pdf/2203.04802.pdf)]

* **Nerfels**: "Renderable Neural Codes for Improved Camera Pose Estimation", *arXiv*. [[Paper](https://arxiv.org/pdf/2206.01916.pdf)]

---
## SLAM
* **iSDF**: Real-Time Neural Signed Distance Fields
for Robot Perception, *RSS, 2022*. [[Paper](https://arxiv.org/abs/2204.02296)] [[Pytorch Code](https://github.com/facebookresearch/iSDF)] [[Website](https://joeaortiz.github.io/iSDF/)]

* **LENS**: " LENS: Localization enhanced by NeRF synthesis", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2110.06558)]

* **NICE-SLAM**: "Neural Implicit Scalable Encoding for SLAM", *CVPR, 2021*. [[Paper](https://arxiv.org/abs/2112.12130)] [Pytorch Code](https://github.com/cvg/nice-slam)] [[Website](https://pengsongyou.github.io/nice-slam?utm_source=catalyzex.com)]

* **iMAP**: "Implicit Mapping and Positioning in Real-Time", *ICCV, 2021*. [[Paper](https://arxiv.org/abs/2103.12352)] [[Website](https://edgarsucar.github.io/iMAP/)]

---
## Manipulation/RL
* **Neural Descriptor Fields**:
SE(3)-Equivariant Object Representations for Manipulation, *arXiv*. [[Paper](https://arxiv.org/abs/2112.05124)] [[Pytorch Code](https://github.com/anthonysimeonov/ndf_robot)] [[Website](https://yilundu.github.io/ndf/)]

* **NeRF-RL**: "Reinforcement Learning with Neural Radiance Fields", *arXiv*. [[Paper](https://dannydriess.github.io/papers/22-driess-NeRF-RL-preprint.pdf)]  [[Website](https://dannydriess.github.io/nerf-rl/)]

* **Dex-NeRF**: "Using a Neural Radiance Field to Grasp Transparent Objects", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2110.14217)]  [[Website](https://sites.google.com/view/dex-nerf)]

* **NeRF-Supervision**: "Learning Dense Object Descriptors from Neural Radiance Fields", *ICRA, 2022*. [[Paper](https://arxiv.org/abs/2203.01913)] [Pytorch Code](https://github.com/yenchenlin/nerf-supervision-public) [[Website](https://yenchenlin.me/nerf-supervision/)]

---
## Planning/Navigation
* **NeRFlow**: "Neural Radiance Flow for 4D View Synthesis and Video Processing", *ICCV, 2021*. [[Paper](https://arxiv.org/abs/2012.09790)] [[Pytorch Code](https://github.com/yilundu/nerflow)] [[Website](https://yilundu.github.io/nerflow/)] 

* **NeRF-Navigation**: "Vision-Only Robot Navigation in a Neural Radiance World", *ICRA, 2022*. [[Paper](https://mikh3x4.github.io/nerf-navigation/assets/NeRF_Navigation.pdf)] [[Pytorch Code](https://github.com/mikh3x4/nerf-navigation)] [[Website](https://mikh3x4.github.io/nerf-navigation/)] 

* **NeRF-dy**: "3D Neural Scene Representations for Visuomotor Control", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2107.04004)] [[Website](https://3d-representation-learning.github.io/nerf-dy/)] 

* **CompNeRFdyn**: "Learning Multi-Object Dynamics with Compositional Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2202.11855.pdf)] [[Website](https://dannydriess.github.io/compnerfdyn/)] 

* **PIFO**: "Deep Visual Constraints: Neural Implicit Models for Manipulation Planning from Visual Input", *arXiv*. [[Paper](https://arxiv.org/pdf/2112.04812.pdf)] [[Website](https://sites.google.com/view/deep-visual-constraints)] 

* **RedSDF**: "Regularized Deep Signed Distance Fields
for Reactive Motion Generation", *arXiv*. [[Paper](https://arxiv.org/abs/2203.04739)] [[Website](https://irosalab.com/2022/02/28/redsdf/)] 

* **ESDF**: "Sampling-free obstacle gradients and reactive planning in Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/abs/2205.01389)]

* "Full-Body Visual Self-Modeling of Robot Morphologies", *arXiv*. [[Paper](https://arxiv.org/abs/2205.01389)] [Pytorch Code](https://github.com/BoyuanChen/visual-selfmodeling) [Website](https://robot-morphology.cs.columbia.edu/)

----
## Citation
If you find this repository useful, please consider citing this list:
```
@misc{irshad2022implicitnerfroboticspaperslist,
    title = {Awesome-Implicit-NeRF-Robotics},
    author = {Irshad, Muhammad Zubair},
    journal = {GitHub repository},
    url = {https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics},
    year = {2022},
}
```
