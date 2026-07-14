<div align="center">

# 🎯🔥 CSS-300 🔥🎯
### 🌈 A Multi-Dimensional Benchmark for Decomposing Source-Preference Sycophancy in RAG 🌈

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=F72585&center=true&vCenter=true&multiline=true&width=800&height=100&lines=Measuring+Source-Preference+Sycophancy%3Bin+Retrieval-Augmented+Generation+%F0%9F%9A%80%3B300+Curated+Evaluation+Instances+%F0%9F%A7%A0" alt="Typing SVG" />

<br/>

![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)
![RAG](https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Generation-8A2BE2?style=for-the-badge)
![License](https://img.shields.io/badge/License-See%20LICENSE-00C9A7?style=for-the-badge)

![Stars](https://img.shields.io/github/stars/Nikhil10062006/CSS300?style=for-the-badge&color=FFD700&label=⭐%20Stars)
![Forks](https://img.shields.io/github/forks/Nikhil10062006/CSS300?style=for-the-badge&color=1E90FF&label=🍴%20Forks)
![Issues](https://img.shields.io/github/issues/Nikhil10062006/CSS300?style=for-the-badge&color=FF6B6B&label=🐛%20Issues)
![Last Commit](https://img.shields.io/github/last-commit/Nikhil10062006/CSS300?style=for-the-badge&color=32CD32&label=🕒%20Last%20Commit)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Welcome%20to%20CSS-300&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%"/>

</div>

---

## ✨ TL;DR — Why CSS-300?

> 🧠 Does your RAG system trust **evidence** — or does it just trust **whichever source it was handed**?
>
> **CSS-300** is a curated, 300-instance benchmark built to expose and measure **source-preference sycophancy**: the tendency of a model to defer to a retrieved source's authority instead of independently reasoning about the evidence in front of it.

<div align="center">

| 🎯 Purpose | 🧪 Instances | 🧬 Domain | 🛠️ Status |
|:---:|:---:|:---:|:---:|
| Measure sycophancy in RAG | **300** curated cases | Retrieval-Augmented Generation | ✅ Active |

</div>

---

## 🌟 Features at a Glance

<table>
<tr>
<td width="50%" valign="top">

### 🔍 What's Inside
- 📦 `dataset.json` — the full 300-instance benchmark
- 📊 `figures/` — every figure from the paper
- 📁 `source_data/` — raw data behind every figure & table
- 📜 Fully reproducible pipeline

</td>
<td width="50%" valign="top">

### 🎯 What It's For
- 🧪 Benchmarking RAG systems
- 🛡️ Testing robustness to biased evidence
- 🔬 Alignment & interpretability research
- ⚖️ Cross-model, cross-pipeline comparison

</td>
</tr>
</table>

---

## 🗂️ Repository Structure

```text
CSS-300/
├── 📦 dataset.json          # Complete CSS-300 benchmark dataset
├── 🖼️  figures/              # Figures included in the manuscript
├── 📊 source_data/          # Source data behind figures & tables
└── 📄 README.md             # You are here 👋
```

<div align="center">

| File / Directory | Description |
|:--|:--|
| 🧾 `dataset.json` | Complete CSS-300 benchmark dataset |
| 🖼️ `figures/` | Figures appearing in the manuscript |
| 📊 `source_data/` | Source data to reproduce figures & tables |

</div>

---

## 🚀 The Dataset

<div align="center">

```
 ██████╗███████╗███████╗     ██████╗  ██████╗  ██████╗ 
██╔════╝██╔════╝██╔════╝     ╚════██╗██╔═████╗██╔═████╗
██║     ███████╗███████╗█████╗█████╔╝██║██╔██║██║██╔██║
██║     ╚════██║╚════██║╚════╝╚═══██╗████╔╝██║████╔╝██║
╚██████╗███████║███████║     ██████╔╝╚██████╔╝╚██████╔╝
 ╚═════╝╚══════╝╚══════╝     ╚═════╝  ╚═════╝  ╚═════╝ 
```

**300 carefully curated evaluation instances** 🧬 measuring source-preference sycophancy across multiple dimensions.

</div>

The benchmark is built for:

- 🧪 **Benchmarking** Retrieval-Augmented Generation systems
- 🛡️ **Evaluating** model robustness against biased retrieved evidence
- 📐 **Measuring** source-preference behaviors
- 🧠 **Alignment & interpretability** research
- ⚖️ **Comparative evaluation** across language models and retrieval pipelines

> 📖 For construction methodology, taxonomy, and evaluation protocol, see the accompanying manuscript.

---

## 🔁 Reproducibility

<div align="center">

| ✅ Included | Description |
|:---:|:--|
| 🧾 | Complete benchmark dataset |
| 🖼️ | Figures used in the paper |
| 📊 | Source data behind every figure & table |

</div>

Everything you need to **reproduce every analysis** and build on top of the benchmark is right here.

---

## 🧪 Data Generation & Validation

```mermaid
graph LR
    A[🤖 AI-Assisted Generation] --> B[👥 Independent Human Annotation]
    B --> C[✅ Multi-Stage Validation]
    C --> D[🎯 CSS-300 Benchmark]
    style A fill:#F72585,color:#fff,stroke:#333
    style B fill:#7209B7,color:#fff,stroke:#333
    style C fill:#3A0CA3,color:#fff,stroke:#333
    style D fill:#00C9A7,color:#fff,stroke:#333
```

The benchmark was generated via an **AI-assisted pipeline**, then independently annotated and validated by the research team, with **multiple stages of quality-assurance review**.

---

## 🔒 Ethics & Privacy

<div align="center">

![No PII](https://img.shields.io/badge/PII-None-success?style=for-the-badge)
![No Personal Data](https://img.shields.io/badge/Personal%20Data-None-success?style=for-the-badge)
![Research Only](https://img.shields.io/badge/Usage-Research%20Only-blueviolet?style=for-the-badge)

</div>

This repository **does not contain**:

- ❌ Personal data
- ❌ Sensitive information
- ❌ Personally identifiable information (PII)
- ❌ Human subject data

Intended **exclusively** for scientific research on RAG systems and model evaluation. 🔬

---

## 📚 Citation

If CSS-300 powers your research, please cite:

```bibtex
@article{css300,
  title={CSS-300: A Multi-Dimensional Benchmark for Decomposing Source-Preference Sycophancy in Retrieval-Augmented Generation},
  author={Authors},
  year={2026}
}
```

> ✏️ Update with final publication details once available.

---

## 📄 License

Please refer to the repository's `LICENSE` file for licensing information.

---

## 👥 Contributors

<div align="center">

<a href="https://github.com/Aryan-Sonone"><img src="https://img.shields.io/badge/@Aryan--Sonone-Contributor-F72585?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://github.com/Nikhil10062006"><img src="https://img.shields.io/badge/@Nikhil10062006-Contributor-3A0CA3?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

---

## 📬 Contact

Questions, issues, or collaboration ideas? 🎉

- 🐛 Open an issue in this repository
- ✉️ Reach out to the corresponding authors listed in the manuscript

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

### ⭐ If CSS-300 helps your research, consider starring the repo! ⭐

</div>
