# 👩🤝🤖 awesome-llm-datasets
This repository is a collection of useful links related to datasets for Language Model models (LLMs) and Reinforcement Learning with Human Feedback (RLHF).

It includes a variety of open datasets, as well as tools, pre-trained models, and research papers that can help researchers and developers work with LLMs and RLHF from a data perspective.

Follow and star for the latest and greatest links related to datasets for LLMs and RLHF.

## Table of Contents

1. [📦 Datasets](#datasets)
    1. [📚 For pre-training](#for-pre-training)
        1. [2023](#2023)
        2. [Before 2023](#before-2023)
    2. [🗣️ For instruction-tuning](#for-instruction-tuning)
    3. [👩🤝🤖 For RLHF](#for-rlhf)
    4. [⚖️ For evaluation](#for-evaluation)
    5. [👽 For other purposes](#for-other-purposes)
2. [🦾 Models and their datasets](#models-and-their-datasets)
3. [🧰 Tools and methods](#tools-and-methods)
4. [📔 Papers](#papers)



## Datasets

### For pre-training

#### 2023

**[RedPajama Data](https://github.com/togethercomputer/RedPajama-Data)**:

1.2 Trillion tokens Dataset in English:

| Dataset       | Token Count |
|---------------|-------------|
| Commoncrawl   | 878 Billion        |
| C4            | 175 Billion        |
| GitHub        | 59 Billion         |
| Books         | 26 Billion         |
| ArXiv         | 28 Billion         |
| Wikipedia     | 24 Billion         |
| StackExchange | 20 Billion         |
| Total         | 1.2 Trillion      |

Also includes code for data preparation, deduplication, tokenization, and visualization.

Created by Ontocord.ai, MILA Québec AI Institute, ETH DS3Lab, Université de Montréal, Stanford Center for Research on Foundation Models (CRFM), Stanford Hazy Research research group and LAION.

#### Before 2023

### For instruction-tuning

### For RLHF & Alignment

### For evaluation

### For other purposes

## Models and their datasets

### LLaMA

Overview: A collection of open source foundation models ranging in size from 7B to 65B parameters
released by Meta AI.

License: Non-commercial bespoke (model), GPL-3.0 (code)

📝 [Release blog post](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)
📄 [arXiv publication](https://arxiv.org/abs/2302.13971)
🃏 [Model card](https://github.com/facebookresearch/llama/blob/main/MODEL_CARD.md)

### Vicuna

Overview: A 13B parameter open source chatbot model fine-tuned on LLaMA and ~70k ChatGPT
conversations that maintains 92% of ChatGPT’s performance and outperforms LLaMA and Alpaca.

License: Non-commercial bespoke license (model), Apache 2.0 (code).

📦 [Repo](https://github.com/lm-sys/FastChat#vicuna-weights)

📝 [Release blog post](https://vicuna.lmsys.org/)

🔗 [ShareGPT dataset](https://sharegpt.com/)

🤗 [Models](https://huggingface.co/lmsys)

🤖 [Gradio demo](https://chat.lmsys.org/)

### Dolly 2.0

Overview: A fully open source 12B parameter instruction-following LLM, fine-tuned on a
human-generated instruction dataset licensed for research and commercial use.

License: CC BY-SA 3.0 (model), CC BY-SA 3.0 (dataset), Apache 2.0 (code).

📦 [Repo](https://github.com/databrickslabs/dolly)

📝 [Release blog post](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm) 

🤗 [Models](https://huggingface.co/databricks)

### LLaVA
Overview: A multi-modal LLM that combines a vision encoder and Vicuna for general-purpose visual and
language understanding, with capabilities similar to GPT-4.

License: Non-commercial bespoke (model), CC BY NC 4.0 (dataset), Apache 2.0 (code).

📦 [Repo](https://github.com/haotian-liu/LLaVA)

📝 [Project homepage](https://llava-vl.github.io/)

📄 [arXiv publication](https://arxiv.org/abs/2304.08485)

🤗 [Dataset & models](https://huggingface.co/liuhaotian)

🤖 [Gradio demo](https://llava.hliu.cc/)

### StableLM

Overview: A suite of low-parameter (3B, 7B) LLMs trained on a new dataset built on The Pile, with
1.5 trillion tokens of content.

License: CC BY-SA-4.0 (models).

📦 [Repo](https://github.com/stability-AI/stableLM/)

📝 [Release blog post](https://stability.ai/blog/stability-ai-launches-the-first-of-its-stablelm-suite-of-language-models)

🤗 [Models](https://huggingface.co/stabilityai)

🤖 [Gradio demo](https://huggingface.co/spaces/stabilityai/stablelm-tuned-alpha-chat)

### Alpaca

Overview: A partially open source instruction-following model fine-tuned on LLaMA which is smaller and cheaper and performs similarly to GPT-3.5.

License: Non-commercial bespoke (model), CC BY-NC 4.0 (dataset), Apache 2.0 (code).

📝 [Release blog post](https://crfm.stanford.edu/2023/03/13/alpaca.html)

🤗 [Dataset](https://huggingface.co/datasets/tatsu-lab/alpaca)

## Tools and methods

## Papers


