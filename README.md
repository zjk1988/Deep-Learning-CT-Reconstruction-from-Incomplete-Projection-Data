# Awesome CT Reconstruction from Incomplete projection data ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) 

<!-- ![Image](https://pbs.twimg.com/media/GLbj1TyasAA9WF0?format=jpg&name=4096x4096)

RWKV4:  [![Star](https://img.shields.io/github/stars/BlinkDL/RWKV-LM.svg?style=social&label=Star)](https://github.com/BlinkDL/RWKV-LM)[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13048)

RWKV5&6:  [![Star](https://img.shields.io/github/stars/BlinkDL/RWKV-LM.svg?style=social&label=Star)](https://github.com/BlinkDL/RWKV-LM)[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.05892)

RWKV Ecosystem: https://rwkv.cn/eco -->

## Table of Contents 

- [Survey](#Survey)
- [Limited Angle](#Limited-angle)
- [Sparse View](#Sparse-view)
- [Metal Artifact Reduction](#Metal-artifact-reduction)
- [Dataset](#Dataset)

### Survey
| Title                                                        | Code                                                         | Link                                                         | Year |
| :----------------------------------------------------------- | :----------------------------------------------------------- | ------------------------------------------------------------ | ---- |
| A Review of Deep Learning CT Reconstruction From Incomplete Projection Data | [![Star](https://img.shields.io/github/stars/zjk1988/Deep-Learning-CT-Reconstruction-from-Incomplete-Projection-Data.svg?style=social&label=Star)](https://github.com/zjk1988/Deep-Learning-CT-Reconstruction-from-Incomplete-Projection-Data) | [IEEE TRPMS](https://ieeexplore.ieee.org/abstract/document/10253669) | 2023 |
| CT Image Denoising and Deblurring With Deep Learning: Current Status and Perspectives | None | [IEEE TRPMS](https://ieeexplore.ieee.org/abstract/document/10253669) | 2023 |


### Metal Artifacts Reduction
| Title | Code | Link | Year |
|:------|:-----|:-----|:-----|
| F2IFlow: A Fast and Flexible Diffusion Model for CT Metal Artifact Reduction | None | [IEEE TMI](https://ieeexplore.ieee.org/abstract/document/10741004) | 2024 |
| Metal Artifacts Reducing Method Based on Diffusion Model Using Intraoral Optical Scanning Data for Dental Cone-beam CT | None | [IEEE TMI](https://ieeexplore.ieee.org/abstract/document/10630537) | 2024 |
| DiffMAR: A Generalized Diffusion Model for Metal Artifact Reduction in CT Images | None | [IEEE JBHI](https://ieeexplore.ieee.org/abstract/document/10629037) | 2024 |
| A Denoising Diffusion Probabilistic Model for Metal Artifact Reduction in CT | None | [IEEE TMI](https://ieeexplore.ieee.org/abstract/document/10586949/) | 2024 |
| Adaptive and Iterative Learning With Multi-Perspective Regularizations for Metal Artifact Reduction | None | [IEEE TMI](https://ieeexplore.ieee.org/abstract/document/10510476) | 2024 |
| PND-Net: Physics-Inspired Non-Local Dual-Domain Network for Metal Artifact Reduction | None | [IEEE TMI](https://ieeexplore.ieee.org/abstract/document/10404006) | 2024 |
| Quad-Net: Quad-Domain Network for CT Metal Artifact Reduction | [![Star](https://img.shields.io/github/stars/longzilicart/Quad-Net.svg?style=social&label=Star)](https://github.com/longzilicart/Quad-Net) | [IEEE TMI](https://ieeexplore.ieee.org/abstract/document/10385220) | 2024 |
| Unsupervised CT Metal Artifact Reduction by Plugging Diffusion Priors in Dual Domains | [![Star](https://img.shields.io/github/stars/DeepXuan/DuDoDp-MAR.svg?style=social&label=Star)](https://github.com/DeepXuan/DuDoDp-MAR) | [IEEE TMI](https://ieeexplore.ieee.org/abstract/document/10385050) | 2024 |
| SemiMAR: Semi-Supervised Learning for CT Metal Artifact Reduction | [![Star](https://img.shields.io/github/stars/zjk1988/SemiMAR.svg?style=social&label=Star)](https://github.com/zjk1988/SemiMAR) | [IEEE JBHI](https://ieeexplore.ieee.org/abstract/document/10239528) | 2023 |
| Unsupervised Polychromatic Neural Representation for CT Metal Artifact Reduction | [![Star](https://img.shields.io/github/stars/iwuqing/Polyner.svg?style=social&label=Star)](https://github.com/iwuqing/Polyner) | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/dbf02b21d77409a2db30e56866a8ab3a-Abstract-Conference.html) | 2023 |




## Citation
If you find this survey useful for your research, please cite our [Paper](https://ieeexplore.ieee.org/abstract/document/10253669):
```
@ARTICLE{10253669,
  author={Wang, Tao and Xia, Wenjun and Lu, Jingfeng and Zhang, Yi},
  journal={IEEE Transactions on Radiation and Plasma Medical Sciences}, 
  title={A Review of Deep Learning CT Reconstruction From Incomplete Projection Data}, 
  year={2024},
  volume={8},
  number={2},
  pages={138-152},
  doi={10.1109/TRPMS.2023.3316349}}

```

<!-- ### Vision Backbone

| Title                                                        | Code                                                         | Link                                                         |
| :----------------------------------------------------------- | :----------------------------------------------------------- | ------------------------------------------------------------ |
| Vision-RWKV: Efficient and Scalable Visual Perception with RWKV-Like Architectures | [![Star](https://img.shields.io/github/stars/OpenGVLab/Vision-RWKV.svg?style=social&label=Star)](https://github.com/OpenGVLab/Vision-RWKV) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.02308) | -->

<!-- ### Image Restoration

| Title                                                        | Code                                                         | Link                                                         |
| :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Restore-RWKV: Efficient and Effective Medical Image Restoration with RWKV | [![Star](https://img.shields.io/github/stars/Yaziwel/Restore-RWKV.svg?style=social&label=Star)](https://github.com/Yaziwel/Restore-RWKV) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.11087) |

### Image Generation

| Title                                                        | Code                                                         | Link                                                         |
| :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Diffusion-RWKV: Scaling RWKV-Like Architectures for Diffusion Models | [![Star](https://img.shields.io/github/stars/feizc/Diffusion-RWKV.svg?style=social&label=Star)](https://github.com/feizc/Diffusion-RWKV) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.04478) |

### Image Segmentation

| Title                                                        | Code                                                         | Link                                                         |
| :----------------------------------------------------------- | :----------------------------------------------------------- | ------------------------------------------------------------ |
| Vision-RWKV: Efficient and Scalable Visual Perception with RWKV-Like Architectures | [![Star](https://img.shields.io/github/stars/OpenGVLab/Vision-RWKV.svg?style=social&label=Star)](https://github.com/OpenGVLab/Vision-RWKV) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.02308) |
| Mamba or RWKV: Exploring High-Quality and High-Efficiency Segment Anything Model | [![Star](https://img.shields.io/github/stars/HarborYuan/ovsam.svg?style=social&label=Star)](https://github.com/HarborYuan/ovsam) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19369) |
| BSBP-RWKV: Background Suppression with Boundary Preservation for Efficient Medical Image Segmentation | N/A                                                          | [LINK](https://openreview.net/forum?id=ULD5RCk0oo)           | -->

<!-- ### Vision-Language Model

| Title                                                      | Code                                                         | Link                                                         |
| :--------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| VisualRWKV: Visual Language model based on RWKV            | [![Star](https://img.shields.io/github/stars/howard-hou/VisualRWKV.svg?style=social&label=Star)](https://github.com/howard-hou/VisualRWKV) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.13362) |
| RWKV-CLIP: A Robust Vision-Language Representation Learner | [![Star](https://img.shields.io/github/stars/deepglint/RWKV-CLIP.svg?style=social&label=Star)](https://github.com/deepglint/RWKV-CLIP) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.06973) |

### 3D Point Cloud Learning

| Title                                                        | Code                                                         | Link                                                         |
| :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| PointRWKV: Efficient RWKV-Like Model for Hierarchical Point Cloud Learning | [![Star](https://img.shields.io/github/stars/hithqd/PointRWKV.svg?style=social&label=Star)](https://github.com/hithqd/PointRWKV) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15214) |
| LION: Linear Group RNN for 3D Object Detection in Point Clouds | [![Star](https://img.shields.io/github/stars/happinesslz/LION.svg?style=social&label=Star)](https://github.com/happinesslz/LION) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.18232) |
| OccRWKV: Rethinking Efficient 3D Semantic Occupancy Prediction with Linear Complexity | [![Star](https://img.shields.io/github/stars/jmwang0117/OccRWKV.svg?style=social&label=Star)](https://github.com/jmwang0117/OccRWKV) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.19987) |

### Video Understanding

| Title                                           | Code | Link                                                         |
| :---------------------------------------------- | ---- | ------------------------------------------------------------ |
| Video RWKV: Video Action Recognition Based RWKV | N/A  | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.05636) | -->