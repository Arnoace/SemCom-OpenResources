# Semantic Communication Open Resources

A curated collection of research papers, open-source implementations, datasets, pretrained models, and research tools for Semantic Communication (SemCom).

This repository organizes open resources according to data modalities and research directions, aiming to facilitate literature exploration, algorithm development, and experimental reproduction.

## 1. Text-based Semantic Communication

Research on semantic representation, text transmission, language models, and semantic reconstruction.

### 1.1 Research Papers

| No. | Paper | Year | Core Contributions / Innovations | Models / Architectures | Channel / Communication Scheme | Paper Resources | GitHub Code Resources |
|---|---|---:|---|---|---|---|---|
| 1 | Deep Learning Enabled Semantic Communication Systems | 2021 | Proposes DeepSC, an end-to-end deep learning-based semantic communication framework that jointly learns semantic and channel encoding/decoding | Transformer | Jointly learned neural channel encoder/decoder; evaluates AWGN and Rayleigh fading channels | [DOI](https://doi.org/10.1109/TSP.2021.3071210) | [DeepSC](https://github.com/13274086/DeepSC) |
| 2 | Enhancing Deep Semantic Communication Systems (Deep-SC) using the Pre-trained Models BERT and BART | 2024 | Explores the integration of pretrained language models into DeepSC to improve semantic representation and text reconstruction | BERT, BART | Deep-SC-based semantic communication framework | [DOI](https://doi.org/10.1109/MI-STA61267.2024.10599693) | Not found |
| 3 | SEQ2SEQ-SC: End-To-End Semantic Communication Systems with Pre-Trained Language Model | 2023 | Integrates pretrained encoder-decoder Transformers into semantic communication; improves generalization to unseen text and introduces lexical and semantic similarity evaluation | BART-base, SBERT | 5G NR-compatible link-level simulation; Polar coding, 16-QAM, AWGN and Rayleigh fading | [DOI](https://doi.org/10.1109/IEEECONF59524.2023.10476895) · [PDF](https://www.jaypujara.org/pubs/2023/lee2023seq2seqsc.pdf) | Not found |
| 4 | GenSC: Generative Semantic Communication Systems Using BART-Like Model | 2024 | Explores generative semantic communication using a BART-like model for semantic encoding and text generation/reconstruction | BART-like encoder-decoder architecture | Semantic communication with a generative language model | [DOI](https://doi.org/10.1109/LCOMM.2024.3450309) | [GenSC](https://github.com/CTHMIT/gensc) |
| 5 | On the Uses of Large Language Models to Design End-to-End Learning Semantic Communication | 2024 | Investigates the use of large language models in designing end-to-end learning-based semantic communication systems | Large Language Models (LLMs) | End-to-end semantic communication | [DOI](https://doi.org/10.1109/WCNC57260.2024.10570717) | Not found |
| 6 | A Road Map for Utilizing SemCom on the Way to Breaking Traditional QoS Boundaries | 2026 | Discusses research directions and opportunities for applying semantic communication to move beyond traditional QoS-oriented communication | Semantic communication and large AI models | Semantic communication system and network perspectives | [DOI](https://doi.org/10.1109/ICC59461.2026.11588274) | Not found |

### 1.2 Datasets

| Dataset | Description | Related Work | Resource |
|---|---|---|---|
| European Parliament (Europarl) Corpus | Multilingual parallel corpus extracted from European Parliament proceedings; used for text data preparation and training in semantic communication experiments | DeepSC, SEQ2SEQ-SC | [Official Website](https://www.statmt.org/europarl/) |

### 1.3 Pretrained Models

| Model | Description | Related Work | Resource |
|---|---|---|---|
| BERT-base-multilingual-cased | Multilingual pretrained bidirectional Transformer model | BERT-based semantic representation and reconstruction research | [Hugging Face](https://huggingface.co/bert-base-multilingual-cased) |
| BART-base | Pretrained encoder-decoder Transformer model based on denoising sequence-to-sequence pretraining | SEQ2SEQ-SC and BART-based semantic communication | [Hugging Face](https://huggingface.co/facebook/bart-base) |

### 1.4 Research Tools and Literature Discovery

| Tool | Description | Resource |
|---|---|---|
| Connected Papers | Visual exploration of related academic papers and research connections | [Website](https://www.connectedpapers.com/) |
| OpenSemanticComm | Open-source resource collection related to semantic communication | [GitHub](https://github.com/yang-hsiao/OpenSemanticComm) |

## 2. Image-based Semantic Communication

Research on image semantic representation, feature extraction, transmission, and reconstruction.

### 2.1 Research Papers

Papers to be added.

### 2.2 Datasets and Pretrained Models

Resources to be added.

### 2.3 GitHub Implementations

Implementations to be added.

## 3. Speech-based Semantic Communication

Research on speech semantic representation, speech transmission, and reconstruction.

### 3.1 Research Papers

Papers to be added.

### 3.2 Datasets and Pretrained Models

Resources to be added.

### 3.3 GitHub Implementations

Implementations to be added.

## 4. Video-based Semantic Communication

Research on video semantic representation, temporal feature extraction, transmission, and reconstruction.

### 4.1 Research Papers

Papers to be added.

### 4.2 Datasets and Pretrained Models

Resources to be added.

### 4.3 GitHub Implementations

Implementations to be added.

## 5. Point Cloud-based Semantic Communication

Research on point cloud feature extraction, 3D semantic representation, compression, transmission, and reconstruction.

### 5.1 Research Papers

Papers to be added.

### 5.2 Datasets and Pretrained Models

Resources to be added.

### 5.3 GitHub Implementations

Implementations to be added.

## 6. Multimodal Semantic Communication

Research on joint semantic representation and transmission across multiple modalities, including text, images, speech, and video.

### 6.1 Research Papers

Papers to be added.

### 6.2 Datasets and Pretrained Models

Resources to be added.

### 6.3 GitHub Implementations

Implementations to be added.

## 7. Secure Semantic Communication

Research on privacy protection, confidentiality, adversarial attacks, robustness, and security mechanisms in semantic communication systems.

### 7.1 Research Papers

Papers to be added.

### 7.2 Datasets and Tools

Resources to be added.

### 7.3 GitHub Implementations

Implementations to be added.

## 8. Optical Semantic Communication

Research on semantic communication over optical communication systems and optical channels.

### 8.1 Research Papers

Papers to be added.

### 8.2 Datasets and Simulation Tools

Resources to be added.

### 8.3 GitHub Implementations

Implementations to be added.

## 9. Contributing

Contributions are welcome!

If you find relevant research papers, official implementations, reproductions, datasets, pretrained models, or tools, feel free to submit an issue or pull request.

Please provide the original paper or project link whenever possible. Clearly distinguish official implementations from third-party reproductions.

## Disclaimer

This repository is an independent research resource collection. All papers, code, datasets, and models belong to their respective authors and owners. Please refer to the original sources for licensing and usage conditions.
