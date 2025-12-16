# Awesome Diffusion Models for Video Super-Resolution

> A curated list of resources for **Video Super-Resolution (VSR)** using **Diffusion Models**.  
> 一个关于 **基于扩散模型的视频超分辨率 (VSR)** 精选资源的列表。

> ⚡️ **Note:** This list is updated **daily** by following arXiv. If you find anything missing, feel free to open an issue! 😊
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

> The following papers are arranged in chronological order based on their posting time on arXiv.  
> 以下的论文排列顺序是按照在 arXiv 上发布的时间顺序排列的。

<a id="2025-papers"></a>
### 2025
| Title                                                                                 | Published                                             | Code                                                    | Keywords                      |
|---------------------------------------------------------------------------------------|-------------------------------------------------------|---------------------------------------------------------|-------------------------------|
| **SeedVR**: Seeding Infinity in Diffusion Transformer Towards Generic Video Restoration | [CVPR2025(Jan)](https://arxiv.org/abs/2501.01320) | [GitHub](https://github.com/ByteDance-Seed/SeedVR)      | Train the full model on 256 NVIDIA H100-80G GPUs |
| **DiffVSR**: Enhancing Real-World Video Super-Resolution with Diffusion Models for Advanced Visual Quality and Temporal Consistency | [ICCV2025(Jan)](https://arxiv.org/abs/2501.10110v2) | [GitHub](https://github.com/xh9998/DiffVSR)      | T2I(SD x4 Upscaler)-based |
| **STAR**: Spatial-Temporal Augmentation with Text-to-Video Models for Real-World Video Super-Resolution | [ICCV2025(Feb)](https://arxiv.org/abs/2501.02976) | [GitHub](https://github.com/NJU-PCALab/STAR)      | T2V(CogVideoX-5B)-based |
| **UltraVSR**: Achieving Ultra-Realistic Video Super-Resolution with Efficient One-Step Diffusion Space | [ACMMM2025(May)](https://arxiv.org/abs/2505.19958) | [GitHub](https://github.com/yongliuy/UltraVSR)     | T2I(SD)-based, one-step |
| **DOVE**: Efficient One-Step Diffusion Model for Real-World Video Super-Resolution | [NIPS2025(May)](https://arxiv.org/abs/2505.16239) |   [GitHub](https://github.com/zhengchen1999/DOVE/)   | T2V(CogVideoX1.5-5B)-based, one-step |
| **LiftVSR**: Lifting Image Diffusion to Video Super-Resolution via Hybrid Temporal Modeling with Only 4×RTX4090s | [Arxiv2025(Jun)](https://arxiv.org/abs/2506.08529) |   [GitHub](https://github.com/kopperx/LiftVSR)   | T2I(PixArt-α)-based |
| **DLoRAL**: One-Step Diffusion for Detail-Rich and Temporally Consistent Video Super-Resolution | [NIPS2025(Jun)](https://arxiv.org/abs/2506.15591) |   [GitHub](https://github.com/yjsunnn/DLoRAL)   | T2I(SD2.1)-based, one-step |
| **SeedVR2**: One-Step Video Restoration via Diffusion Adversarial Post-Training | [Arxiv2025(Jun)](https://arxiv.org/abs/2506.05301) | [GitHub](https://github.com/ByteDance-Seed/SeedVR)      | Based on [SeedVR](https://arxiv.org/abs/2501.01320), one-step |
| **SimpleGVR**: A Simple Baseline for Latent-Cascaded Video Super-Resolution | [Arxiv2025(Jun)](https://arxiv.org/abs/2506.19838) |     | T2V-intialized, train on 16 NVIDIA H800-80G GPUs |
| **DAM-VSR**: Disentanglement of Appearance and Motion for Video Super-Resolution | [SIGGRAPH2025(Jul)](https://arxiv.org/abs/2507.01012) | [GitHub](https://github.com/kongzhecn/DAM-VSR)      | I2V(Stable Video Diffusion)-based |
| **TurboVSR**: Fantastic Video Upscalers and Where to Find Them | [ICCV2025(Jul)](https://arxiv.org/abs/2506.23618) |      | I2V(LTX-Video)-based |
| **RealisVSR**: Detail-enhanced Diffusion for Real-World 4K Video Super-Resolution | [Arxiv2025(Jul)](https://arxiv.org/abs/2507.19138) |  [Github](https://zws98.github.io/RealisVSR-project/)    | T2V(Wan2.1-1.3B)-based |
| Semantic and Temporal Integration in Latent Diffusion Space for High-Fidelity Video Super-Resolution | [Arxiv2025(Aug)](https://arxiv.org/abs/2508.00471) |      | T2I(SD2.1)-based |
| **Vivid-VR**: Distilling Concepts from Text-to-Video Diffusion Transformer for Photorealistic Video Restoration | [Arxiv2025(Aug)](https://arxiv.org/abs/2508.14483) | [Github](https://arxiv.org/pdf/2508.14483)     | T2V(CogVideoX1.5-5B)-based |
| **OS-DiffVSR**: Towards One-step Latent Diffusion Model for High-detailed Real-world Video Super-Resolution | [Arxiv2025(Sep)](https://arxiv.org/abs/2509.16507) |     | T2I(SD2.1)-based |
| Towards Redundancy Reduction in Diffusion Models for Efficient Video Super-Resolution | [Arxiv2025(Sep)](https://arxiv.org/abs/2509.23980) |  [Github](https://github.com/jp-guo/OASIS)   | T2V(Wan2.1-1.3B)-based |
| Asymmetric VAE for One-Step Video Super-Resolution Acceleration | [Arxiv2025(Sep)](https://arxiv.org/abs/2509.24142) |   [Github](https://github.com/JianzeLi-114/FastVSR)  | T2V(CogVideoX1.5-5B)-based |
| **PatchVSR**: Breaking Video Diffusion Resolution Limits with Patch-wise Video Super-Resolution | [CVPR2025(Sep)](https://arxiv.org/abs/2509.26025) | [Project](https://shiandu.github.io/PatchVSR-website/)    | T2V-based |
| **L∀TINO**: Latent Video Consistency Inverse Solver for High Definition Video Restoration | [Arxiv2025(Oct)](https://arxiv.org/abs/2510.01339) |    |     |
| **InfVSR**: Breaking Length Limits of Generic Video Super-Resolution | [Arxiv2025(Oct)](https://arxiv.org/abs/2510.00948) |  [Github](https://github.com/Kai-Liu001/InfVSR)   | T2V(Wan2.1-1.3B)-based |
| **UniMMVSR**: A Unified Multi-Modal Framework for Cascaded Video Super-Resolution | [Arxiv2025(Oct)](https://arxiv.org/abs/2510.08143) |  [GitHub](https://github.com/ShianDu/UniMMVSR)   | T2V-based, hybrid-modal conditions |
| **MoA-VR**: A Mixture-of-Agents System Towards All-in-One Video Restoration | [Arxiv2025(Oct)](https://arxiv.org/abs/2510.08508) |  [GitHub](https://github.com/MediaX-SJTU/MoA-VR)   | Agent-based video restoration |
| **FlashVSR**: Towards Real-time Diffusion-based Streaming Video Super-Resolution | [Arxiv2025(Oct)](https://arxiv.org/abs/2510.12747) | [GitHub](https://github.com/OpenImagingLab/FlashVSR)    | T2V(Wan 2.1–1.3B)-based |
| Rethinking Diffusion Model-Based Video Super-Resolution: Leveraging Dense Guidance from Aligned Features | [Arxiv2025(Nov)](https://arxiv.org/pdf/2511.16928) |     | T2I(SD x4 Upscaler)-based   |
| **STCDiT**: Spatio-Temporally Consistent Diffusion Transformer for High-Quality Video Super-Resolution | [Arxiv2025(Nov)](https://arxiv.org/pdf/2511.18786) |  [GitHub](https://github.com/JyChen9811/STCDiT)   | T2V(Wan2.1 T2V-1.3B and Wan 2.1 I2V-14B)-based   |
| **CreativeVR**: Diffusion-Prior-Guided Approach for Structure and Motion Restoration in Generative and Real Videos | [Arxiv2025(Dec)](https://arxiv.org/pdf/2512.12060) |  [Project](https://daveishan.github.io/creativevr-webpage/)   | T2V(Wan2.1-1.3B)-based   |



<a id="2024-papers"></a>
### 2024
| Title                                                                                                  | Published | Code                                                    | Keywords                      |
|--------------------------------------------------------------------------------------------------------|-----------|---------------------------------------------------------|-------------------------------|
| **Upscale-A-Video**: Temporal-Consistent Diffusion Model for Real-World Video Super-Resolution         | [CVPR2024(Dec)](https://arxiv.org/abs/2312.06640) | [GitHub](https://github.com/sczhou/Upscale-A-Video)     | T2I(SD x4 Upscaler)-based                     |
| **MGLD-VSR**: Motion-Guided Latent Diffusion for Temporally Consistent Real-world Video Super-resolution             | [ECCV2024(Dec)](https://arxiv.org/abs/2312.00853) | [GitHub](https://github.com/IanYeung/MGLD-VSR)          | T2I(SD2.1)-based                     |

---

<a id="datasets"></a>
## 📊 Datasets / 数据集
- [LSDIR](https://huggingface.co/ofsoundof/LSDIR/tree/main) - High-quality image dataset that contains 84,991 training images, 1,000 validation images, and 1,000 test images.
- [REDS](https://seungjunnah.github.io/Datasets/reds.html) - 300 video sequences with resolution of 720×1280, and each video has 100 frames.  
- [OpenVid-1M](https://huggingface.co/datasets/nkp37/OpenVid-1M) - A high-quality text-to-video dataset, and all videos in the OpenVid-1M dataset have resolutions of at least 512×512.  
- [WebVid-2M](https://opendatalab.com/OpenDataLab/WebVid-2M) - A large-scale dataset containing 2.5M text-video pairs with resolution of 336×596.
- [YouHQ-Train](https://drive.google.com/file/d/1f8g8gTHzQq-cKt4s94YQXDwJcdjL59lK/view) - 38,576 videos witwh resolution of 1080 × 1920 for training, each of which has around 32 frames.
- [RealVSR](https://github.com/IanYeung/RealVSR) - The dataset consists of 500 LR-HR sequence pairs with **real degradation**, each of which has 50 frames in length and 1024×512 pixels in size.
- [YouHQ-Test](https://drive.google.com/file/d/1rkeBQJMqnRTRDtyLyse4k6Vg2TilvTKC/view) - 40 video clips for evaluation, each of which has around 32 frames.
- [RealisVideo-4K-Test](https://huggingface.co/datasets/WisonZws/RealisVideo-4K) - 1,000 high-definition video(4K)-text pairs. 
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
