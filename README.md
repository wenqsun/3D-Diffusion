# Repository for 3D Diffusion Generation Research
This is a repository for 3D Diffusion Generation research papers digest. The taxonomy and papers highly refer the paper (state of the art on diffusion models for visual computing) and the repo: https://github.com/cwchenwang/awesome-3d-diffusion?tab=readme-ov-file

## Survey Paper
1. [state of the art on diffusion models for visual computing](https://arxiv.org/abs/2310.07204) 🌟🌟🌟🌟🌟 \
   This survey paper provides insightful introductions about diffusion models and critical applications, including 2D, 3D, video, and 4D.

## Direct 3D Generation via Diffusion Models
This series of papers are focused on modeling the distribution of 3D shapes. Eventually, 3D content/model can be directly generated by the well-trained 3D diffusion models.
<img width="1310" alt="image" src="https://github.com/wenqsun/3D-Diffusion/assets/93043187/21e134a2-a110-40aa-9638-1cd9bc11e8bc">
Taxonomy: the type of output, representation,  

## Multiview 2D-to-3D Generation via Diffusion Models
This series of papers aim to leverage the 2D diffusion models (pre-trained or train from scratch) to generate high-quality and diverse 

### Text-to-3D using Pre-trained Image Diffusion Models (Text-to-3D)
1. [DreamFusion: Text-to-3D using 2D Diffusion](https://arxiv.org/abs/2209.14988) 🌟🌟🌟🌟🌟 $\textit{ICLR 2023 Outstanding Paper Award}$\
   This paper firstly proposes using SDS to generate 3D contents based on the pre-trained diffusion models.
2. [Magic3D: High-Resolution Text-to-3D Content Creation](https://research.nvidia.com/labs/dir/magic3d/) 🌟🌟🌟🌟 $\textit{CVPR 2023}$\
   Based on the SDS, they propose the coarse-to-fine two-stage optimization to generate high-resolution 3D output efficiently.
3. [Fantasia3D: Disentangling Geometry and Appearance for High-quality Text-to-3D Content Creation](https://arxiv.org/abs/2303.13873) 🌟🌟🌟 $\textit{ICCV 2023}$\
   They
5. [ProlificDreamer: High-Fidelity and Diverse Text-to-3D Generation with Variational Score Distillation](https://arxiv.org/abs/2305.16213) 🌟🌟🌟🌟🌟 $\textit{NeurIPS 2023 Spotlight}$\
   This paper proposes the VSD to enhance the quality and diversity of 3D contents.
6. [NFSD: Noise Free Score Distillation](https://arxiv.org/abs/2310.17590) 

### Adapting Image Models for Multi-view Synthesis (Image-to-3D)
1. [RealFusion: 360° Reconstruction of Any Object from a Single Image](https://arxiv.org/abs/2302.10663) 🌟🌟🌟 $\textit{CVPR 2023}$\

2. [Zero-1-to-3: Zero-shot One Image to 3D Object](https://arxiv.org/abs/2303.11328)
   Zero-shot transfer, single image input, and 3D generation content.
3. [Magic123: One Image to High-Quality 3D Object Generation Using Both 2D and 3D Diffusion Priors](https://arxiv.org/abs/2306.17843) 🌟🌟🌟🌟 $\textit{ICCV 2023}$\

4. 

### 3D-Aware Image Diffusion

