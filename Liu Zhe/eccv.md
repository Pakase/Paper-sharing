**Accelerating Score-based Generative Models with Preconditioned Diffusion Sampling**

- 论文/Paper: http://arxiv.org/abs/2207.02196
- 代码/Code: https://github.com/fudan-zvg/pds

**qDWI-Morph: Motion-compensated quantitative Diffusion-Weighted MRI analysis for fetal lung maturity assessment**

- 论文/Paper: http://arxiv.org/pdf/2208.09836
- 代码/Code: https://github.com/TechnionComputationalMRILab/qDWI-Morph.

**Ultra-high-resolution unpaired stain transformation via Kernelized Instance Normalization**

- 论文/Paper: https://arxiv.org/pdf/2208.10730v1.pdf
- 代码/Code: https://github.com/Kaminyou/URUST

**Accelerating Score-based Generative Models with Preconditioned Diffusion Sampling**

- 论文/Paper: http://arxiv.org/abs/2207.02196
- 代码/Code: https://github.com/fudan-zvg/pds
**CCPL: Contrastive Coherence Preserving Loss for Versatile Style Transfer**

- 论文/Paper: https://arxiv.org/abs/2207.04808
- 代码/Code: https://github.com/JarrentWu1031/CCPL
- 通过在不同特征层的随机位置对生成特征进行采样。然后在内容特征的相同位置采样同样数量的向量，对每个采样向量，文中希望建模和保留其与周围向量的关联性。为了保留这种邻近向量间的关系，作者并未简单将对应的差向量向相同的方向优化，而是使用了对比学习的形式，来增大对应差向量的互信息，同时与不同位置的差向量在隐空间拉远距离。这么做避免了风格变化和维持原状的直接冲突，使得生成的图像及视频的风格化并未减弱，而是更加合理地与内容结构融为一体。由于更好的保留了内容图中局部之间的关联性，局部随机扰动明显减少，图像生成的质量也大大提升。 注意，本文中训练过程没有视频信息参与，训练数据由单图组成。

文章另外还提出了一种轻量化的风格化网络SCTNet来配合完成通用风格迁移的任务。结合CCPL和SCTNet，文中模型在艺术化，照片化和视频风格迁移三个任务上都超越了之前方法的效果。在视频风格迁移任务中性能逼近最先进的利用视频帧训练的方法。文中还展示了CCPL应用于其他风格迁移模型上以及图到图任务中的效果提升，展示了其广泛应用的潜力。



**CCPL: Contrastive Coherence Preserving Loss for Versatile Style Transfer**

- 论文/Paper: http://arxiv.org/pdf/2207.04808
- 代码/Code: https://github.com/JarrentWu1031/CCPL

**Registration based Few-Shot Anomaly Detection**
- 论文/Paper: https://arxiv.org/abs/2207.07361
- 代码/Code: https://github.com/Jaraxxus-Me/AirDet
- 无需微调的小样本目标检测方法AirDet，针对机器人自主探索任务设计。基训练后，未经微调的AirDet表现甚至优于部分微调后的方法。论文、项目代码、ROS部署接口均已开源。

**Rethinking the Context-oriented Generalization of Vision Transformer**
- 论文/Paper: https://arxiv.org/abs/2203.10790
- 代码/Code: https://github.com/MediaBrain-SJTU/RegAD
- 上海交通大学 MediaBrain 团队和上海人工智能实验室智慧医疗团队等的研究人员提出了一种基于配准的少样本异常检测框架 RegAD，用于学习多个异常检测任务之间共享的通用模型。RegAD 无需模型参数调整，仅利用少量正常样本，就可以直接应用于新的异常检测任务。

**Fast-Vid2Vid: Spatial-Temporal Compression for Video-to-Video Synthesis**

- 论文/Paper: http://arxiv.org/pdf/2207.05049
- 代码/Code: https://github.com/fast-vid2vid/fast-vid2vid

**RepMix: Representation Mixing for Robust Attribution of Synthesized Images**

- 论文/Paper: http://arxiv.org/abs/2207.02063
- 代码/Code: https://github.com/tubui/image_attribution

**VecGAN: Image-to-Image Translation with Interpretable Latent Directions**

- 论文/Paper: http://arxiv.org/pdf/2207.03411
- 代码/Code: None

**Context-Consistent Semantic Image Editing with Style-Preserved Modulation**

- 论文/Paper: http://arxiv.org/pdf/2207.06252
- 代码/Code: https://github.com/wuyangluo/spmpgan

**DynaST: Dynamic Sparse Transformer for Exemplar-Guided Image Generation**

- 论文/Paper: http://arxiv.org/pdf/2207.06124
- 代码/Code: https://github.com/huage001/dynast

**Supervised Attribute Information Removal and Reconstruction for Image Manipulation**

- 论文/Paper: http://arxiv.org/pdf/2207.06555
- 代码/Code: https://github.com/nannanli999/airr

**Name: Adaptive Feature Interpolation for Low-Shot Image Generation**

- 论文/Paper: https://arxiv.org/abs/2112.02450
- 代码/Code: https://github.com/dzld00/Adaptive-Feature-Interpolation-for-Low-Shot-Image-Generation

**WaveGAN: Frequency-aware GAN for High-Fidelity Few-shot Image Generation**

- 论文/Paper: http://arxiv.org/pdf/2207.07288
- 代码/Code: Link:https://github.com/kobeshegu/ECCV2022_WaveGAN

**FakeCLR: Exploring Contrastive Learning for Solving Latent Discontinuity in Data-Efficient GANs**

- 论文/Paper: http://arxiv.org/pdf/2207.08630
- 代码/Code: https://github.com/iceli1007/FakeCLR

**Outpainting by Queries**
- 论文/Paper: https://arxiv.org/abs/2207.05312
- 代码/Code: https://github.com/Kaiseem/QueryOTR

**Single Stage Virtual Try-on via Deformable Attention Flows**

- 论文/Paper: http://arxiv.org/pdf/2207.09161
- 代码/Code: https://github.com/OFA-Sys/DAFlow

**Structure-aware Editable Morphable Model for 3D Facial Detail Animation and Manipulation**

- 论文/Paper: http://arxiv.org/pdf/2207.09019
- 代码/Code: https://github.com/gerwang/facial-detail-manipulation

**Monocular 3D Object Reconstruction with GAN Inversion**

- 论文/Paper: http://arxiv.org/pdf/2207.10061
- 代码/Code: https://github.com/junzhezhang/mesh-inversion

**Generative Multiplane Images: Making a 2D GAN 3D-Aware**

- 论文/Paper: http://arxiv.org/pdf/2207.10642
- 代码/Code: https://github.com/apple/ml-gmpi

**DeltaGAN: Towards Diverse Few-shot Image Generation with Sample-Specific Delta**

- 论文/Paper: http://arxiv.org/pdf/2207.10271
- 代码/Code: https://github.com/bcmi/deltagan-few-shot-image-generation

**Injecting 3D Perception of Controllable NeRF-GAN into StyleGAN for Editable Portrait Image Synthesis**

- 论文/Paper: http://arxiv.org/pdf/2207.10257
- 代码/Code: https://github.com/jgkwak95/surf-gan

**SGBANet: Semantic GAN and Balanced Attention Network for Arbitrarily Oriented Scene Text Recognition**

- 论文/Paper: http://arxiv.org/pdf/2207.10256
- 代码/Code: None

**2D GANs Meet Unsupervised Single-view 3D Reconstruction**

- 论文/Paper: http://arxiv.org/pdf/2207.10183
- 代码/Code: None

**InfiniteNature-Zero: Learning Perpetual View Generation of Natural Scenes from Single Images**

- 论文/Paper: http://arxiv.org/pdf/2207.11148
- 代码/Code: None

**Auto-regressive Image Synthesis with Integrated Quantization**

- 论文/Paper: http://arxiv.org/pdf/2207.10776
- 代码/Code: None

**Compositional Human-Scene Interaction Synthesis with Semantic Control**

- 论文/Paper: http://arxiv.org/pdf/2207.12824
- 代码/Code: https://github.com/zkf1997/coins

**Generator Knows What Discriminator Should Learn in Unconditional GANs**

- 论文/Paper: http://arxiv.org/pdf/2207.13320
- 代码/Code: https://github.com/naver-ai/GGDR

**StyleLight: HDR Panorama Generation for Lighting Estimation and Editing**

- 论文/Paper: http://arxiv.org/pdf/2207.14811
- 代码/Code: https://github.com/Wanggcong/StyleLight

**Cross Attention Based Style Distribution for Controllable Person Image Synthesis**

- 论文/Paper: http://arxiv.org/pdf/2208.00712
- 代码/Code: https://github.com/xyzhouo/casd

**SKDCGN: Source-free Knowledge Distillation of Counterfactual Generative Networks using cGANs**

- 论文/Paper: http://arxiv.org/pdf/2208.04226
- 代码/Code: https://github.com/ambekarsameer96/SKDCGN

**Hierarchical Semantic Regularization of Latent Spaces in StyleGANs**

- 论文/Paper: http://arxiv.org/pdf/2208.03764
- 代码/Code: None

**Style Your Hair: Latent Optimization for Pose-Invariant Hairstyle Transfer via Local-Style-Aware Hair Alignment**

- 论文/Paper: http://arxiv.org/pdf/2208.07765
- 代码/Code: https://github.com/taeu/style-your-hair

**Paint2Pix: Interactive Painting based Progressive Image Synthesis and Editing**

- 论文/Paper: http://arxiv.org/pdf/2208.08092
- 代码/Code: https://github.com/1jsingh/paint2pix

**Mind the Gap in Distilling StyleGANs**

- 论文/Paper: http://arxiv.org/pdf/2208.08840
- 代码/Code: https://github.com/xuguodong03/stylekd
