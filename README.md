

# 🧠 Awesome Visual Reasoning Datasets

<p align="center"> <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a> <a href="https://github.com/awesome-ai/awesome-visual-reasoning/stargazers"><img src="https://img.shields.io/github/stars/awesome-ai/awesome-visual-reasoning?style=social" alt="GitHub Stars"></a> <a href="https://github.com/awesome-ai/awesome-visual-reasoning/pulls"><img src="https://img.shields.io/github/issues-pr/awesome-ai/awesome-visual-reasoning" alt="Pull Requests"></a> <a href="http://creativecommons.org/publicdomain/zero/1.0/"><img src="https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg" alt="License: CC0-1.0"></a> </p>

> 💡 **Visual reasoning** refers to the ability of AI systems to **infer, interpret, and reason** about visual information beyond perception.
> This repository curates high-quality datasets across multiple reasoning domains — math, science, spatial, commonsense, and multimodal logic — to support **VLM** and **reasoning model research**.

-----

## 📖 Table of Contents

  * [🧮 Mathematical Reasoning](https://www.google.com/search?q=%23-mathematical-reasoning)
  * [🔬 Scientific Reasoning](https://www.google.com/search?q=%23-scientific-reasoning)
  * [📐 Spatial & Geometric Reasoning](https://www.google.com/search?q=%23-spatial--geometric-reasoning)
  * [🧩 Commonsense Reasoning](https://www.google.com/search?q=%23-commonsense-reasoning)
  * [📊 Chart, Diagram & Figure Reasoning](https://www.google.com/search?q=%23-chart-diagram--figure-reasoning)
  * [🌆 Scene & Object Understanding](https://www.google.com/search?q=%23-scene--object-understanding)
  * [💬 Multimodal Logical Reasoning](https://www.google.com/search?q=%23-multimodal-logical-reasoning)
  * [🧱 Synthetic & Programmatic Datasets](https://www.google.com/search?q=%23-synthetic--programmatic-datasets)
  * [🔗 Hybrid Datasets](https://www.google.com/search?q=%23-hybrid-datasets)
  * [📚 References](https://www.google.com/search?q=%23-references)
  * [🤝 Contributing](https://www.google.com/search?q=%23-contributing)
  * [🪶 Citation](https://www.google.com/search?q=%23-citation)

-----

## 🧮 Mathematical Reasoning

| Name | Data Size | Description | Modality | Task Type | Paper Link 📄 | Hugging Face Link 🤗 |
|---|---|---|---|---|---|---|
| **GeoQA** | 5.8k | Geometry problem-solving with diagram understanding. | Diagram + Text | Diagram QA | [Paper 📄](https://arxiv.org/abs/2105.00530) | [Link 🤗](https://huggingface.co/datasets/TAL-AI/GeoQA) |
| **We-Math 2.0** | N/A | Unified MathBook system with RL-based multimodal reasoning tasks. | Image + Text | CoT, RL fine-tuning | [Paper 📄](https://arxiv.org/abs/2508.10433) | [Link 🤗](https://huggingface.co/datasets/we-math/WeMath2.0) |
| **MM-MathInstruct** | N/A | Instruction-tuning dataset for multimodal math reasoning models. | Image + Text | Instruction tuning | N/A | [Link 🤗](https://huggingface.co/MathLLMs/MM-MathInstruct) |
| **Geo170K** | \~170K | Large synthetic geometric dataset for diagram-based QA and reasoning. | Image + Text | Geometry QA | [Paper 📄](https://arxiv.org/abs/2404.09341) | [Link 🤗](https://huggingface.co/datasets/G-LLaVA/Geo170K) |

-----

## 🔬 Scientific Reasoning

| Name | Data Size | Description | Modality | Task Type | Paper Link 📄 | Hugging Face Link 🤗 |
|---|---|---|---|---|---|---|
| **ScienceQA** | 21k | Multimodal QA over science topics (images, diagrams, text). | Image + Text | QA + Explanation | [Website 🌐](https://scienceqa.github.io/) | [Link 🤗](https://huggingface.co/datasets/derek-thomas/ScienceQA) |
| **AI2D** | 5k | Diagram-based QA for scientific diagram understanding. | Diagram + Text | Diagram QA | [Website 🌐](https://allenai.org/data/ai2d) | [Link 🤗](https://huggingface.co/datasets/allenai/ai2d) |
| **ScienceDiagramsQA** | 7k | Diagram-centric reasoning dataset in science. | Diagram + Text | QA | [GitHub 📄](https://github.com/SciQA/ScienceDiagramsQA) | N/A |
| **TQA (TextbookQA)** | 26k | QA derived from textbooks combining text and diagrams. | Diagram + Text | Text + Diagram QA | [Website 🌐](https://allenai.org/data/tqa) | N/A |

-----

## 📐 Spatial & Geometric Reasoning

| Name | Data Size | Description | Modality | Task Type | Paper Link 📄 | Hugging Face Link 🤗 |
|---|---|---|---|---|---|---|
| **CLEVR** | 100k | Synthetic dataset testing compositional visual reasoning. | Image | Visual QA | [Website 🌐](https://cs.stanford.edu/people/jcjohns/clevr/) | [Link 🤗](https://huggingface.co/datasets/clevr) |
| **GQA** | 22M | Real-world compositional reasoning dataset. | Image | Scene QA | [Website 🌐](https://cs.stanford.edu/people/dorarad/gqa/index.html) | [Link 🤗](https://huggingface.co/datasets/gqa) |
| **ShapeWorld** | Variable | Synthetic shapes dataset for abstract reasoning. | Image | Description QA | [Paper 📄](https://arxiv.org/abs/1704.04517) | N/A |
| **CoGenT** | 100k | CLEVR variant testing compositional generalization. | Image | Generalization QA | [Website 🌐](https://cs.stanford.edu/people/jcjohns/clevr/) | N/A |

-----

## 🧩 Commonsense Reasoning

| Name | Data Size | Description | Modality | Task Type | Paper Link 📄 | Hugging Face Link 🤗 |
|---|---|---|---|---|---|---|
| **VCR** | 290k | Visual commonsense reasoning over images and text. | Image + Text | QA + Rationale | [Website 🌐](https://visualcommonsense.com/) | [Link 🤗](https://huggingface.co/datasets/visualcommonsense/VCR) |
| **OK-VQA** | 14k | QA requiring commonsense knowledge beyond the image. | Image + Text | Open QA | [Website 🌐](https://okvqa.allenai.org/) | [Link 🤗](https://huggingface.co/datasets/okvqa) |
| **A-OKVQA** | 25k | Extended OK-VQA with multiple-choice and rationale explanations. | Image + Text | QA + Rationale | [Website 🌐](https://allenai.org/project/a-okvqa) | [Link 🤗](https://huggingface.co/datasets/a-okvqa) |

-----

## 📊 Chart, Diagram & Figure Reasoning

| Name | Data Size | Description | Modality | Task Type | Paper Link 📄 | Hugging Face Link 🤗 |
|---|---|---|---|---|---|---|
| **ChartQA** | 20k | Reasoning over charts with natural language questions. | Chart + Text | Chart QA | [Paper 📄](https://arxiv.org/abs/2203.10244) | [Link 🤗](https://huggingface.co/datasets/vis-nlp/ChartQA) |
| **FigureQA** | 100k | Synthetic figure reasoning via attribute comparison. | Chart | Figure reasoning | [Paper 📄](https://arxiv.org/abs/1710.07300) | N/A |
| **PlotQA** | 28k | Real-world plot-based QA emphasizing data reasoning. | Chart + Text | Data reasoning QA | [Paper 📄](https://arxiv.org/abs/2004.00494) | N/A |
| **DVQA** | 3M | Bar chart reasoning with compositional questions. | Chart + Text | Chart QA | [Paper 📄](https://arxiv.org/abs/1801.08163) | N/A |
| **DUDE** | \~1M | A large-scale multimodal dataset for Document Understanding, Detection, and Extraction. | Document + Text | Document parsing, VQA | [Paper 📄](https://arxiv.org/abs/2311.16109) | [Link 🤗](https://www.google.com/search?q=https://huggingface.co/datasets/HuggingFaceM4/DUDE) |
| **All-Doc-VQA** | \~1M | A large-scale collection of 10 document VQA datasets, unified for instruction tuning. | Document + Text | Document VQA, Instruction tuning | N/A | [Link 🤗](https://www.google.com/search?q=https://huggingface.co/datasets/HuggingFaceM4/all-doc-vqa-1m) |
| **DocVQA** | \~50K | Visual QA on single document images, requiring reading and understanding text. | Document + Text | Document VQA | [Paper 📄](https://arxiv.org/abs/1907.00490) | [Link 🤗](https://www.google.com/search?q=https://huggingface.co/datasets/HuggingFaceM4/DocVQA) |
| **InfographicsVQA** | \~5.5K | VQA dataset focused on infographics, requiring reasoning about charts, text, and layout. | Document + Text | Document VQA | [Paper 📄](https://www.google.com/search?q=https://arxiv.org/abs/2105.02795) | [Link 🤗](https://www.google.com/search?q=https://huggingface.co/datasets/HuggingFaceM4/InfographicsVQA) |

-----

## 🌆 Scene & Object Understanding

| Name | Data Size | Description | Modality | Task Type | Paper Link 📄 | Hugging Face Link 🤗 |
|---|---|---|---|---|---|---|
| **Visual7W** | 327k | Visual QA emphasizing grounding and reasoning. | Image + Text | QA | [Website 🌐](https://ai.stanford.edu/~yukez/visual7w/) | N/A |
| **VQA v2** | 1.1M | Large-scale benchmark with diverse reasoning types. | Image + Text | QA | [Website 🌐](https://visualqa.org/) | [Link 🤗](https://huggingface.co/datasets/vqa) |
| **VizWiz** | 31k | Real-world dataset from blind users' photos. | Image + Text | QA | [Website 🌐](https://vizwiz.org/) | [Link 🤗](https://huggingface.co/datasets/vizwiz) |

-----

## 💬 Multimodal Logical Reasoning

| Name | Data Size | Description | Modality | Task Type | Paper Link 📄 | Hugging Face Link 🤗 |
|---|---|---|---|---|---|---|
| **VisDial** | 120k | Dialogue-based visual reasoning. | Image + Dialogue | Dialog reasoning | [Website 🌐](https://visualdialog.org/) | [Link 🤗](https://huggingface.co/datasets/visdial) |
| **IconQA** | 40k | IQ-test style reasoning with diagrams and analogies. | Diagram + Text | Analogy QA | [Website 🌐](https://iconqa.github.io/) | N/A |
| **RAVEN** | 70k | Abstract reasoning inspired by Raven’s Progressive Matrices. | Diagram | Abstract reasoning | [Paper 📄](https://arxiv.org/abs/1903.02741) | N/A |
| **I-RAVEN** | 100k | Improved RAVEN dataset with diverse pattern distributions. | Diagram | Logical reasoning | [Paper 📄](https://arxiv.org/abs/2007.03058) | N/A |

-----

## 🧱 Synthetic & Programmatic Datasets

| Name | Data Size | Description | Modality | Task Type | Paper Link 📄 | Hugging Face Link 🤗 |
|---|---|---|---|---|---|---|
| **CLEVRER** | 20k | Video-based causal reasoning extension of CLEVR. | Video + Text | Causal reasoning | [Website 🌐](https://clevrer.csail.mit.edu/) | N/A |
| **IntPhys** | 10k | Tests intuitive physics understanding. | Video | Physical reasoning | [Website 🌐](https://intphys.com/) | N/A |
| **PhysicalIQ** | 12k | Visual reasoning about physical interactions and stability. | Image + Video | Physics QA | [Website 🌐](https://physicaliq.github.io/) | N/A |

-----

## 🔗 Hybrid Datasets

> This section includes large-scale instruction-tuning datasets, document-centric datasets, and hybrid collections used for pretraining and fine-tuning general-purpose VLMs.

| Name | Data Size | Description | Modality | Task Type | Paper Link 📄 | Hugging Face Link 🤗 |
|---|---|---|---|---|---|---|
| **MMR1** | Millions | Multimodal long-chain-of-thought reasoning dataset designed for SFT and RL training pipelines. | Image + Text | Long CoT QA | [Paper 📄](https://arxiv.org/abs/2509.21268) | [Link 🤗](https://huggingface.co/datasets/MMR1) |
| **Vision-G1** | N/A | Multi-domain reasoning dataset (46 sources: math, spatial, GUI, commonsense, etc.) curated for RL-based training and evaluation. | Image + Text | Multimodal QA, RL training | [Paper 📄](https://arxiv.org/abs/2410.11890) | [Link 🤗](https://huggingface.co/datasets/vision-g1) |
| **FineVision** | 17M+ images | Large-scale open multimodal corpus covering VQA, OCR, charts, GUI, and more. Designed for pretraining and instruction tuning. | Image + Text | Multimodal QA, GUI, OCR | N/A | [Link 🤗](https://huggingface.co/datasets/HuggingFaceM4/FineVision) |
| **LLaVA-OneVision (1.5)** | 85M pretrain | Fully open LMM training framework and corpora, including pretraining and instruction datasets (OneVision-1.5 family). | Image + Text | Pretraining, Instruction tuning | [Paper 📄](https://arxiv.org/abs/2509.23661) | [Collection 🤗](https://huggingface.co/collections/liuhaotian/llava-onevision-1.5-66f1d5e5e7c3c9a58b98600a) |
| **LLaVA-OneVision-1.5-Instruct** | Millions | Instruction-tuning subset (SFT splits) from the OneVision family for efficient multimodal instruction tuning. | Image + Text | Visual instruction tuning | [Paper 📄](https://arxiv.org/abs/2509.23661) | [Link 🤗](https://huggingface.co/liuhaotian/LLaVA-OneVision-1.5-Instruct) |
| **Infinity-MM** | Tens of millions | Large multimodal instruction dataset (by BAAI) with tens of millions of curated, high-quality instruction samples for VLM scaling. | Image + Text | Instruction tuning, QA | N/A | [Link 🤗](https://huggingface.co/datasets/BAAI/Infinity-MM) |
| **Cambrian-10M** | \~10M | 10M multimodal instruction samples balancing visual and linguistic signals for robust instruction tuning. | Image + Text | Instruction tuning | [Paper 📄](https://arxiv.org/abs/2406.16860) | [Link 🤗](https://huggingface.co/datasets/nyu-visionx/Cambrian-10M) |
| **MAmmoTH-VL-Instruct** | \~12M | Multimodal dataset family for visual reasoning and instruction tuning (e.g., MAmmoTH-VL-Instruct-12M). | Image + Text | Pretraining, Instruction tuning | [Paper 📄](https://arxiv.org/abs/2412.05237) | [Link 🤗](https://huggingface.co/datasets/MAmmoTH-VL/MAmmoTH-VL-Instruct-12M) |
| **CoSyn-400K** | 400K | Procedurally generated synthetic image–QA pairs for enhancing VQA diversity and robustness. | Synthetic Image + Text | Synthetic QA generation | [Paper 📄](https://arxiv.org/abs/2502.14846) | [Link 🤗](https://huggingface.co/datasets/allenai/CoSyn-400K) |
| **LLaVA-Instruct-150K** | \~150K | Core instruction tuning dataset for LLaVA, mixing VQA, CoT, and conversation. | Image + Text | Visual instruction tuning | [Paper 📄](https://arxiv.org/abs/2304.08485) | [Link 🤗](https://www.google.com/search?q=https://huggingface.co/datasets/liuhaotian/llava_instruct_150k) |
| **LLaVA-CoT-100K** | \~100K | Dataset for training VLMs to conduct autonomous multistage reasoning (summary, visual interpretation, logical reasoning, conclusion). | Image + Text | Visual CoT, Instruction tuning | [Paper 📄](https://www.google.com/search?q=httpshttps://arxiv.org/abs/2411.10440) | [Link 🤗](https://huggingface.co/datasets/Xkev/LLaVA-CoT-100k) |
| **ShareGPT-4V** | 100K | High-quality, detailed image descriptions and conversations generated by GPT-4V for instruction tuning. | Image + Text | Visual instruction tuning | [Paper 📄](https://arxiv.org/abs/2311.12713) | [Link 🤗](https://www.google.com/search?q=https://huggingface.co/datasets/Lin-Chen/ShareGPT-4V) |
| **LRV-Instruction** | \~350K | A large-scale benchmark for evaluating and training on long-range visual-language tasks. | Image + Text | Long-range instruction tuning | [Paper 📄](https://arxiv.org/abs/2403.18039) | [Link 🤗](https://www.google.com/search?q=https://huggingface.co/datasets/kaist-lvis/LRV-Instruction) |
| **MiniGPT-4 Instruct** | \~5K | Curated instruction-following data used for the alignment stage of MiniGPT-4. | Image + Text | Visual instruction tuning | [Paper 📄](https://arxiv.org/abs/2304.10592) | [Link 🤗](https://www.google.com/search?q=https://huggingface.co/datasets/Vision-CAIR/minigpt_4_instruct_data) |
| **InternVL-Chat-SFT** | 590K | Instruction tuning data from the InternVL 1.5 model, covering general VQA, OCR, and reasoning. | Image + Text | Visual instruction tuning | [Paper 📄](https://arxiv.org/abs/2405.05047) | [Link 🤗](https://www.google.com/search?q=https://huggingface.co/datasets/OpenDataLab/InternVL-Chat-SFT-590K) |

-----

## 📚 References

  * **Surveys**
      * [A Survey on Visual Reasoning (2023)](https://arxiv.org/abs/2306.04862)
      * [Multimodal Reasoning in VLMs (2024)](https://arxiv.org/abs/2402.08000)

-----

## 🤝 Contributing

Contributions are warmly welcome\! 💛
Please open an **issue** or **pull request** to:

  * Add new visual reasoning datasets
  * Update dataset metadata or Hugging Face links
  * Suggest improved classification or structure

-----

## 🪶 Citation

```bibtex
@misc{awesome_visual_reasoning,
  title={Awesome Visual Reasoning Datasets},
  author={Yun Zhu},
  year={2025},
  url={https.github.com/awesome-ai/awesome-visual-reasoning}
}
```
