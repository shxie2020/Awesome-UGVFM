# Awesome Vision Foundation Models Unifying Understanding and Generation
LLMs that can solve all language tasks and exhibit the scaling law are very impressive. *How about building vision foundation models?*  
Solving vision tasks separately has achieved significant advancements. *How about unifying understanding and generation?*  
As the long-term roadmap for building a generalist foundation model to solve all vision tasks has not yet been fully determined, we conduct the first survey to provide comprehensive summary and in-depth analysis on vision foundation models unifying both understanding and generation. This repository provides a curated list of related papers and resources, come take a look and let's share insights on unresolved challenges together! Please stay tuned and give us a 🌟 if you are interested in our project, we will update the latest advancements continuously.


---

## 🔥 News
`[2024-10-29]` We have released the survey v1: [Towards Unifying Understanding and Generation in the Era of Vision Foundation Models: A Survey from the Autoregression Perspective](https://arxiv.org/abs/2410.22217).

---


## 📃 Table of Contents
- [Vision-Foundation-Models-Unifying-Understanding-and-Generation](#-vision-foundation-models-unifying-understanding-and-generation)
  - [Autoregression](#-autoregression)
  - [Diffusion](#-diffusion)
  - [Autoregression and Diffusion](#-autoregression-and-diffusion)
 
---


## Vision Foundation Models Unifying Understanding and Generation

### Autoregression
|  Title  |  Abbreviation  |  Venue  |   Date   |  Organization  |   Open Source  |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| [**JetFormer: An Autoregressive Generative Model of Raw Images and Text**](https://arxiv.org/pdf/2411.19722) | JetFormer | arXiv | 2024-11-29 | Google Deepmind | - | - |
| [**MUSE-VL: Modeling Unified VLM through Semantic Discrete Encoding**](https://arxiv.org/pdf/2411.17762) | MUSE-VL | arXiv | 2024-11-26 | ByteDance | - | - |
| [**SAR3D: Autoregressive 3D Object Generation and Understanding via Multi-scale 3D VQVAE**](https://arxiv.org/pdf/2411.16856) | SAR3D | arXiv | 2024-11-25 | NTU, Shanghai AI Lab | [Github](https://github.com/cyw-3d/SAR3D) | - |
| [**Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution**](https://arxiv.org/pdf/2409.12191) | Qwen2-VL | arXiv | 2024-09-18 | Alibaba | [Github](https://github.com/QwenLM/Qwen2-VL) | - |
| [**xGen-MM (BLIP-3): A Family of Open Large Multimodal Models**](https://arxiv.org/pdf/2408.08872) | xGen-MM | arXiv | 2024-08-16 | Salesforce, UW | [Github](https://github.com/salesforce/LAVIS/tree/xgen-mm) | - |
| [**Chameleon: Mixed-Modal Early-Fusion Foundation Models**](https://arxiv.org/pdf/2405.09818) | Chameleon | arXiv | 2024-05-16 | Meta FAIR | [Github](https://github.com/facebookresearch/chameleon) | - |
| [**GiT: Towards Generalist Vision Transformer through Universal Language Interface**](https://arxiv.org/pdf/2403.09394) | GiT | ECCV | 2024-03-14 | PKU, Max Planck Institute for Informatics, CUHK, ETH Zurich | [Github](https://github.com/Haiyang-W/GiT) | - |
| [**Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization**](https://arxiv.org/pdf/2402.03161) | Video-LaVIT | ICML | 2024-02-05 | PKU, Kuaishou | [Github](https://github.com/jy0205/LaVIT) | - |
| [**Scalable pre-training of large autoregressive image models**](https://openreview.net/pdf?id=c92KDfEZTg) | AIM | ICML | 2024-01-16 | Apple | [Github](https://github.com/apple/ml-aim) | - |
| [**Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision Language Audio and Action**](https://openaccess.thecvf.com/content/CVPR2024/papers/Lu_Unified-IO_2_Scaling_Autoregressive_Multimodal_Models_with_Vision_Language_Audio_CVPR_2024_paper.pdf) | Unified-IO 2 | CVPR | 2023-12-28 | Allen  Institute for AI, UIUC, UW | [Github](https://github.com/allenai/unified-io-2) | - |
| [**Sequential Modeling Enables Scalable Learning for Large Vision Models**](https://openaccess.thecvf.com/content/CVPR2024/papers/Bai_Sequential_Modeling_Enables_Scalable_Learning_for_Large_Vision_Models_CVPR_2024_paper.pdf) | LVM | CVPR | 2023-12-01 | UC Berkeley, JHU | [Github](https://github.com/ytongbai/LVM) | - |
| [**TEAL: Tokenize and Embed ALL for Multi-modal Large Language Models**](https://arxiv.org/pdf/2311.04589) | TEAL | arXiv | 2023-11-08 | Tencent | - | - |

### Diffusion
|  Title  |  Abbreviation  |  Venue  |   Date   |  Organization  |   Open Source  |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| [**MoTe: Learning Motion-Text Diffusion Model for Multiple Generation Tasks**](https://arxiv.org/pdf/2411.19786) | MoTe | arXiv | 2024-11-29 | HKU, NUS, ZJU | - | - |
| [**LaVin-DiT: Large Vision Diffusion Transformer**](https://arxiv.org/pdf/2411.11505) | LaVin-DiT | arXiv | 2024-11-18 | USYD, NUS, UniMelb, AIsphere | [Github](https://github.com/DerrickWang005/LaVin-DiT) | - |
| [**Unimotion: Unifying 3D Human Motion Synthesis and Understanding**](https://arxiv.org/pdf/2409.15904) | Unimotion | arXiv | 2024-09-24 | Tuebingen U, Max Planck Institute for Informatics | [Github](https://github.com/Coral79/Unimotion) | - |
| [**One Transformer Fits All Distributions in Multi-Modal Diffusion at Scale**](https://proceedings.mlr.press/v202/bao23a/bao23a.pdf) | UniDiffuser | ICML | 2023-03-12 | THU, Shengshu, RUC, BAAI, Pazhou Lab | [Github](https://github.com/thu-ml/unidiffuser) | - |


### Autoregression and Diffusion
|  Title  |  Abbreviation  |  Venue  |   Date   |  Organization  |   Open Source  |
|:--------|:--------:|:--------:|:--------:|:--------:|:--------:|
| [**MIO: A Foundation Model on Multimodal Tokens**](https://arxiv.org/pdf/2409.17692) | MIO | arXiv | 2024-09-26 | BHU, 01.AI, M-A-P, PolyU, UAlberta, UWaterloo, UoM, CAS, PKU, HKUST | [Github](https://github.com/MIO-Team/MIO) | - |
| [**Show-o: One Single Transformer to Unify Multimodal Understanding and Generation**](https://arxiv.org/pdf/2408.12528) | Show-o | arXiv | 2024-08-22 | NUS, ByteDance | [Github](https://github.com/showlab/Show-o) | - |
| [**AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling**](https://arxiv.org/pdf/2402.12226) | AnyGPT | arXiv | 2024-02-19 | FDU, Multimodal Art Projection Research Community, Shanghai AI Lab | [Github](https://junzhan2000.github.io/AnyGPT.github.io/) | - |
| [**Generative multimodal models are in-context learners**](https://openaccess.thecvf.com/content/CVPR2024/papers/Sun_Generative_Multimodal_Models_are_In-Context_Learners_CVPR_2024_paper.pdf) | Emu2 | CVPR | 2023-12-20 | BAAI, THU, PKU | [Github](https://github.com/baaivision/Emu/tree/main/Emu2) | - |
| [**VL-GPT: A Generative Pre-trained Transformer for Vision and Language Understanding and Generation**](https://arxiv.org/pdf/2312.09251) | VL-GPT | arXiv | 2023-12-14 | XJTU, Tencent, HKU | [Github](https://github.com/AILab-CVC/VL-GPT) | - |
| [**CoDi-2: In-Context, Interleaved, and Interactive Any-to-Any Generation**](https://openaccess.thecvf.com/content/CVPR2024/papers/Tang_CoDi-2_In-Context_Interleaved_and_Interactive_Any-to-Any_Generation_CVPR_2024_paper.pdf) | CoDi-2 | CVPR | 2023-11-30 | UC Berkeley, Microsoft, Zoom, UNC Chapel Hill | [Github](https://github.com/microsoft/i-Code/tree/main/CoDi-2) | - |
| [**DreamLLM: Synergistic Multimodal Comprehension and Creation**](https://openreview.net/pdf?id=y01KGvd9Bw) | DreamLLM | ICLR | 2023-09-20 | XJTU, IIISCT, MEGVII Technology, THU, HUST, Shanghai AI Lab, Shanghai Qi Zhi Institute | [Github](https://github.com/RunpeiDong/DreamLLM) | - |
| [**Emu: Generative Pretraining in Multimodality**](https://proceedings.neurips.cc/paper_files/paper/2023/file/43a69d143273bd8215578bde887bb552-Paper-Conference.pdf) | Emu | ICLR | 2023-07-11 | BAAI, THU, PKU | [Github](https://github.com/baaivision/Emu) | - |
| [**Generating Images with Multimodal Language Models**](https://proceedings.neurips.cc/paper_files/paper/2023/file/43a69d143273bd8215578bde887bb552-Paper-Conference.pdf) | GILL | NeurIPS | 2023-05-26 | CMU | [Github](https://github.com/kohjingyu/gill) | - |

---


## 🫶 Citation
If you find our survey and repo useful, you can cite the paper as following formats. We appreciate it a lot.

### Survey v1: Towards Unifying Understanding and Generation in the Era of Vision Foundation Models: A Survey from the Autoregression Perspective
```BibTeX
@article{xie2024arvfm,
  title={Towards Unifying Understanding and Generation in the Era of Vision Foundation Models: A Survey from the Autoregression Perspective},
  author={Xie, Shenghao and Zu, Wenqiang and Zhao, Mingyang and Su, Duo and Liu, Shilong and Shi, Ruohua and Li, Guoqi and Zhang, Shanghang and Ma, Lei},
  journal={arXiv preprint arXiv:2410.22217},
  year={2024}
}
```

---
