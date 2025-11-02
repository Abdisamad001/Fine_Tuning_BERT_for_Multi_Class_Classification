# Fine Tuning BERT for Multi-Class Classification

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Latest-red)
![Transformers](https://img.shields.io/badge/🤗%20Transformers-Latest-yellow)
![NLP](https://img.shields.io/badge/NLP-BERT-orange)

This repository demonstrates how to fine-tune the BERT (Bidirectional Encoder Representations from Transformers) model for multi-class classification tasks using Python and deep learning libraries. 

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)

## Overview

BERT has revolutionized Natural Language Processing by introducing deep bidirectional representations. This project covers:
- Loading pre-trained BERT models
- Preparing datasets for multi-class classification
- Implementing custom classification heads

## Installation

Clone this repository:
```bash
git clone https://github.com/Abdisamad001/Fine_Tuning_BERT_for_Multi_Class_Classification.git
cd Fine_Tuning_BERT_for_Multi_Class_Classification
```

Install the required dependencies:
```bash
pip install -r requirements.txt
```


## Dataset

The project supports CSV or TSV formatted datasets with the following columns:
- `text`: The input sentence or paragraph.
- `label`: The target class (integer or string).

You can use any multi-class labeled dataset suitable for your task.

---

**Author:** [Abdisamad001](https://github.com/Abdisamad001)
