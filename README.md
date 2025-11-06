

# 🧠 Awesome Visual Reasoning Datasets

*A curated collection of datasets for visual reasoning research across multiple domains, including mathematics, science, spatial understanding, and commonsense reasoning.*

> 💡 Visual reasoning refers to the ability of AI systems to infer, interpret, and reason about visual information beyond simple perception. This repository organizes key datasets for training, evaluating, and benchmarking visual reasoning models.

---

## 📚 Table of Contents

* [Mathematical Reasoning](#mathematical-reasoning)
* [Scientific Reasoning](#scientific-reasoning)
* [Spatial & Geometric Reasoning](#spatial--geometric-reasoning)
* [Commonsense Reasoning](#commonsense-reasoning)
* [Chart, Diagram & Figure Reasoning](#chart-diagram--figure-reasoning)
* [Scene & Object Understanding](#scene--object-understanding)
* [Multimodal Logical Reasoning](#multimodal-logical-reasoning)
* [Synthetic & Programmatic Datasets](#synthetic--programmatic-datasets)
* [References](#references)

---

## 🧮 Mathematical Reasoning

| Dataset       | Description                                                                                         | Source                                           | Modality       | Size          | Task Type          | Benchmark Usage       |
| ------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------ | -------------- | ------------- | ------------------ | --------------------- |
| **MathVista** | Integrates visual and textual math reasoning tasks including geometry, algebra, and visual puzzles. | [MathVista (2024)](https://mathvista.github.io/) | Image + Text   | 6.5k QA pairs | Multimodal QA      | VL benchmark          |
| **GeoQA**     | Focuses on geometry problem-solving with diagram understanding.                                     | [GeoQA (2021)](https://github.com/TAL-AI/GeoQA)  | Diagram + Text | 5.8k          | Diagram-based QA   | Math reasoning        |
| **MathVerse** | Evaluates reasoning with complex visual-textual math scenes.                                        | [MathVerse (2024)](https://mathverse.github.io/) | Image + Text   | 12k           | QA + CoT reasoning | Visual math benchmark |
| **We-Math**   | Large-scale dataset for step-by-step multimodal math reasoning.                                     | [We-Math (2024)](https://we-math.github.io/)     | Image + Text   | 50k           | Reasoning QA       | Long CoT evaluation   |

---

## 🔬 Scientific Reasoning

| Dataset               | Description                                                                            | Source                                                                 | Modality       | Size | Task Type        | Benchmark Usage     |
| --------------------- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | -------------- | ---- | ---------------- | ------------------- |
| **ScienceQA**         | Multimodal QA dataset covering science topics with images, diagrams, and explanations. | [ScienceQA (2023)](https://scienceqa.github.io/)                       | Image + Text   | 21k  | QA + Explanation | Major VLM benchmark |
| **AI2D**              | Diagram-based dataset for scientific diagram understanding and question answering.     | [AI2D (2016)](https://allenai.org/data/ai2d)                           | Diagram + Text | 5k   | Diagram QA       | Science reasoning   |
| **ScienceDiagramsQA** | High-level science diagram QA dataset emphasizing reasoning over visual cues.          | [ScienceDiagramsQA (2024)](https://github.com/SciQA/ScienceDiagramsQA) | Diagram + Text | 7k   | QA               | Diagram reasoning   |
| **TQA (TextbookQA)**  | QA dataset derived from science textbooks combining text and diagrams.                 | [TQA (2017)](https://tqa.cs.washington.edu/)                           | Diagram + Text | 26k  | Text+Diagram QA  | Science reasoning   |

---

## 📐 Spatial & Geometric Reasoning

| Dataset        | Description                                                                          | Source                                                              | Modality | Size     | Task Type                    | Benchmark Usage         |
| -------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------- | -------- | -------- | ---------------------------- | ----------------------- |
| **CLEVR**      | Synthetic dataset testing compositional visual reasoning (spatial, attribute-based). | [CLEVR (2017)](https://cs.stanford.edu/people/jcjohns/clevr/)       | Image    | 100k     | Visual QA                    | Foundational reasoning  |
| **GQA**        | Tests compositional reasoning in real-world scenes.                                  | [GQA (2019)](https://cs.stanford.edu/people/dorarad/gqa/index.html) | Image    | 22M      | Scene QA                     | Reasoning benchmark     |
| **ShapeWorld** | Synthetic shapes-based dataset for testing abstract spatial reasoning.               | [ShapeWorld (2017)](https://github.com/AlexKuhnle/ShapeWorld)       | Image    | Variable | Description QA               | Compositional reasoning |
| **CoGenT**     | CLEVR variant focusing on generalization to novel visual concepts.                   | [CoGenT (2018)](https://cs.stanford.edu/people/jcjohns/clevr/)      | Image    | 100k     | Compositional generalization | CLEVR extension         |

---

## 🧩 Commonsense Reasoning

| Dataset     | Description                                                                  | Source                                                | Modality     | Size          | Task Type      | Benchmark Usage       |
| ----------- | ---------------------------------------------------------------------------- | ----------------------------------------------------- | ------------ | ------------- | -------------- | --------------------- |
| **VCR**     | Visual Commonsense Reasoning dataset for understanding implicit visual cues. | [VCR (2019)](https://visualcommonsense.com/)          | Image + Text | 290k QA pairs | QA + Rationale | Commonsense benchmark |
| **OK-VQA**  | Open-ended QA requiring commonsense knowledge beyond the image.              | [OK-VQA (2019)](https://okvqa.allenai.org/)           | Image + Text | 14k           | Open-ended QA  | Commonsense           |
| **A-OKVQA** | Extends OK-VQA with multiple-choice and rationale explanations.              | [A-OKVQA (2022)](https://allenai.org/project/a-okvqa) | Image + Text | 25k           | QA + Rationale | Reasoning evaluation  |

---

## 📊 Chart, Diagram & Figure Reasoning

| Dataset      | Description                                                             | Source                                                   | Modality     | Size | Task Type         | Benchmark Usage           |
| ------------ | ----------------------------------------------------------------------- | -------------------------------------------------------- | ------------ | ---- | ----------------- | ------------------------- |
| **ChartQA**  | Reasoning over charts with natural language questions.                  | [ChartQA (2022)](https://github.com/vis-nlp/ChartQA)     | Chart + Text | 20k  | Chart QA          | Chart understanding       |
| **FigureQA** | Synthetic figure reasoning dataset testing visual attribute comparison. | [FigureQA (2018)](https://datasets.maluuba.com/FigureQA) | Chart        | 100k | Figure reasoning  | Synthetic reasoning       |
| **PlotQA**   | Real-world plot-based QA dataset emphasizing data reasoning.            | [PlotQA (2020)](https://github.com/NiteshMethani/PlotQA) | Chart + Text | 28k  | Data reasoning QA | Chart reasoning benchmark |
| **DVQA**     | Bar chart reasoning with compositional questions.                       | [DVQA (2018)](https://www.cs.cmu.edu/~dvqa/)             | Chart + Text | 3M   | Chart QA          | Visual data reasoning     |

---

## 🌆 Scene & Object Understanding

| Dataset      | Description                                                                              | Source                                                      | Modality     | Size          | Task Type | Benchmark Usage         |
| ------------ | ---------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ------------ | ------------- | --------- | ----------------------- |
| **Visual7W** | Visual QA dataset emphasizing grounding and reasoning over natural images.               | [Visual7W (2016)](https://ai.stanford.edu/~yukez/visual7w/) | Image + Text | 327k QA pairs | QA        | Reasoning QA            |
| **VQA v2**   | Large-scale visual question answering benchmark with diverse reasoning types.            | [VQA v2 (2017)](https://visualqa.org/)                      | Image + Text | 1.1M          | QA        | Standard VQA benchmark  |
| **VizWiz**   | Visual QA dataset using images taken by blind people — challenging real-world reasoning. | [VizWiz (2018)](https://vizwiz.org/)                        | Image + Text | 31k           | QA        | Accessibility benchmark |

---

## 🧩 Multimodal Logical Reasoning

| Dataset     | Description                                                          | Source                                                      | Modality         | Size | Task Type          | Benchmark Usage        |
| ----------- | -------------------------------------------------------------------- | ----------------------------------------------------------- | ---------------- | ---- | ------------------ | ---------------------- |
| **VisDial** | Dialogue-based visual reasoning dataset.                             | [VisDial (2017)](https://visualdialog.org/)                 | Image + Dialogue | 120k | Dialog reasoning   | Multimodal             |
| **IconQA**  | Visual IQ-test style reasoning dataset with diagrams and analogies.  | [IconQA (2022)](https://iconqa.github.io/)                  | Diagram + Text   | 40k  | Analogy QA         | Logical reasoning      |
| **RAVEN**   | Abstract reasoning dataset inspired by Raven’s Progressive Matrices. | [RAVEN (2019)](https://github.com/WellyZhang/RAVEN)         | Diagram          | 70k  | Abstract reasoning | Visual logic benchmark |
| **I-RAVEN** | Improved RAVEN dataset with diverse pattern distributions.           | [I-RAVEN (2020)](https://github.com/zhangjiqingyun/I-RAVEN) | Diagram          | 100k | Logical reasoning  | Pattern reasoning      |

---

## 🧱 Synthetic & Programmatic Datasets

| Dataset        | Description                                                         | Source                                             | Modality      | Size | Task Type          | Benchmark Usage    |
| -------------- | ------------------------------------------------------------------- | -------------------------------------------------- | ------------- | ---- | ------------------ | ------------------ |
| **CLEVRER**    | Video-based causal reasoning extension of CLEVR.                    | [CLEVRER (2020)](https://clevrer.csail.mit.edu/)   | Video + Text  | 20k  | Causal reasoning   | Temporal reasoning |
| **IntPhys**    | Physical reasoning dataset testing intuitive physics understanding. | [IntPhys (2019)](https://intphys.com/)             | Video         | 10k  | Physical reasoning | Causal reasoning   |
| **PhysicalIQ** | Visual reasoning about physical interactions and stability.         | [PhysicalIQ (2024)](https://physicaliq.github.io/) | Image + Video | 12k  | Physics QA         | Physical reasoning |

---

## 📚 References

* “Visual Reasoning Datasets and Benchmarks,” *AI2 Research, Stanford, Meta AI, DeepMind, Tsinghua University.*
* Comprehensive surveys:

  * [A Survey on Visual Reasoning (2023)](https://arxiv.org/abs/2306.04862)
  * [Multimodal Reasoning in VLMs (2024)](https://arxiv.org/abs/2402.08000)

---

## 🧩 Contributing

Contributions are welcome!
Please open an issue or pull request to:

* Add new visual reasoning datasets
* Update dataset metadata or links
* Suggest new domain classifications

---

## 🪶 Citation

If you use this list, please cite:

```bibtex
@misc{awesome_visual_reasoning,
  title={Awesome Visual Reasoning Datasets},
  author={Yun Zhu},
  year={2025},
  url={https://github.com/awesome-ai/awesome-visual-reasoning}
}
```

