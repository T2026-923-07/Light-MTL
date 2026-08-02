# Light-MTL

## Exploring Multi-Task Learning with Fine-Tuned Small Language Models via LoRA for Natural Language Understanding Tasks

This repository contains the official implementation, experimental notebooks, datasets, and experimental results accompanying the paper:

> **Exploring Multi-Task Learning with Fine-Tuned Small Language Models via LoRA for Natural Language Understanding Tasks**

---

## Project Information

This research is conducted within the framework of science and technology projects at institutional level of **Quy Nhon University**, Vietnam under the project code **T2026.923.07**.

---

## Abstract

Natural Language Understanding (NLU) tasks have achieved remarkable performance with pre-trained language models. However, full fine-tuning often requires substantial computational resources and memory. This work investigates an efficient Multi-Task Learning (MTL) framework based on Small Language Models (SLMs) combined with Low-Rank Adaptation (LoRA). The proposed approach significantly reduces the number of trainable parameters while maintaining competitive performance on multiple benchmark datasets.

---

## Repository Contents

This repository currently includes:

- Jupyter notebooks for model training and evaluation
- Experimental result files (.csv)
- Source code for baseline and proposed methods
- Figures used in the paper
- README and supplementary materials

---

## Benchmark Tasks

The experiments are conducted on the following Natural Language Understanding tasks:

- SST-2 (Sentiment Classification)
- QQP (Quora Question Pairs)
- STS-B (Semantic Textual Similarity)

The repository also contains comparison results for:

- SVM
- BiLSTM
- MiniLM
- DistilBERT
- ALBERT
- Single-task Learning (STL)
- Multi-task Learning (MTL)
- LoRA-based Parameter-Efficient Fine-Tuning (Light-MTL)

---

## Repository

The repository contains experimental notebooks and result files used in the paper.

Typical files include:

- `.ipynb` notebooks
- `.csv` experimental results
- Figures
- README

---

## Requirements

Python 3.10+

Main libraries include:

- PyTorch
- Transformers
- Hugging Face
- PEFT (LoRA)
- Datasets
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Experimental Results

The repository provides:

- Training notebooks
- Evaluation notebooks
- Experimental CSV files
- Figures used in the manuscript

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

This work was supported by the institutional science and technology project at **Quy Nhon University**, Vietnam under the project code **T2026.923.07**.

---

## Contact

**Nguyen Phuong Thao**

Quy Nhon University

Email: *your-email@domain.com*

---

## License

This project is released under the MIT License.
