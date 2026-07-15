<div align="center">

# 📊 CSS-300 — Source Data
### Raw data behind every figure in the manuscript

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=F72585&center=true&vCenter=true&multiline=true&width=800&height=80&lines=Every+Number+Behind+Every+Figure%3BFully+Reproducible+%F0%9F%94%81" alt="Typing SVG" />

<br/>

![Source Data](https://img.shields.io/badge/Contents-Source%20Data-3A0CA3?style=for-the-badge)
![Format](https://img.shields.io/badge/Format-CSV-00C9A7?style=for-the-badge)
![Reproducible](https://img.shields.io/badge/Reproducibility-✅%20Full-brightgreen?style=for-the-badge)

</div>

---

## ✨ Overview

This folder contains the **raw source data** used to generate the figures reported in the CSS-300 manuscript — covering per-model results, per-domain breakdowns, and per-pillar sycophancy decomposition.

> 📖 For metric definitions and computation details, see Section 3 (Methodology) of the manuscript.

---

## 🗂️ Folder Structure

```text
source_data/
├── 📊 phase1_pass_rates.csv
├── 📊 figure3_css_ranking.csv
├── 📊 figure4_radar_chart.csv
├── 📊 figure5_asr_mas.csv
├── 📊 figure6_phase4_temporal.csv
├── 📊 figure7_authority_sensitivity.csv
├── 📊 figure8_sag.csv
├── 📊 figure9_css_pillars.csv
└── 📄 README.md
```

---

## 📈 What's Inside

<div align="center">

| 📁 File | 🧾 Description |
|:--|:--|
| 📊 `phase1_pass_rates.csv` | Neutral-condition (Phase 1) qualification pass rates per model/domain |
| 📊 `figure3_css_ranking.csv` | Unified CSS Score, ranked across all eleven models |
| 📊 `figure4_radar_chart.csv` | Normalised multi-dimensional sycophancy profiles (SAG, ASR, MAS, CSS) |
| 📊 `figure5_asr_mas.csv` | Authority Sensitivity Rate (ASR) and Memory Anchoring Score (MAS) by tier |
| 📊 `figure6_phase4_temporal.csv` | Phase 4 temporal sycophancy breakdown for small/local models |
| 📊 `figure7_authority_sensitivity.csv` | Sycophancy rate at each authority credential level |
| 📊 `figure8_sag.csv` | Source Attribution Gap (SAG) across models |
| 📊 `figure9_css_pillars.csv` | Stacked decomposition of the Unified CSS Score by pillar |

</div>

---

## 🔁 Reproducibility

Every file in `source_data/` maps **1:1** to a figure in the manuscript, so anyone can:

- ✅ Regenerate every figure from raw numbers
- ✅ Verify reported statistics independently
- ✅ Re-analyze results under alternative aggregation choices

---

## 📐 Usage Notes

<div align="center">

| ✅ Guideline | Description |
|:---|:--|
| 🏷️ Naming | `figureN_description.csv` convention, matching the `figures/` folder |
| 🔗 Referencing | Match filenames to the figure numbers used in the manuscript |
| 🧩 Format | CSV for all tabular data |
| 🔄 Units | Percentages reported as raw numeric values (e.g. `9.6`, not `9.6%`) |

</div>

---

## 📚 Citation

If you reuse this data, please cite the CSS-300 manuscript:

```bibtex
@article{css300,
  title={CSS-300: A Multi-Dimensional Benchmark for Decomposing Source-Preference Sycophancy in Retrieval-Augmented Generation},
  author={Authors},
  year={2026}
}
```

---

<div align="center">

⬅️ [Back to main repository](../README.md)

</div>
