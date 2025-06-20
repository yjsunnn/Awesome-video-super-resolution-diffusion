# Awesome Diffusion Models for Video Super-Resolution

> A curated list of resources for **Video Super-Resolution (VSR)** using **Diffusion Models**.  
> 一个关于 **基于扩散模型的视频超分辨率 (VSR)** 精选资源的列表。
---

## 📖 Table of Contents / 目录
- [Introduction / 简介](#introduction)
- [Papers / 论文](#papers)
  - [2025](#2025-papers)
  - [2024](#2024-papers)
- [Datasets / 数据集](#datasets)
---

<a id="introduction"></a>
## 🌟 Introduction / 简介
This repository focuses on collecting resources related to **Video Super-Resolution (VSR)** using **Diffusion Models**, including papers, open-source code and datasets. It serves as a one-stop reference for researchers and developers interested in this field.

本仓库专注于收集 **基于扩散模型 (Diffusion Models)** 的 **视频超分辨率 (VSR)** 相关资源，包括论文、开源代码、数据集，为对该领域感兴趣的研究者和开发者提供一站式参考资料。

---

<a id="papers"></a>
## 📄 Papers / 论文

<a id="2025-papers"></a>
### 2025
| Title                                                                                 | Published                                             | Code                                                    | Keywords                      |
|---------------------------------------------------------------------------------------|-------------------------------------------------------|---------------------------------------------------------|-------------------------------|
| **SeedVR**: Seeding Infinity in Diffusion Transformer Towards Generic Video Restoration | [CVPR2025(Jan)](https://arxiv.org/abs/2501.01320) | [GitHub](https://github.com/ByteDance-Seed/SeedVR)      | Train the full model on 256 NVIDIA H100-80G GPUs |
| **DiffVSR**: Enhancing Real-World Video Super-Resolution with Diffusion Models for Advanced Visual Quality and Temporal Consistency | [Arxiv2025(Jan)](https://arxiv.org/abs/2501.10110v2) | [Project](https://xh9998.github.io/DiffVSR-project/)      | T2I-based |
| **STAR**: Spatial-Temporal Augmentation with Text-to-Video Models for Real-World Video Super-Resolution | [Arxiv2025(Feb)](https://arxiv.org/abs/2501.02976) | [GitHub](https://github.com/NJU-PCALab/STAR)      | T2V-based |
| **UltraVSR**: Achieving Ultra-Realistic Video Super-Resolution with Efficient One-Step Diffusion Space | [Arxiv2025(May)](https://arxiv.org/abs/2505.19958) |      | T2I-based, one-step |
| **DOVE**: Efficient One-Step Diffusion Model for Real-World Video Super-Resolution | [Arxiv2025(May)](https://arxiv.org/abs/2505.16239) |   [GitHub](https://github.com/zhengchen1999/DOVE/)   | T2V-based, one-step |
| **LiftVSR**: Lifting Image Diffusion to Video Super-Resolution via Hybrid Temporal Modeling with Only 4×RTX4090s | [Arxiv2025(June)](https://arxiv.org/abs/2506.08529) |   [GitHub](https://github.com/kopperx/LiftVSR)   | T2I-based |
| **DLoRAL**: One-Step Diffusion for Detail-Rich and Temporally Consistent Video Super-Resolution | [Arxiv2025(June)](https://arxiv.org/abs/2506.15591) |   [GitHub](https://github.com/yjsunnn/DLoRAL)   | T2I-based, one-step |
| **SeedVR2**: One-Step Video Restoration via Diffusion Adversarial Post-Training | [Arxiv2025(June)](https://arxiv.org/abs/2506.05301) | [GitHub](https://github.com/ByteDance-Seed/SeedVR)      | Based on [SeedVR](https://arxiv.org/abs/2501.01320), one-step |


<a id="2024-papers"></a>
### 2024
| Title                                                                                                  | Published | Code                                                    | Keywords                      |
|--------------------------------------------------------------------------------------------------------|-----------|---------------------------------------------------------|-------------------------------|
| **Upscale-A-Video**: Temporal-Consistent Diffusion Model for Real-World Video Super-Resolution         | [CVPR2024(Dec)](https://arxiv.org/abs/2312.06640) | [GitHub](https://github.com/sczhou/Upscale-A-Video)     | T2I-based                     |
| **MGLD-VSR**: Motion-Guided Latent Diffusion for Temporally Consistent Real-world Video Super-resolution             | [ECCV2024(Dec)](https://arxiv.org/abs/2312.00853) | [GitHub](https://github.com/IanYeung/MGLD-VSR)          | T2I-based                     |

---

<a id="datasets"></a>
## 📊 Datasets / 数据集
- [REDS](https://seungjunnah.github.io/Datasets/reds.html) - 300 video sequences with resolution of 720×1280, and each video has 100 frames.  
- [OpenVid-1M](https://huggingface.co/datasets/nkp37/OpenVid-1M) - A high-quality text-to-video dataset, and all videos in the OpenVid-1M dataset have resolutions of at least 512×512.  
- [WebVid-2M](https://opendatalab.com/OpenDataLab/WebVid-2M) - A large-scale dataset containing 2.5M text-video pairs with resolution of 336×596.
- [YouHQ-Train](https://drive.google.com/file/d/1f8g8gTHzQq-cKt4s94YQXDwJcdjL59lK/view) - 38,576 videos witwh resolution of 1080 × 1920 for training, each of which has around 32 frames.
- [RealVSR](https://github.com/IanYeung/RealVSR) - The dataset consists of 500 LR-HR sequence pairs with **real degradation**, each of which has 50 frames in length and 1024×512 pixels in size.
- [YouHQ-Test](https://drive.google.com/file/d/1rkeBQJMqnRTRDtyLyse4k6Vg2TilvTKC/view) - 40 video clips for evaluation, each of which has around 32 frames.
- [SPMCS](https://github.com/jiangsutx/SPMC_VideoSR) - 30 different videos, each of them contains 31 frames.
- [UDM10](https://drive.google.com/file/d/1G4V4KZZhhfzUlqHiSBBuWyqLyIOvOs0W/edit) - 10 video sequences, each containing 32 consecutive frames with a resolution of 720x1272.
- [VideoLQ](https://drive.google.com/drive/folders/1-1iJRNdqdFZWOnoUU4xG1Z1QhwsGwMDy) - 50 video sequences, with each sequence containing a variable number of frames ranging from 33 to 100.
---

:star: If it is helpful to your videos or projects, please help star this repo. Thanks! :hugs:

<div>
    <a href="https://github.com/yjsunnn/Awesome-video-super-resolution-diffusion/" target="_blank" style="text-decoration: none;">
        <img src="https://visitor-badge.laobi.icu/badge?page_id=yjsunnn/Awesome-video-super-resolution-diffusion">
    </a>
</div>
