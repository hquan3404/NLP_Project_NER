# NLP_Project_NER# NLP\_Project\_NER

**Project Title:** NLP Project for Named Entity Recognition (NER)

## Description

This repository contains a team-based implementation of various sequence modeling architectures for Named Entity Recognition (NER) tasks. The project includes implementations of GRU, BiGRU, LSTM, BiLSTM, CNN-based models, and hybrid architectures. Our aim is to compare model performance on standard NER datasets and provide clear examples of preprocessing, training, and evaluation workflows.

## Features

* Data preprocessing pipeline for raw text to tokenized, indexed inputs
* Multiple model architectures:

  * uniGRU (`uniGRU.py`)
  * biGRU (`biGRU.py`)
  * uniLSTM (`uniLSTM.py`)
  * biLSTM (`biLSTM.py`)
  * CNN + biGRU (`CNN_biGRU.py`)
  * CNN + biLSTM (`CNN_biLSTM.py`)
  * uniGRU and uniLSTM variants
* Jupyter notebook for interactive experiments (`main.ipynb`)
* Scripted training and evaluation (`prepro.py`, additional scripts)
* Model visualization utilities in the `visualize/` folder

## Repository Structure

```
NLP_Project_NER/
├── Input/              # Raw and processed datasets
├── Log/                # Training and evaluation logs
├── Model/              # Model definitions and trained weights
│   ├── __pycache__/
│   ├── biGRU.py
│   ├── uniGRU.py
│   ├── uniLSTM.py          
│   ├── biLSTM.py           
│   ├── CNN_biGRU.py
│   ├── CNN_biLSTM.py
│   └── CNN_biGRU.py
├── visualize/          # Plotting utilities
├── main.ipynb          # Interactive experiment notebook
├── prepro.py           # Preprocessing script
└── README.md           # This file
```

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/hquan3404/NLP_Project_NER.git
   cd NLP_Project_NER
   ```
   ```
## Contributions

* **\[Pham Quan]**: Designed and implemented the **uniLSTM** (`uniLSTM.py`) and **biLSTM** (`biLSTM.py`) architectures, including model definition, training loop, hyperparameter tuning, and evaluation metrics.
* Other team members contributed GRU variants, CNN hybrids, data processing, and visualization components.

## License

This project is licensed under the [MIT License](LICENSE).

---

> **Note:** This is a team project. For full access to the private repository and collaboration history, please request access or view the public fork and documentation provided [here.](https://github.com/ngocnhatAI/Named-Entity-Recognition).
