# 🧠 Awesome Visual Reasoning Datasets

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  
[![Hugging Face](https://img.shields.io/badge/🤗-HuggingFace-yellow)](https://huggingface.co/) 
[![arXiv](https://img.shields.io/badge/arXiv-Resources-red)](https://arxiv.org/)  
[![Stars](https://img.shields.io/github/stars/awesome-ai/awesome-visual-reasoning?style=social)](https://github.com/awesome-ai/awesome-visual-reasoning/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/awesome-ai/awesome-visual-reasoning/pulls)
[![License](https://img.shields.io/github/license/awesome-ai/awesome-visual-reasoning)](LICENSE)

> 💡 *Visual reasoning* refers to the ability of AI systems to **infer, interpret, and reason** about visual information beyond perception.  
> This repository curates high-quality datasets across multiple reasoning domains — math, science, spatial, commonsense, and multimodal logic — to support **VLM** and **reasoning model research**.

---

## 📖 Table of Contents
- [🧮 Mathematical Reasoning](#-mathematical-reasoning)
- [🔬 Scientific Reasoning](#-scientific-reasoning)
- [📐 Spatial & Geometric Reasoning](#-spatial--geometric-reasoning)
- [🧩 Commonsense Reasoning](#-commonsense-reasoning)
- [📊 Chart, Diagram & Figure Reasoning](#-chart-diagram--figure-reasoning)
- [🌆 Scene & Object Understanding](#-scene--object-understanding)
- [💬 Multimodal Logical Reasoning](#-multimodal-logical-reasoning)
- [🧱 Synthetic & Programmatic Datasets](#-synthetic--programmatic-datasets)
- [🔗 Hybrid Datasets](#-hybrid)
- [📚 References](#-references)
- [🤝 Contributing](#-contributing)
- [🪶 Citation](#-citation)

---

<details open>
<summary><h2>🧮 Mathematical Reasoning</h2></summary>

| Dataset | Description | Source | Modality | Size | Task Type |
|----------|--------------|---------|-----------|------|-----------|
| **MathVista** | Integrates visual & textual math reasoning tasks (geometry, algebra, puzzles). | [🌐 Website](https://mathvista.github.io/) • [🤗 HF](https://huggingface.co/datasets/MathVista) | Image + Text | 6.5k | Multimodal QA |
| **GeoQA** | Geometry problem-solving with diagram understanding. | [GitHub](https://github.com/TAL-AI/GeoQA) • [🤗 HF](https://huggingface.co/datasets/TAL-AI/GeoQA) | Diagram + Text | 5.8k | Diagram QA |
| **MathVerse** | Complex visual-textual math reasoning with compositional logic. | [🌐 Website](https://mathverse.github.io/) | Image + Text | 12k | QA + CoT reasoning |
| **We-Math** | Large-scale step-by-step multimodal math reasoning dataset. | [🌐 Website](https://we-math.github.io/) • [🤗 HF](https://huggingface.co/datasets/we-math/WeMath) | Image + Text | 50k | Reasoning QA |
| **We-Math 2.0** | Unified MathBook system with RL-based multimodal reasoning tasks. | [🤗 HF](https://huggingface.co/datasets/we-math/WeMath2.0) | Image + Text | – | CoT, RL fine-tuning |
| **MM-MathInstruct** | Instruction-tuning dataset for multimodal math reasoning models. | [🤗 HF](https://huggingface.co/MathLLMs/MM-MathInstruct) | Image + Text | – | Instruction tuning |
| **Geo170K** | Large synthetic geometric dataset for diagram-based QA and reasoning. | [🤗 HF](https://huggingface.co/datasets/G-LLaVA/Geo170K) | Image + Text | ~170K | Geometry QA |

</details>

---

<details>
<summary><h2>🔬 Scientific Reasoning</h2></summary>

| Dataset | Description | Source | Modality | Size | Task Type |
|----------|-------------|---------|-----------|------|-----------|
| **ScienceQA** | Multimodal QA over science topics (images, diagrams, text). | [🌐 Website](https://scienceqa.github.io/) • [🤗 HF](https://huggingface.co/datasets/derek-thomas/ScienceQA) | Image + Text | 21k | QA + Explanation |
| **AI2D** | Diagram-based QA for scientific diagram understanding. | [🌐 Website](https://allenai.org/data/ai2d) • [🤗 HF](https://huggingface.co/datasets/allenai/ai2d) | Diagram + Text | 5k | Diagram QA |
| **ScienceDiagramsQA** | Diagram-centric reasoning dataset in science. | [GitHub](https://github.com/SciQA/ScienceDiagramsQA) | Diagram + Text | 7k | QA |
| **TQA (TextbookQA)** | QA derived from textbooks combining text and diagrams. | [🌐 Website](https://tqa.cs.washington.edu/) | Diagram + Text | 26k | Text + Diagram QA |

</details>

---

<details>
<summary><h2>📐 Spatial & Geometric Reasoning</h2></summary>

| Dataset | Description | Source | Modality | Size | Task Type |
|----------|-------------|---------|-----------|------|-----------|
| **CLEVR** | Synthetic dataset testing compositional visual reasoning. | [🌐 Website](https://cs.stanford.edu/people/jcjohns/clevr/) • [🤗 HF](https://huggingface.co/datasets/clevr) | Image | 100k | Visual QA |
| **GQA** | Real-world compositional reasoning dataset. | [🌐 Website](https://cs.stanford.edu/people/dorarad/gqa/index.html) • [🤗 HF](https://huggingface.co/datasets/gqa) | Image | 22M | Scene QA |
| **ShapeWorld** | Synthetic shapes dataset for abstract reasoning. | [GitHub](https://github.com/AlexKuhnle/ShapeWorld) | Image | Variable | Description QA |
| **CoGenT** | CLEVR variant testing compositional generalization. | [🌐 Website](https://cs.stanford.edu/people/jcjohns/clevr/) | Image | 100k | Generalization QA |

</details>

---

<details>
<summary><h2>🧩 Commonsense Reasoning</h2></summary>

| Dataset | Description | Source | Modality | Size | Task Type |
|----------|-------------|---------|-----------|------|-----------|
| **VCR** | Visual commonsense reasoning over images and text. | [🌐 Website](https://visualcommonsense.com/) • [🤗 HF](https://huggingface.co/datasets/visualcommonsense/VCR) | Image + Text | 290k | QA + Rationale |
| **OK-VQA** | QA requiring commonsense knowledge beyond the image. | [🌐 Website](https://okvqa.allenai.org/) • [🤗 HF](https://huggingface.co/datasets/okvqa) | Image + Text | 14k | Open QA |
| **A-OKVQA** | Extended OK-VQA with multiple-choice and rationale explanations. | [🌐 Website](https://allenai.org/project/a-okvqa) • [🤗 HF](https://huggingface.co/datasets/a-okvqa) | Image + Text | 25k | QA + Rationale |

</details>

---

<details>
<summary><h2>📊 Chart, Diagram & Figure Reasoning</h2></summary>

| Dataset | Description | Source | Modality | Size | Task Type |
|----------|-------------|---------|-----------|------|-----------|
| **ChartQA** | Reasoning over charts with natural language questions. | [GitHub](https://github.com/vis-nlp/ChartQA) • [🤗 HF](https://huggingface.co/datasets/vis-nlp/ChartQA) | Chart + Text | 20k | Chart QA |
| **FigureQA** | Synthetic figure reasoning via attribute comparison. | [🌐 Website](https://datasets.maluuba.com/FigureQA) | Chart | 100k | Figure reasoning |
| **PlotQA** | Real-world plot-based QA emphasizing data reasoning. | [GitHub](https://github.com/NiteshMethani/PlotQA) | Chart + Text | 28k | Data reasoning QA |
| **DVQA** | Bar chart reasoning with compositional questions. | [🌐 Website](https://www.cs.cmu.edu/~dvqa/) | Chart + Text | 3M | Chart QA |

</details>

---

<details>
<summary><h2>🌆 Scene & Object Understanding</h2></summary>

| Dataset | Description | Source | Modality | Size | Task Type |
|----------|-------------|---------|-----------|------|-----------|
| **Visual7W** | Visual QA emphasizing grounding and reasoning. | [🌐 Website](https://ai.stanford.edu/~yukez/visual7w/) | Image + Text | 327k | QA |
| **VQA v2** | Large-scale benchmark with diverse reasoning types. | [🌐 Website](https://visualqa.org/) • [🤗 HF](https://huggingface.co/datasets/vqa) | Image + Text | 1.1M | QA |
| **VizWiz** | Real-world dataset from blind users' photos. | [🌐 Website](https://vizwiz.org/) • [🤗 HF](https://huggingface.co/datasets/vizwiz) | Image + Text | 31k | QA |

</details>

---

<details>
<summary><h2>💬 Multimodal Logical Reasoning</h2></summary>

| Dataset | Description | Source | Modality | Size | Task Type |
|----------|-------------|---------|-----------|------|-----------|
| **VisDial** | Dialogue-based visual reasoning. | [🌐 Website](https://visualdialog.org/) • [🤗 HF](https://huggingface.co/datasets/visdial) | Image + Dialogue | 120k | Dialog reasoning |
| **IconQA** | IQ-test style reasoning with diagrams and analogies. | [🌐 Website](https://iconqa.github.io/) | Diagram + Text | 40k | Analogy QA |
| **RAVEN** | Abstract reasoning inspired by Raven’s Progressive Matrices. | [GitHub](https://github.com/WellyZhang/RAVEN) | Diagram | 70k | Abstract reasoning |
| **I-RAVEN** | Improved RAVEN dataset with diverse pattern distributions. | [GitHub](https://github.com/zhangjiqingyun/I-RAVEN) | Diagram | 100k | Logical reasoning |

</details>

---

<details>
<summary><h2>🧱 Synthetic & Programmatic Datasets</h2></summary>

| Dataset | Description | Source | Modality | Size | Task Type |
|----------|-------------|---------|-----------|------|-----------|
| **CLEVRER** | Video-based causal reasoning extension of CLEVR. | [🌐 Website](https://clevrer.csail.mit.edu/) | Video + Text | 20k | Causal reasoning |
| **IntPhys** | Tests intuitive physics understanding. | [🌐 Website](https://intphys.com/) | Video | 10k | Physical reasoning |
| **PhysicalIQ** | Visual reasoning about physical interactions and stability. | [🌐 Website](https://physicaliq.github.io/) | Image + Video | 12k | Physics QA |

</details>

---

<details>
<summary><h2>🔗 Hybrid Datasets</h2></summary>

| Dataset | Description | Source | Modality | Size | Task Type |
|----------|-------------|---------|-----------|------|-----------|
| **MMR1** | Multimodal long-CoT reasoning dataset for SFT + RL pipelines. | [🤗 HF](https://huggingface.co/datasets/MMR1) | Image + Text | Millions | Long CoT QA |
| **Vision-G1** | Multi-domain RL-ready reasoning dataset curated from 46 sources (math, spatial, GUI, commonsense, etc.). | [🤗 HF](https://huggingface.co/datasets/vision-g1) • [arXiv](https://arxiv.org/abs/2410.11890) | Image + Text | – | Multimodal QA, RL training |

</details>

---

## 📚 References

- *Visual Reasoning Datasets and Benchmarks* — AI2, Stanford, Meta AI, DeepMind, Tsinghua University.  
- **Surveys**
  - [A Survey on Visual Reasoning (2023)](https://arxiv.org/abs/2306.04862)  
  - [Multimodal Reasoning in VLMs (2024)](https://arxiv.org/abs/2402.08000)

---

## 🤝 Contributing

Contributions are warmly welcome! 💛  
Please open an **issue** or **pull request** to:
- Add new visual reasoning datasets  
- Update dataset metadata or Hugging Face links  
- Suggest improved classification or structure  

---

## 🪶 Citation

```bibtex
@misc{awesome_visual_reasoning,
  title={Awesome Visual Reasoning Datasets},
  author={Yun Zhu},
  year={2025},
  url={https://github.com/awesome-ai/awesome-visual-reasoning}
}
