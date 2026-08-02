# Light-MTL

## Exploring Multi-Task Learning with Fine-Tuned Small Language Models via LoRA for Natural Language Understanding Tasks

This repository contains the official implementation, experimental results, and supplementary materials for the paper:

> **Exploring Multi-Task Learning with Fine-Tuned Small Language Models via LoRA for Natural Language Understanding Tasks**

---

## Project Information

This research is conducted within the framework of science and technology projects at institutional level of **Quy Nhon University**, Vietnam under the project code **T2026.923.07**.

---

## Abstract

Natural Language Understanding (NLU) tasks are commonly addressed using large pre-trained language models. However, full fine-tuning requires substantial computational resources and storage. This project investigates an efficient Multi-Task Learning (MTL) framework based on Small Language Models (SLMs) combined with Low-Rank Adaptation (LoRA). The proposed approach enables parameter-efficient adaptation while preserving competitive performance across multiple NLU benchmark tasks.

---

## Repository Structure

```text
Light-MTL/
│
├── notebooks/              # Jupyter notebooks
├── results/                # Experimental results
├── figures/                # Figures used in the paper
├── data/                   # Dataset (if publicly distributable)
├── models/                 # Saved checkpoints
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Experimental Tasks

The proposed framework is evaluated on several Natural Language Understanding benchmarks including:

- SST-2 (Sentiment Classification)
- QQP (Question Pair Classification)
- STS-B (Semantic Textual Similarity)

Baseline methods include:

- SVM
- BiLSTM
- STL-MiniLM
- STL-DistilBERT
- STL-ALBERT
- Full Multi-Task Fine-Tuning
- Proposed Light-MTL (LoRA)

---

## Installation

Clone the repository

```bash
git clone https://github.com/T2026-923-07/Light-MTL.git
cd Light-MTL
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

Run the experiments using the corresponding notebooks or Python scripts.

Example:

```bash
python train.py
```

or

```bash
jupyter notebook
```

---

## Experimental Results

The repository contains:

- Experimental notebooks
- Evaluation results
- CSV result files
- Figures used in the paper

---

## Citation

If you find this repository useful, please cite:

```bibtex
@article{nguyen2026lightmtl,
  title={Exploring Multi-Task Learning with Fine-Tuned Small Language Models via LoRA for Natural Language Understanding Tasks},
  author={Nguyen, Phuong Thao and Le, Quang-Hung},
  year={2026}
}
```

---

## Acknowledgement

This work was supported by the institutional science and technology project at Quy Nhon University under project code **T2026.923.07**.

---

## License

This project is released under the MIT License.
