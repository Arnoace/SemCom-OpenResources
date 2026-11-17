# 语义通信开源资源

语义通信（SemCom）研究论文、开源实现、数据集、预训练模型与研究工具的精选合集。

本仓库按数据模态与研究方向整理开源资源，旨在促进文献调研、算法开发与实验复现。

- [语义通信开源资源](#语义通信开源资源)
  - [1. 基于文本的语义通信](#1-基于文本的语义通信)
    - [1.1 研究论文](#11-研究论文)
    - [1.2 数据集](#12-数据集)
    - [1.3 预训练模型](#13-预训练模型)
    - [1.4 研究工具与文献发现](#14-研究工具与文献发现)
  - [2. 基于图像的语义通信](#2-基于图像的语义通信)
    - [2.1 研究论文](#21-研究论文)
    - [2.2 数据集与预训练模型](#22-数据集与预训练模型)
    - [2.3 GitHub 实现](#23-github-实现)
  - [3. 基于语音的语义通信](#3-基于语音的语义通信)
    - [3.1 研究论文](#31-研究论文)
    - [3.2 数据集与预训练模型](#32-数据集与预训练模型)
    - [3.3 GitHub 实现](#33-github-实现)
  - [4. 基于视频的语义通信](#4-基于视频的语义通信)
    - [4.1 研究论文](#41-研究论文)
    - [4.2 数据集与预训练模型](#42-数据集与预训练模型)
    - [4.3 GitHub 实现](#43-github-实现)
  - [5. 基于点云的语义通信](#5-基于点云的语义通信)
    - [5.1 研究论文](#51-研究论文)
    - [5.2 数据集与预训练模型](#52-数据集与预训练模型)
    - [5.3 GitHub 实现](#53-github-实现)
  - [6. 多模态语义通信](#6-多模态语义通信)
    - [6.1 研究论文](#61-研究论文)
    - [6.2 数据集与预训练模型](#62-数据集与预训练模型)
    - [6.3 GitHub 实现](#63-github-实现)
  - [7. 安全语义通信](#7-安全语义通信)
    - [7.1 研究论文](#71-研究论文)
    - [7.2 数据集与工具](#72-数据集与工具)
    - [7.3 GitHub 实现](#73-github-实现)
  - [8. 光学语义通信](#8-光学语义通信)
    - [8.1 研究论文](#81-研究论文)
    - [8.2 数据集与仿真工具](#82-数据集与仿真工具)
    - [8.3 GitHub 实现](#83-github-实现)
  - [9. 贡献指南](#9-贡献指南)
  - [免责声明](#免责声明)


## 1. 基于文本的语义通信

研究语义表示、文本传输、语言模型与语义重建。

### 1.1 研究论文

| 序号 | 论文 | 年份 | 核心贡献 / 创新点 | 模型 / 架构 | 信道 / 通信方案 | 论文资源 | GitHub 代码资源 |
|---|---|---:|---|---|---|---|---|
| 1 | Deep Learning Enabled Semantic Communication Systems | 2021 | Proposes DeepSC, an end-to-end deep learning-based semantic communication framework that jointly learns semantic and channel encoding/decoding | Transformer | Jointly learned neural channel encoder/decoder; evaluates AWGN and Rayleigh fading channels | [DOI](https://doi.org/10.1109/TSP.2021.3071210) | [DeepSC](https://github.com/13274086/DeepSC) |
| 2 | Enhancing Deep Semantic Communication Systems (Deep-SC) using the Pre-trained Models BERT and BART | 2024 | Explores the integration of pretrained language models into DeepSC to improve semantic representation and text reconstruction | BERT, BART | Deep-SC-based semantic communication framework | [DOI](https://doi.org/10.1109/MI-STA61267.2024.10599693) | 未找到 |
| 3 | SEQ2SEQ-SC: End-To-End Semantic Communication Systems with Pre-Trained Language Model | 2023 | Integrates pretrained encoder-decoder Transformers into semantic communication; improves generalization to unseen text and introduces lexical and semantic similarity evaluation | BART-base | 5G NR-compatible link-level simulation; Polar coding, 16-QAM, AWGN and Rayleigh fading | [DOI](https://doi.org/10.1109/IEEECONF59524.2023.10476895) · [PDF](https://www.jaypujara.org/pubs/2023/lee2023seq2seqsc.pdf) | 未找到 |
| 4 | GenSC: Generative Semantic Communication Systems Using BART-Like Model | 2024 | Explores generative semantic communication using a BART-like model for semantic encoding and text generation/reconstruction | BART-like encoder-decoder architecture | Semantic communication with a generative language model | [DOI](https://doi.org/10.1109/LCOMM.2024.3450309) | [GenSC](https://github.com/CTHMIT/gensc) |
| 5 | On the Uses of Large Language Models to Design End-to-End Learning Semantic Communication | 2024 | Investigates the use of large language models in designing end-to-end learning-based semantic communication systems | BART and GPT-2 models | End-to-end semantic communication | [DOI](https://doi.org/10.1109/WCNC57260.2024.10570717) | 未找到 |
| 6 | A Road Map for Utilizing SemCom on the Way to Breaking Traditional QoS Boundaries | 2026 | Discusses research directions and opportunities for applying semantic communication to move beyond traditional QoS-oriented communication | BART and GPT-2 models | Semantic communication system and network perspectives | [DOI](https://doi.org/10.1109/ICC59461.2026.11588274) | 未找到 |

### 1.2 数据集

| 数据集 | 描述 | 相关工作 | 资源 |
|---|---|---|---|
| European Parliament (Europarl) Corpus | 从欧洲议会议程中提取的多语言平行语料库，用于语义通信实验中的文本数据准备与训练 | DeepSC、SEQ2SEQ-SC | [官方网站](https://www.statmt.org/europarl/) |

### 1.3 预训练模型

| 模型 | 描述 | 相关工作 | 资源 |
|---|---|---|---|
| BERT-base-multilingual-cased | 多语言预训练双向 Transformer 模型 | 基于 BERT 的语义表示与重建研究 | [Hugging Face](https://huggingface.co/bert-base-multilingual-cased) |
| BART-base | 基于去噪序列到序列预训练的编码器-解码器 Transformer 预训练模型 | SEQ2SEQ-SC 与基于 BART 的语义通信 | [Hugging Face](https://huggingface.co/facebook/bart-base) |

### 1.4 研究工具与文献发现

| 工具 | 描述 | 资源 |
|---|---|---|
| Connected Papers | 以可视化方式探索相关学术论文与研究关联 | [网站](https://www.connectedpapers.com/) |
| OpenSemanticComm | 语义通信相关的开源资源集合 | [GitHub](https://github.com/yang-hsiao/OpenSemanticComm) |

## 2. 基于图像的语义通信

研究图像语义表示、特征提取、传输与重建。

### 2.1 研究论文

待补充论文。

### 2.2 数据集与预训练模型

待补充资源。

### 2.3 GitHub 实现

待补充实现。

## 3. 基于语音的语义通信

研究语音语义表示、语音传输与重建。

### 3.1 研究论文

待补充论文。

### 3.2 数据集与预训练模型

待补充资源。

### 3.3 GitHub 实现

待补充实现。

## 4. 基于视频的语义通信

研究视频语义表示、时序特征提取、传输与重建。

### 4.1 研究论文

待补充论文。

### 4.2 数据集与预训练模型

待补充资源。

### 4.3 GitHub 实现

待补充实现。

## 5. 基于点云的语义通信

研究点云特征提取、三维语义表示、压缩、传输与重建。

### 5.1 研究论文

待补充论文。

### 5.2 数据集与预训练模型

待补充资源。

### 5.3 GitHub 实现

待补充实现。

## 6. 多模态语义通信

研究跨多种模态（包括文本、图像、语音与视频）的联合语义表示与传输。

### 6.1 研究论文

待补充论文。

### 6.2 数据集与预训练模型

待补充资源。

### 6.3 GitHub 实现

待补充实现。

## 7. 安全语义通信

研究语义通信系统中的隐私保护、保密性、对抗攻击、鲁棒性与安全机制。

### 7.1 研究论文

待补充论文。

### 7.2 数据集与工具

待补充资源。

### 7.3 GitHub 实现

待补充实现。

## 8. 光学语义通信

研究光通信系统与光信道上的语义通信。

### 8.1 研究论文

待补充论文。

### 8.2 数据集与仿真工具

待补充资源。

### 8.3 GitHub 实现

待补充实现。

## 9. 贡献指南

欢迎贡献！

如果你发现了相关的研究论文、官方实现、复现代码、数据集、预训练模型或工具，欢迎提交 issue 或 pull request。

请尽可能提供原始论文或项目链接，并明确区分官方实现与第三方复现。

## 免责声明

本仓库是一个独立的研究资源集合。所有论文、代码、数据集与模型均归其各自的作者与所有者所有。请参阅原始来源以了解许可与使用条件。
