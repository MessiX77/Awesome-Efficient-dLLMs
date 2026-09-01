# Awesome-Efficient-dLLMs

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/MessiX77/Awesome-Efficient-dLLMs)
[![Stars](https://img.shields.io/github/stars/MessiX77/Awesome-Efficient-dLLMs.svg?style=social)](https://img.shields.io/github/stars/MessiX77/Awesome-Efficient-dLLMs.svg?style=social)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC--BY--NC--ND%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![PRWelcome](https://img.shields.io/badge/PRs-Welcome-red)](https://img.shields.io/badge/PRs-Welcome-red)
[![PDF](https://img.shields.io/badge/Paper-PDF-pdf.svg)](https://github.com/MessiX77/Awesome-Efficient-dLLMs/blob/main/files/Efficient_dLLMs.pdf)
[![Paper](https://img.shields.io/badge/Authorea-Preprint-turquoise.svg)](https://www.authorea.com/users/1021451/articles/1381451-efficient-diffusion-language-models-a-comprehensive-survey)


📒A curated list of Awesome **Efficient Diffusion Language Models** Papers with codes.

<p align="center">
    <img src="images/meta.png" width="100%" style="align:center;"/>
</p>


<p align="center">
    <img src="images/taxonomy.png" width="100%" style="align:center;"/>
</p>


## 📖 News 🔥🔥
<div id="news"></div
>

- [2026-08-21]: 🎉 Our survey has been accepted to **EMNLP 2026 Findings**!

- [2026-04-24]: 🚀 We have migrated this repository to [MessiX77](https://github.com/MessiX77/Awesome-Efficient-dLLMs). Please star and follow the new repo!

- [2026-02-02]: 🤗 We update the ICLR 2026 accepted papers!

- [2026-01-26]: 🤗 Our [first version paper](https://www.authorea.com/users/1021451/articles/1381451-efficient-diffusion-language-models-a-comprehensive-survey?__cf_chl_rt_tk=N3oFKQWmtIx7d0qLM1RU8W3qSfdoh8IeoOEnMxUrQOY-1770035362-1.0.1.1-19KAjC_KEoeeixwFNFCEOpPpoUoyKhAujSRxSu9B3.A) is available!

- [2026-01-23]: 🤗 We release the repository!


## 🤖Contents

- [Awesome-Efficient-dLLMs](#awesome-efficient-dllms)
  - [🤖Contents](#contents)
  - [📙 Training Efficiency](#-training-efficiency)
  - [📙 Inference Acceleration | Parallel Decoding](#-inference-acceleration--parallel-decoding)
  - [📙 Inference Acceleration | Cache Management](#-inference-acceleration--cache-management)
  - [📙 Inference Acceleration | Compression Techniques](#-inference-acceleration--compression-techniques)
  - [📙 Contextual Scalability | Variable Length](#-contextual-scalability--variable-length)
  - [📙 Contextual Scalability | Long Context](#-contextual-scalability--long-context)
  - [📙 System Framework](#-system-framework)
  - [📙 Multimodal DLM](#-multimodal-dlm)
  - [©️Citations](#️citations)



## 📙 Training Efficiency  

<div id="Training"></div>  

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:| 
|2024.10| AR-to-diffusion |[**DiffuLLaMA**] Scaling Diffusion Language Models via Adaptation from Autoregressive Models (@HKU)  | [[pdf]](https://arxiv.org/pdf/2410.17891) |[[code]](https://github.com/HKUNLP/DiffuLLaMA) ![](https://img.shields.io/github/stars/HKUNLP/DiffuLLaMA.svg?style=social) |ICLR 2025|
|2025.07| AR-to-diffusion |[**Dream 7B**] Dream 7B: Diffusion Large Language Models (@HKU)  | [[pdf]](https://arxiv.org/pdf/2508.15487) |[[code]](https://github.com/DreamLM/Dream) ![](https://img.shields.io/github/stars/DreamLM/Dream.svg?style=social) |arXiv|
|2025.10| AR-to-diffusion |[**RND1**] RND1: Simple, Scalable AR-to-Diffusion Conversion (@Radical Numerics)  | [[pdf]](https://www.radicalnumerics.ai/assets/rnd1_report.pdf) |[[code]](https://github.com/RadicalNumerics/RND1) ![](https://img.shields.io/github/stars/RadicalNumerics/RND1.svg?style=social) |blog|
|2025.09| AR-to-block diffusion |[**SDLM**] Sequential Diffusion Language Models (@Shanghai AI Lab)  | [[pdf]](https://arxiv.org/pdf/2509.24007) |[[code]](https://github.com/OpenGVLab/SDLM) ![](https://img.shields.io/github/stars/OpenGVLab/SDLM.svg?style=social) |arXiv|
|2025.09| AR-to-block diffusion |[**Fast-dLLM v2**] Fast-dLLM v2: Efficient Block-Diffusion LLM (@NVIDIA)  | [[pdf]](https://arxiv.org/pdf/2509.26328) |[[code]](https://github.com/NVlabs/Fast-dLLM) ![](https://img.shields.io/github/stars/NVlabs/Fast-dLLM.svg?style=social) |ICLR 2026|
|2025.10| AR-to-block diffusion |[**SDAR**] SDAR: A Synergistic Diffusion-AutoRegression Paradigm for Scalable Sequence Generation (@Shanghai AI Lab)  | [[pdf]](https://arxiv.org/pdf/2510.06303) |[[code]](https://github.com/JetAstra/SDAR) ![](https://img.shields.io/github/stars/JetAstra/SDAR.svg?style=social) |arXiv|
|2025.12| AR-to-block diffusion |[**LLaDA2.0**] LLaDA2.0: Scaling Up Diffusion Language Models to 100B (@Ant Group)  | [[pdf]](https://arxiv.org/pdf/2512.15745) | [[code]](https://github.com/inclusionAI/LLaDA2.0) ![](https://img.shields.io/github/stars/inclusionAI/LLaDA2.0.svg?style=social) |arXiv|
|2025.12| AR-to-block diffusion |[**Efficient-DLM**] Efficient-DLM: From Autoregressive to Diffusion Language Models, and Beyond in Speed (@NVIDIA)  | [[pdf]](https://arxiv.org/pdf/2512.14067) |  |arXiv|
|2025.12| AR-to-block diffusion |[**NBDiff**] From Next-Token to Next-Block: A Principled Adaptation Path for Diffusion LLMs (@Shanghai AI Lab)  | [[pdf]](https://arxiv.org/pdf/2512.06776) |[[code]](https://github.com/prajwal369/NBDiff) ![](https://img.shields.io/github/stars/prajwal369/NBDiff.svg?style=social) |arXiv|
|2026.01| AR-to-block diffusion |[**Diffusion In Diffusion**] Diffusion In Diffusion: Reclaiming Global Coherence in Semi-Autoregressive Diffusion (@Huawei)  | [[pdf]](https://arxiv.org/pdf/2601.13599) | |arXiv|
|2025.09| MoE |[**LLaDA-MoE**] LLaDA-MoE: A Sparse MoE Diffusion Language Model (@Ant Group)  | [[pdf]](https://arxiv.org/pdf/2509.24389) |  |arXiv|
|2025.12| Encoder-Decoder |[**E2D2**] Encoder-Decoder Diffusion Language Models for Efficient Training and Inference (@Cornell)  | [[pdf]](https://arxiv.org/pdf/2510.22852) | [[code]](https://github.com/kuleshov-group/e2d2) ![](https://img.shields.io/github/stars/kuleshov-group/e2d2.svg?style=social) |NeurIPS 2025|
|2026.02| Scaling Law |[**Scaling Beyond MDLM**] Scaling Beyond Masked Diffusion Language Models (@NVIDIA)| [[pdf]](https://arxiv.org/pdf/2602.15014) | |arXiv|
|2026.03| Training Paradigm |[**Mask Is What DLLM Needs**] Mask Is What DLLM Needs: A Masked Data Training Paradigm for Diffusion LLMs (@Huawei)| [[pdf]](https://arxiv.org/pdf/2603.15803) | |arXiv|


## 📙 Inference Acceleration | Parallel Decoding
- **Fast-dLLM++: Fréchet Profile Decoding for Faster Diffusion LLM Inference** (2026) [[arXiv](https://arxiv.org/abs/2606.02955)] [[Code](https://github.com/Ringo-Star/FastdLLM_plusplus)] [[Project Page](https://ringo-star.github.io/projectpage_frechet/)]
<div id="Parallel"></div> 

<p align="center">
    <img src="images/parallel.png" width="100%" style="align:center;"/>
</p>
 
|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.05| Heuristic Methods |[**Fast-dLLM**] Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding (@NVIDIA)| [[pdf]](https://arxiv.org/pdf/2505.22618) |[[code]](https://github.com/NVlabs/Fast-dLLM)![](https://img.shields.io/github/stars/NVlabs/Fast-dLLM.svg?style=social) |ICLR 2026|
|2025.05| Heuristic Methods |[**EB-Sampler**] Accelerated Sampling from Masked Diffusion Models via Entropy Bounded Unmasking (@Meta)| [[pdf]](https://arxiv.org/pdf/2505.24857) | |NeurIPS 2025|
|2025.06| Heuristic Methods |[**SlowFast Sampling**] Accelerating diffusion large language models with slowfast: The three golden principles (@SJTU)| [[pdf]](https://arxiv.org/pdf/2506.10848) | [[code]](https://github.com/LiangrunFlora/Slow-Fast-Sampling)![](https://img.shields.io/github/stars/LiangrunFlora/Slow-Fast-Sampling?style=social) |ICLR 2026|
|2025.06| Heuristic Methods |[**WINO**] Wide-In, Narrow-Out: Revokable Decoding for Efficient and Effective DLLMs (@SJTU) | [[pdf]](https://arxiv.org/pdf/2509.00707) | [[code]](https://github.com/Feng-Hong/WINO-DLLM)![](https://img.shields.io/github/stars/Feng-Hong/WINO-DLLM?style=social)|ICLR 2026|
|2025.06| Heuristic Methods |[**APD**] Accelerating Diffusion LLMs via Adaptive Parallel Decoding (@UCLA)| [[pdf]](https://arxiv.org/pdf/2506.00413) | [[code]](https://github.com/danielmisrael/apd)![](https://img.shields.io/github/stars/danielmisrael/apd?style=social) |NeurIPS 2025|
|2025.08| Heuristic Methods |[**Prophet**] Diffusion language models know the answer before decoding (@PolyUHK)| [[pdf]](https://arxiv.org/pdf/2508.19982) | [[code]](https://github.com/pixeli99/Prophet)![](https://img.shields.io/github/stars/pixeli99/Prophet?style=social) |ICLR 2026|
|2025.08| Heuristic Methods |[**RWS**] Reward-Weighted Sampling: Enhancing Non-Autoregressive Characteristics in Masked Diffusion LLMs (@KAIST)| [[pdf]](https://arxiv.org/pdf/2509.00707) | |EMNLP 2025|
|2025.10| Heuristic Methods |[**LocalLeap**] Accelerated Diffusion LLM Inference via Local Determinism Propagation (@Kuaishou)| [[pdf]](https://arxiv.org/pdf/2510.07081) | [[code]](https://github.com/friedrichor/LocalLeap)![](https://img.shields.io/github/stars/friedrichor/LocalLeap?style=social) |arXiv|
|2025.10| Heuristic Methods |[**FreeDave**] Free Draft-and-Verification: Toward Lossless Parallel Decoding for Diffusion Large Language Models (@UW-Madison) | [[pdf]](https://arxiv.org/pdf/2510.00294) | [[code]](https://github.com/cychomatica/FreeDave)![](https://img.shields.io/github/stars/cychomatica/FreeDave?style=social)|arXiv|
|2025.10| Heuristic Methods |[**Saber**] Saber: An Efficient Sampling with Adaptive Acceleration and Backtracking Enhanced Remasking for Diffusion Language Model (@PKU)| [[pdf]](https://arxiv.org/pdf/2510.18165) |[[code]](https://github.com/zhaoyMa/Saber)![](https://img.shields.io/github/stars/zhaoyMa/Saber.svg?style=social) |arXiv|
|2025.12| Heuristic Methods |[**SchED**] Fast-Decoding Diffusion Language Models via Progress-Aware Confidence Schedules (@MBZUAI)| [[pdf]](https://arxiv.org/pdf/2512.02892) |[[code]](https://github.com/amr-mohamedd/SchED)![](https://img.shields.io/github/stars/amr-mohamedd/SchED?style=social) |arXiv|
|2025.12| Heuristic Methods |[**CadLLM**] Improving the Throughput of Diffusion-based Large Language Models via a Training-Free Confidence-Aware Calibration (@Intel)| [[pdf]](https://arxiv.org/pdf/2512.07173) | |arXiv|
|2025.12| Heuristic Methods |[**LoPA**] LoPA: Scaling dLLM Inference via Lookahead Parallel Decoding (@SJTU) | [[pdf]](https://arxiv.org/pdf/2512.16229) | [[code]](https://github.com/SJTU-DENG-Lab/LoPA)![](https://img.shields.io/github/stars/SJTU-DENG-Lab/LoPA?style=social)|arXiv|
|2026.01| Heuristic Methods |[**Diffusion In Diffusion**] Diffusion In Diffusion: Reclaiming Global Coherence in Semi-Autoregressive Diffusion (@Huawei)  | [[pdf]](https://arxiv.org/pdf/2601.13599) | |arXiv|
|2026.01| Heuristic Methods |[**Order-Token Search**] Improving Diffusion Language Model Decoding through Joint Search in Generation Order and Token Space (@Stanford)| [[pdf]](https://arxiv.org/pdf/2601.20339) | |arXiv|
|2026.01| Heuristic Methods |[**RDD**] Reversible Diffusion Decoding for Diffusion Language Models (@ZJU)| [[pdf]](https://arxiv.org/pdf/2602.00150) | |arXiv|
|2026.02| Heuristic Methods |[**ReMix**] Rejection Mixing: Fast Semantic Propagation of Mask Tokens for Efficient DLLM Inference (@SJTU)| [[pdf]](https://arxiv.org/pdf/2602.22868) | [[code]](https://github.com/Serpientw/ReMix-DLLM)![](https://img.shields.io/github/stars/Serpientw/ReMix-DLLM?style=social) |CVPR2026| 
|2026.02| Heuristic Methods |[**Info-Gain Sampler**] Improving Sampling for Masked Diffusion Models via Information Gain (@CMU)| [[pdf]](https://arxiv.org/pdf/2602.18176) | |arXiv|
|2026.03| Heuristic Methods |[**DOS**] DOS: Dependency-Oriented Sampler for Masked Diffusion Language Models (@SEU)| [[pdf]](https://arxiv.org/pdf/2603.15340) | |arXiv|
|2026.03| Heuristic Methods |[**Confidence-Based Decoding**] Confidence-Based Decoding is Provably Efficient for Diffusion Language Models (@UMD)| [[pdf]](https://arxiv.org/pdf/2603.22248) | |arXiv|
|2025.09| Learning-based Methods |[**dParallel**] dparallel: Learnable parallel decoding for dllms (@NUS) | [[pdf]](https://arxiv.org/pdf/2509.26488) | [[code]](https://github.com/czg1225/dParallel)![](https://img.shields.io/github/stars/czg1225/dParallel?style=social)| ICLR 2026|
|2025.09| Learning-based Methods |[**LSD**] Learnable sampler distillation for discrete diffusion models (@UESTC) | [[pdf]](https://arxiv.org/pdf/2509.19962) | [[code]](https://github.com/feiyangfu/LSD)![](https://img.shields.io/github/stars/feiyangfu/LSD?style=social)|NeurIPS 2025|
|2025.09| Learning-based Methods |[**ADJUST**] Enabling Approximate Joint Sampling in Diffusion LMs (@UT-Austin) | [[pdf]](https://arxiv.org/pdf/2509.22738) | |arXiv|
|2025.09| Learning-based Methods |[**Learn2PD**] Learning to Parallel: Accelerating Diffusion Large Language Models via Learnable Parallel Decoding (@UCF)| [[pdf]](https://arxiv.org/pdf/2509.25188) | [[code]](https://github.com/ims-kdks/Learning-to-Parallel-Decoding)![](https://img.shields.io/github/stars/ims-kdks/Learning-to-Parallel-Decoding.svg?style=social) |ICLR 2026|
|2025.12| Learning-based Methods | Learning Unmasking Policies for Diffusion Language Models (@Apple) | [[pdf]](https://arxiv.org/pdf/2512.09106) | |arXiv|
|2026.01| Learning-based Methods |[**d3LLM**] d3LLM: Ultra-Fast Diffusion LLM using Pseudo-Trajectory Distillation (@UCSD)| [[pdf]](https://arxiv.org/pdf/2601.07568) |[[code]](https://github.com/hao-ai-lab/d3LLM)![](https://img.shields.io/github/stars/hao-ai-lab/d3LLM.svg?style=social) |arXiv|

## 📙 Inference Acceleration | Cache Management
<div id="Cache"></div> 

<p align="center">
    <img src="images/cache.png" width="100%" style="align:center;"/>
</p>

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.03| Architecture Paradigms |[**Block Diffusion**] Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models (@Cornell)| [[pdf]](https://arxiv.org/pdf/2503.09573) |[[code]](https://github.com/kuleshov-group/bd3lms)![](https://img.shields.io/github/stars/kuleshov-group/bd3lms.svg?style=social) |ICLR 2025|
|2025.05| Architecture Paradigms |[**Fast-dLLM**] Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding (@NVIDIA)| [[pdf]](https://arxiv.org/pdf/2505.22618) |[[code]](https://github.com/NVlabs/Fast-dLLM)![](https://img.shields.io/github/stars/NVlabs/Fast-dLLM.svg?style=social) |ICLR 2026|
|2025.09| Architecture Paradigms |[**Fast-dLLM-v2**] Fast-dLLM v2: Efficient Block-Diffusion Large Language Model(@NVIDIA)| [[pdf]](https://arxiv.org/pdf/2509.26328) |[[code]](https://github.com/NVlabs/Fast-dLLM)![](https://img.shields.io/github/stars/NVlabs/Fast-dLLM.svg?style=social) |ICLR 2026|
|2025.05| Adaptive Refresh Mechanisms |[**dKV-Cache**] dKV-Cache: The Cache for Diffusion Language Models (@NUS)| [[pdf]](https://arxiv.org/pdf/2505.15781) |[[code]](https://github.com/horseee/dKV-Cache)![](https://img.shields.io/github/stars/horseee/dKV-Cache.svg?style=social) |NeurIPS 2025|
|2025.06| Adaptive Refresh Mechanisms |[**dLLM-Cache**] dLLM-Cache: Accelerating Diffusion Large Language Models with Adaptive Caching (@SJTU)| [[pdf]](https://arxiv.org/pdf/2506.06295) |[[code]](https://github.com/maomaocun/dLLM-Cache)![](https://img.shields.io/github/stars/maomaocun/dLLM-Cache.svg?style=social) |arXiv|
|2025.09| Adaptive Refresh Mechanisms |[**d$^2$Cache**] d$^2$Cache: Accelerating Diffusion-Based LLMs via Dual Adaptive Caching (@SEU)| [[pdf]](https://arxiv.org/pdf/2509.23094) |[[code]](https://github.com/Kamichanw/d2Cache)![](https://img.shields.io/github/stars/Kamichanw/d2Cache.svg?style=social) | ICLR 2026|
|2025.08| Memory Sparsity & Eviction |[**Sparse-dLLM**] Sparse-dLLM: Accelerating Diffusion LLMs with Dynamic Cache Eviction (@FDU)| [[pdf]](https://arxiv.org/pdf/2508.02558) |[[code]](https://github.com/OpenMOSS/Sparse-dLLM)![](https://img.shields.io/github/stars/OpenMOSS/Sparse-dLLM.svg?style=social) |arXiv|
|2025.10| Memory Sparsity & Eviction |[**Elastic-Cache**] Attention Is All You Need for KV Cache in Diffusion LLMs (@MBZUAI)| [[pdf]](https://arxiv.org/pdf/2510.14973) |[[code]](https://github.com/VILA-Lab/Elastic-Cache)![](https://img.shields.io/github/stars/VILA-Lab/Elastic-Cache.svg?style=social) |ICLR 2026|
|2025.10| Memory Sparsity & Eviction |[**MaskKV**] Mask Tokens as Prophet: Fine-Grained Cache Eviction for Efficient dLLM Inference (@SJTU)| [[pdf]](https://arxiv.org/pdf/2510.09309) |[[code]](https://github.com/jianuo-huang/MaskKV)![](https://img.shields.io/github/stars/jianuo-huang/MaskKV.svg?style=social) |arXiv|


## 📙 Inference Acceleration | Compression Techniques
<div id="Compression"></div> 

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.08| Quantization |[**QDLM**] Quantization Meets dLLMs: A Systematic Study of Post-training Quantization for Diffusion LLMs (@CASIA)| [[pdf]](https://arxiv.org/pdf/2508.14896) |[[code]](https://github.com/MessiX77/QDLM)![](https://img.shields.io/github/stars/MessiX77/QDLM.svg?style=social) |arXiv|
|2025.08| Quantization |[**DLLMQuant**] DLLMQuant: Quantizing Diffusion-based Large Language Models (@Houmo)| [[pdf]](https://arxiv.org/pdf/2508.14896) | |arXiv|
|2025.09| Quantization |[**Quant-dLLM**] Quant-dLLM: Post-Training Extreme Low-Bit Quantization for Diffusion Large Language Models (@SJTU)| [[pdf]](https://arxiv.org/pdf/2510.03274) |[[code]](https://github.com/ZTA2785/Quant-dLLM)![](https://img.shields.io/github/stars/ZTA2785/Quant-dLLM.svg?style=social) |ICLR 2026|
|2025.06| Distillation |[**DLM-One**] DLM-One: Diffusion Language Models for One-Step Sequence Generation (@UTAustin)| [[pdf]](https://arxiv.org/pdf/2506.00290) | |arXiv|
|2025.12| Distillation |[**FS-DSM**] Fast-Decoding Diffusion Language Models via Progress-Aware Confidence Schedules (@MBZUAI)| [[pdf]](https://arxiv.org/pdf/2512.02892) | |arXiv|
|2026.01| Distillation |[**CD4LM**] CD4LM: Consistency Distillation and aDaptive Decoding for Diffusion Language Models (@Princeton)| [[pdf]](https://arxiv.org/pdf/2601.02236) |[[code]](https://github.com/yihao-liang/CDLM)![](https://img.shields.io/github/stars/yihao-liang/CDLM.svg?style=social) |arXiv|
|2026.01| Distillation |[**d3LLM**] d3LLM: Ultra-Fast Diffusion LLM using Pseudo-Trajectory Distillation (@UCSD)| [[pdf]](https://arxiv.org/pdf/2601.07568) |[[code]](https://github.com/hao-ai-lab/d3LLM)![](https://img.shields.io/github/stars/hao-ai-lab/d3LLM.svg?style=social) |arXiv|
|2025.09| Speculative Decoding - dLLM-only |[**Spiffy**] Spiffy: Multiplying Diffusion LLM Acceleration via Lossless Speculative Decoding (@Qualcomm AI Research)| [[pdf]](https://arxiv.org/pdf/2509.18085) | |arXiv|
|2025.10| Speculative Decoding - dLLM-only |[**SSD**] Self Speculative Decoding for Diffusion Large Language Models (@SJTU)| [[pdf]](https://arxiv.org/pdf/2510.04147) | |arXiv|
|2025.11| Speculative Decoding - dLLM-only |[**ODB**] Orchestrating Dual-Boundaries: An Arithmetic Intensity Inspired Acceleration Framework for Diffusion Language Models (@PKU)| [[pdf]](https://arxiv.org/pdf/2511.21759) | [[code]](https://github.com/PKU-SEC-Lab/ODB-dLLM)![](https://img.shields.io/github/stars/PKU-SEC-Lab/ODB-dLLM.svg?style=social) |arXiv|
|2025.06| Speculative Decoding - dLLM-AR Synergy |[**APD**] Accelerating Diffusion LLMs via Adaptive Parallel Decoding (@UCLA)| [[pdf]](https://arxiv.org/pdf/2506.00413) | |NeurIPS 2025|
|2025.09| Speculative Decoding - dLLM-AR Synergy |[**Learn2PD**] Learning to Parallel: Accelerating Diffusion Large Language Models via Learnable Parallel Decoding (@UCF)| [[pdf]](https://arxiv.org/pdf/2509.25188) | [[code]](https://github.com/ims-kdks/Learning-to-Parallel-Decoding)![](https://img.shields.io/github/stars/ims-kdks/Learning-to-Parallel-Decoding.svg?style=social) |ICLR 2026|
|2025.10| Speculative Decoding - dLLM-AR Synergy |[**DiffuSpec**] DiffuSpec: Unlocking Diffusion Language Models for Speculative Decoding (@THU)| [[pdf]](https://arxiv.org/pdf/2510.02358) | |arXiv|
|2025.12| Speculative Decoding - dLLM-AR Synergy |[**DEER**] DEER: Draft with Diffusion, Verify with Autoregressive Models (@THU)| [[pdf]](https://arxiv.org/pdf/2512.15176) | [[code]](https://github.com/czc726/DEER)![](https://img.shields.io/github/stars/czc726/DEER.svg?style=social) |arXiv|
|2026.01| Speculative Decoding - dLLM-AR Synergy |[**DFlash**] DFlash: Block Diffusion for Flash Speculative Decoding (@UCSD)| | [[code]](https://github.com/z-lab/dflash)![](https://img.shields.io/github/stars/z-lab/dflash.svg?style=social) |GitHub|
|2026.01| Speculative Decoding - dLLM-AR Synergy |[**DART**] DART: Diffusion-Inspired Speculative Decoding for Fast LLM Inference (@NJU)| [[pdf]](https://arxiv.org/pdf/2601.19278) |[[code]](https://github.com/fvliang/DART)![](https://img.shields.io/github/stars/fvliang/DART.svg?style=social) |arXiv|



## 📙 Contextual Scalability | Variable Length
<div id="Variable"></div> 

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2022.10| Variable Length |[**DiffuSeq**] DiffuSeq: Sequence to Sequence Text Generation with Diffusion Models (@HKU)| [[pdf]](https://arxiv.org/pdf/2210.08933) |[[code]](https://github.com/Shark-NLP/DiffuSeq)![](https://img.shields.io/github/stars/Shark-NLP/DiffuSeq.svg?style=social) |ICLR 2023|
|2022.10| Variable Length |[**SSD-LM**] SSD-LM: Semi-autoregressive Simplex-based Diffusion Language Model for Text Generation and Modular Control (@UW)| [[pdf]](https://arxiv.org/pdf/2210.17432) |[[code]](https://github.com/xhan77/SSD-LM)![](https://img.shields.io/github/stars/xhan77/SSD-LM.svg?style=social) |ACL 2023|
|2023.05| Variable Length |[**AR-Diffusion**] AR-Diffusion: Auto-Regressive Diffusion Model for Text Generation (@THU)| [[pdf]](https://arxiv.org/pdf/2305.09515) |[[code]](https://github.com/wutong4012/AR-Diffusion)![](https://img.shields.io/github/stars/wutong4012/AR-Diffusion.svg?style=social) |NeurIPS 2023|
|2025.08| Variable Length |[**DAEDAL**] Beyond Fixed: Training-Free Variable-Length Denoising for Diffusion Large Language Models (@CUHK)| [[pdf]](https://arxiv.org/pdf/2508.14896) |[[code]](https://github.com/Li-Jinsong/DAEDAL)![](https://img.shields.io/github/stars/Li-Jinsong/DAEDAL.svg?style=social) |arXiv|
|2025.08| Variable Length |[**Dream 7B**] Dream 7B: Diffusion Large Language Models (@HKU)| [[pdf]](https://arxiv.org/pdf/2508.15487) |[[code]](https://github.com/HKUNLP/Dream)![](https://img.shields.io/github/stars/HKUNLP/Dream.svg?style=social) |arXiv|
|2025.09| Variable Length |[**FlexMDM**] Any-Order Flexible Length Masked Diffusion (@Harvard)| [[pdf]](https://arxiv.org/pdf/2509.01025) |[[code]](https://github.com/brianlck/FlexMDM)![](https://img.shields.io/github/stars/brianlck/FlexMDM.svg?style=social) |arXiv|
|2025.10| Variable Length |[**dLLM-Var**] Diffusion LLM with Native Variable Generation Lengths: Let [EOS] Lead the Way (@SJTU)| [[pdf]](https://arxiv.org/pdf/2510.24605) |[[code]](https://github.com/maomaocun/dLLM-Var)![](https://img.shields.io/github/stars/maomaocun/dLLM-Var.svg?style=social) |arXiv|
|2025.10| Variable Length |[**OneFlow**] OneFlow: Concurrent Mixed-Modal and Interleaved Generation with Edit Flows (@Meta)| [[pdf]](https://arxiv.org/pdf/2510.03506) | |arXiv|
|2025.11| Variable Length |[**ODB-dLLM**] Orchestrating Dual-Boundaries: An Arithmetic Intensity Inspired Acceleration Framework for Diffusion Language Models (@PKU)| [[pdf]](https://arxiv.org/pdf/2511.21759) |[[code]](https://github.com/PKU-SEC-Lab/ODB-dLLM)![](https://img.shields.io/github/stars/PKU-SEC-Lab/ODB-dLLM.svg?style=social) |arXiv|


## 📙 Contextual Scalability | Long Context
<div id="Long"></div> 

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2024.07| Long Context |[**DDLM-Sum**] Discrete Diffusion Language Model for Efficient Text Summarization (@VinUni)| [[pdf]](https://arxiv.org/pdf/2407.10998) | |NAACL 2025|
|2025.03| Long Context |[**Block Diffusion**] Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models (@Cornell)| [[pdf]](https://arxiv.org/pdf/2503.09573) |[[code]](https://github.com/kuleshov-group/BD3-LMs)![](https://img.shields.io/github/stars/kuleshov-group/BD3-LMs.svg?style=social) |ICLR 2025|
|2025.05| Long Context |[**Dimple**] Dimple: Discrete Diffusion Multimodal Large Language Model with Parallel Decoding (@NUS)| [[pdf]](https://arxiv.org/pdf/2505.16990) |[[code]](https://github.com/yu-rp/Dimple)![](https://img.shields.io/github/stars/yu-rp/Dimple.svg?style=social) |arXiv|
|2025.05| Long Context |[**CtrlDiff**] CtrlDiff: Boosting Large Diffusion Language Models with Dynamic Block Prediction and Controllable Generation (@PKU)| [[pdf]](https://arxiv.org/pdf/2505.14455) | |arXiv|
|2025.06| Long context |[**LongLLaDA**] LongLLaDA: Unlocking Long Context Capabilities in Diffusion LLMs (@FDU)| [[pdf]](https://arxiv.org/pdf/2506.14429) |[[code]](https://github.com/OpenMOSS/LongLLaDA)![](https://img.shields.io/github/stars/OpenMOSS/LongLLaDA.svg?style=social) |AAAI 2026|
|2025.09| Long Context |[**Fast-dLLM v2**] Fast-dLLM v2: Efficient Block-Diffusion LLM (@NVIDIA)| [[pdf]](https://arxiv.org/pdf/2509.26328) |[[code]](https://github.com/NVlabs/Fast-dLLM)![](https://img.shields.io/github/stars/NVlabs/Fast-dLLM.svg?style=social) |ICLR 2026|
|2025.09| Long Context |[**AdaBlock-dLLM**] AdaBlock-dLLM: Semantic-Aware Diffusion LLM Inference via Adaptive Block Size (@ICL)| [[pdf]](https://arxiv.org/pdf/2509.26432) | [[code]](https://github.com/lgxi24/AdaBlock-dLLM)![](https://img.shields.io/github/stars/lgxi24/AdaBlock-dLLM.svg?style=social)|ICLR 2026|
|2025.10| Long Context |[**Rainbow Padding**] Rainbow Padding: Mitigating Early Termination in Instruction-Tuned Diffusion LLMs (@Yonsei)| [[pdf]](https://arxiv.org/pdf/2510.03680) |[[code]](https://github.com/quasar529/rainbow-padding)![](https://img.shields.io/github/stars/quasar529/rainbow-padding.svg?style=social) |ICLR 2026|
|2025.10| Long Context |[**UltraLLaDA**] UltraLLaDA: Scaling the Context Length to 128K for Diffusion Large Language Models (@HKUST)| [[pdf]](https://arxiv.org/pdf/2510.10481) |[[code]](https://github.com/Relaxed-System-Lab/UltraLLaDA)![](https://img.shields.io/github/stars/Relaxed-System-Lab/UltraLLaDA.svg?style=social) |ICLR 2026|


## 📙 System Framework
<div id="Framework"></div> 

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.10| Pre-training \& evaluation |[**dllm**] dLLM: Simple Diffusion Language Modeling (@UCB)| [[pdf]](https://arxiv.org/pdf/2602.22661) |[[code]](https://github.com/ZHZisZZ/dllm)![](https://img.shields.io/github/stars/ZHZisZZ/dllm.svg?style=social) |arXiv|
|2025.10| Evaluation |[**Latency**] How Efficient Are Diffusion Language Models? A Critical Examination of Efficiency Evaluation Practices (@RUC)| [[pdf]](https://arxiv.org/pdf/2510.18480) | |arXiv|
|2025.10| Evaluation |[**ParallelBench**] ParallelBench: Understanding the Trade-offs of Parallel Decoding in Diffusion LLMs (@FuriosaAI)| [[pdf]](https://arxiv.org/pdf/2510.04767) |[[code]](https://github.com/furiosa-ai/ParallelBench)![](https://img.shields.io/github/stars/furiosa-ai/ParallelBench.svg?style=social) |ICLR2026|
|2025.12| Post-training |[**DiRL**] An Efficient Post-Training Framework for Diffusion Language Models (@FDU)| [[pdf]](https://arxiv.org/pdf/2512.22234) |[[code]](https://github.com/OpenMOSS/DiRL)![](https://img.shields.io/github/stars/OpenMOSS/DiRL.svg?style=social) |arXiv|
|2026.03| Post-training |[**StableDRL**] Stabilizing Reinforcement Learning for Diffusion Language Models (@CUHK-SZ)| [[pdf]](https://arxiv.org/pdf/2603.06743) | |arXiv|
|2026.03| Evaluation |[**AR vs MDLM**] Autoregressive vs. Masked Diffusion Language Models: A Controlled Comparison (@Independent)| [[pdf]](https://arxiv.org/pdf/2603.22075) |[[code]](https://github.com/caiovicentino/arche)![](https://img.shields.io/github/stars/caiovicentino/arche.svg?style=social) |arXiv|
|2025.10| Serving |[**dInfer**] dInfer: An Efficient Inference Framework for Diffusion Language Models (@Ant)| [[pdf]](https://arxiv.org/pdf/2510.08666) |[[code]](https://github.com/inclusionAI/dInferL)![](https://img.shields.io/github/stars/inclusionAI/dInfer.svg?style=social) |arXiv|
|2025.12| Serving |[**dLLM-Serve**] Taming the Memory Footprint Crisis: System Design for Production Diffusion LLM Serving (@Virginia Tech)| [[pdf]](https://arxiv.org/pdf/2512.17077) |[[code]](https://github.com/chosen-ox/dLLM-Serve)![](https://img.shields.io/github/stars/chosen-ox/dLLM-Serve.svg?style=social) |arXiv|
|2025.12| Serving |[**SGLang**] Power Up Diffusion LLMs: Day‑0 Support for LLaDA 2.0 (@SGLang)| [[blog]](https://lmsys.org/blog/2025-12-19-diffusion-llm/) |[[code]](https://github.com/sgl-project/sglang)![](https://img.shields.io/github/stars/sgl-project/sglang.svg?style=social) |arXiv|



## 📙 Multimodal DLM
<div id="MDLM"></div> 

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.05| Training & Inference Stage |[**Dimple**] Dimple: Discrete Diffusion Multimodal Large Language Model with Parallel Decoding (@NUS)| [[pdf]](https://arxiv.org/pdf/2505.16990) |[[code]](https://github.com/yu-rp/Dimple)![](https://img.shields.io/github/stars/yu-rp/Dimple.svg?style=social) |arXiv|
|2025.12| Training Stage |[**SDAR-VL**] SDAR-VL: Stable and Efficient Block-wise Diffusion for Vision-Language Understanding (@ZJU)| [[pdf]](https://arxiv.org/pdf/2512.14068) |[[code]](https://github.com/JetAstra/SDAR-VL)![](https://img.shields.io/github/stars/JetAstra/SDAR-VL.svg?style=social) |arXiv|
|2025.10| Inference Stage |[**Lumina-DiMOO**] Lumina-DiMOO: An Omni Diffusion Large Language Model for Multi-Modal Generation and Understanding (@Shanghai AI Lab)| [[pdf]](https://arxiv.org/pdf/2510.06308) |[[code]](https://github.com/Alpha-VLLM/Lumina-DiMOO)![](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-DiMOO.svg?style=social) |arXiv|
|2025.11| Inference Stage |[**D3ToM**] D3ToM: Decider-Guided Dynamic Token Merging for Accelerating Diffusion MLLMs (@SJTU)| [[pdf]](https://arxiv.org/pdf/2511.12280) |[[code]](https://github.com/bcmi/D3ToM-Diffusion-MLLM)![](https://img.shields.io/github/stars/bcmi/D3ToM-Diffusion-MLLM.svg?style=social) |AAAI 2026|
|2025.11| Inference Stage |[**Token-Pruning**] A Comprehensive Study on Visual Token Redundancy for Discrete Diffusion-based Multimodal Large Language Models (@NTU)| [[pdf]](https://arxiv.org/pdf/2511.15098) | |arXiv|
|2025.12| Inference Stage |[**Sparse-LaViDa**] Sparse-LaViDa: Sparse Multimodal Discrete Diffusion Language Models (@Adobe)| [[pdf]](https://arxiv.org/pdf/2512.14008) | |arXiv|
|2026.02| Inference Stage |[**FreeCorrection**] Training-Free Self-Correction for Multimodal Masked Diffusion Models (@UCLA)| [[pdf]](https://arxiv.org/pdf/2602.02927) |[[code]](https://github.com/huge123/FreeCorrection)![](https://img.shields.io/github/stars/huge123/FreeCorrection.svg?style=social) |arXiv|



## ©️Citations 

```BibTeX
@article{lin2026efficient,
  title={Efficient Diffusion Language Models: A Comprehensive Survey},
  author={Lin, Haokun and Jia, Xinle and Liu, Shaozhen and Xia, Shujun and Huang, Weitao and Xu, Haobo and Li, Junyang and Xiao, Yicheng and Xing, Xingrun and Guo, Ziyu and others},
  journal={Authorea Preprints},
  year={2026},
  publisher={Authorea}
}
```