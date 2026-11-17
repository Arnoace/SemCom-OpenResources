# Text-based Semantic Communication

This section collects research papers, implementations, datasets, pretrained models, and useful tools for text-based semantic communication.

## 1. Research Papers

| No. | Paper | Year | Research Focus | Paper Link |
|---|---|---|---|---|
| 1 | Deep Learning Enabled Semantic Communication Systems | 2021 | Transformer-based DeepSC for text transmission | [IEEE](https://doi.org/10.1109/TSP.2021.3071210) |
| 2 | Enhancing Deep Semantic Communication Systems (Deep-SC) using the Pre-trained Models BERT and BART | 2024 | Replacing components with pretrained BERT and BART models | [IEEE](https://doi.org/10.1109/MI-STA61267.2024.10599693) |
| 3 | Seq2SeqSC (Lee et al., 2023) | 2023 | Sequence-to-sequence-based semantic communication | Paper information to be verified |
| 4 | GenSC: Generative Semantic Communication Systems Using BART-Like Model | 2024 | Generative semantic decoding with BART-like models | [IEEE](https://doi.org/10.1109/LCOMM.2024.3450309) |
| 5 | A Road Map for Utilizing SemCom on the Way to Breaking Traditional QoS Boundaries | 2026 | Large AI models for semantic communication | [IEEE](https://doi.org/10.1109/ICC59461.2026.11588274) |
| 6 | On the Uses of Large Language Models to Design End-to-End Learning Semantic Communication | 2024 | LLM-based end-to-end semantic communication | [IEEE](https://doi.org/10.1109/WCNC57260.2024.10570717) |

## 2. Open-source Implementations

| Project | Related Paper | Code | Notes |
|---|---|---|---|
| DeepSC | Deep Learning Enabled Semantic Communication Systems | [GitHub](https://github.com/13274086/DeepSC) | PyTorch implementation |
| GenSC | GenSC: Generative Semantic Communication Systems Using BART-Like Model | [GitHub](https://github.com/CTHMIT/gensc) | Official project repository |

## 3. Datasets

### Europarl Corpus

- **Dataset:** [Europarl Parallel Corpus](https://www.statmt.org/europarl/)
- **Used by:** DeepSC
- **Description:** A multilingual parallel corpus extracted from European Parliament proceedings.
- **Purpose:** Used as text data for training and evaluating semantic communication systems.

## 4. Pretrained Models

### BERT

- **Model:** [bert-base-multilingual-cased](https://huggingface.co/bert-base-multilingual-cased)
- **Platform:** Hugging Face
- **Description:** A multilingual pretrained BERT model.
- **Usage:** Can be used for tokenization, contextual representation, and language modeling-related tasks.

### BART

- **Model:** [BART](https://huggingface.co/facebook/bart-base)
- **Platform:** Hugging Face
- **Description:** A pretrained sequence-to-sequence denoising autoencoder.
- **Usage:** Useful for text reconstruction and generative semantic decoding research.

## 5. Research and Code Discovery

| Resource | Description | Link |
|---|---|---|
| Connected Papers | Explore related papers through a visual similarity graph | [Website](https://www.connectedpapers.com/) |
| OpenSemanticComm | Open-source code collection for semantic communication research | [GitHub](https://github.com/yang-hsiao/OpenSemanticComm) |

## 6. Notes

- Paper links point to publisher or DOI pages whenever available.
- Code links should be checked against the original authors' repositories.
- Dataset and pretrained model links are provided for research and reproduction purposes.
- Please refer to the original sources for licensing and usage conditions.
