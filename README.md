# 🎓𝗗𝗦𝗣: Demonstrate–Search–Predict

A framework for composing retrieval models and language models into powerful pipelines that tackle knowledge-intensive tasks.

[Demonstrate-Search-Predict: Composing retrieval and language models for knowledge-intensive NLP](https://arxiv.org/pdf/2212.14024.pdf)

## Installation

```pip install dsp-ml```

## 🏃 Getting Started

Our [intro notebook](intro.ipynb) provides examples of five "multi-hop" question answering programs of increasing complexity written in DSP.

You can [open the intro notebook in Google Colab](https://colab.research.google.com/github/stanfordnlp/dsp/blob/main/intro.ipynb). You don't even need an API key to get started with it.

Once you go through the notebook, you'll be ready to create your own DSP pipelines!

## [NEW!] DSP Compiler

Our [compiler notebook](compiler.ipynb) introduces the new experimental compiler, which can optimize DSP programs automatically for (much) cheaper execution.

You can [open the compiler notebook in Google Colab](https://colab.research.google.com/github/stanfordnlp/dsp/blob/main/compiler.ipynb). You don't even need an API key to get started with it.

## [NEW!] Picking in-context examples using KNN/ANN methods

Our [knn demo notebook](tests/knn_demonstrations_test.ipynb) provides examples of adding the KNN stage, as described in the paper. This improvement in the Demonstrate stage of DSP allows you not to sample Examples randomly but instead search for better and similar options. You can get an idea from [this paper](https://arxiv.org/abs/2101.06804).

## ✍️ Reference

If you use DSP in a research paper, please cite our work as follows:

```
@article{khattab2022demonstrate,
  title={Demonstrate-Search-Predict: Composing Retrieval and Language Models for Knowledge-Intensive {NLP}},
  author={Khattab, Omar and Santhanam, Keshav and Li, Xiang Lisa and Hall, David and Liang, Percy and Potts, Christopher and Zaharia, Matei},
  journal={arXiv preprint arXiv:2212.14024},
  year={2022}
}
```
