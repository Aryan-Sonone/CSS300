# CSS-300 Benchmark Dataset

> **Official repository for the CSS-300 benchmark accompanying the research paper:**
>
> ***CSS-300: A Multi-Dimensional Benchmark for Decomposing Source-Preference Sycophancy in Retrieval-Augmented Generation***

## Overview

CSS-300 is a benchmark dataset designed to evaluate **source-preference sycophancy** in **Retrieval-Augmented Generation (RAG)** systems. It enables systematic analysis of whether language models exhibit undue preference toward retrieved sources instead of independently evaluating evidence.

The benchmark supports research on model alignment, factual reliability, retrieval robustness, and trustworthy AI by providing a curated collection of evaluation instances together with the data required to reproduce the analyses presented in the accompanying manuscript.

---

## Repository Structure

```text
CSS-300/
├── dataset.json          # Complete CSS-300 benchmark dataset
├── figures/              # Figures included in the manuscript
├── source_data/          # Source data used to generate figures and tables
└── README.md
```

### Contents

| File/Directory | Description                                                                 |
| -------------- | --------------------------------------------------------------------------- |
| `dataset.json` | Complete CSS-300 benchmark dataset.                                         |
| `figures/`     | Figures appearing in the manuscript.                                        |
| `source_data/` | Source data used to reproduce the figures and tables reported in the paper. |

---

## Dataset

The benchmark consists of **300 carefully curated evaluation instances** designed to measure source-preference sycophancy across multiple dimensions.

The dataset is intended for:

* Benchmarking Retrieval-Augmented Generation systems
* Evaluating model robustness against biased retrieved evidence
* Measuring source-preference behaviors
* Alignment and interpretability research
* Comparative evaluation across language models and retrieval pipelines

Refer to the accompanying manuscript for a detailed description of the benchmark construction, evaluation protocol, taxonomy, and experimental methodology.

---

## Reproducibility

To support transparent and reproducible research, this repository includes:

* The complete benchmark dataset
* Figures used in the paper
* Source data used to generate all reported figures and tables

These resources allow researchers to reproduce the analyses and build upon the benchmark in future work.

---

## Data Generation and Validation

The benchmark was generated using an **AI-assisted data generation pipeline** followed by **independent human annotation and validation** performed by members of the research team.

Quality assurance included multiple stages of review to ensure consistency and correctness of the benchmark.

---

## Ethics and Privacy

This repository **does not contain**:

* Personal data
* Sensitive information
* Personally identifiable information (PII)
* Human subject data

The benchmark is intended exclusively for scientific research on Retrieval-Augmented Generation systems and model evaluation.

---

## Citation

If you use CSS-300 in your research, please cite the accompanying paper:

```bibtex
@article{css300,
  title={CSS-300: A Multi-Dimensional Benchmark for Decomposing Source-Preference Sycophancy in Retrieval-Augmented Generation},
  author={Authors},
  year={2026}
}
```

Please update the citation with the final publication details once available.

---

## License

Please refer to the repository's `LICENSE` file for licensing information.

---

## Contributors

The CSS-300 benchmark was developed through the contributions of the research team.

- **[@Aryan-Sonone](https://github.com/Aryan-Sonone)** — Contributor
- **[@Nikhil10062006](https://github.com/Nikhil10062006)** — Contributor
  
## Contact

For questions, issues, or collaboration opportunities, please open an issue in this repository or contact the corresponding authors listed in the accompanying manuscript.
