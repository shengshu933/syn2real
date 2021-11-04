# Integrating Expert Knowledge with Domain Adaptation for Unsupervised Fault Diagnosis
To appear in IEEE Transactions on Instrumentation and Measurement. [PDF](https://arxiv.org/abs/2107.01849)


## Introduction
In this repository, we provide the synthetic CWRU data set. We generate the synthetic faults by injecting experts' understanding on fault patterns to the healthy signals.

### Data Download
[dataset](https://github.com/qinenergy/syn2real/releases)

### Structure
```
├── data
│   ├── cwru.parquet            # CWRU dataset in parquet format, provided in the download link
│   ├── cwru_synthetic.parquet  # Synthetic CWRU dataset we generated, provided in the download link
│   ├── preprocessed            # Preprocessed data we used for our experiments
│   │   ├── XreallDEenv.npy
│   │   ├── XsynallDEenv.npy
│   │   ├── yreallDEenv.npy
│   │   └── ysynallDEenv.npy
│   └── preprocess.py           # Preprocessing code
├── code
│   └── Syn2real_CWRU.ipynb     # Notebook to reproduce our CWRU synthetic to real adaptation results. Identical to the Google Colab we provide.
└── README.md
```

Example code to read and preprocess the parquet files are provided in data/preprocess.py 


## Synthetic Data for CWRU bearings
We generate a synthetic bearing dataset for the syn2real experiments. The Synthetic CWRU dataset is free to use for research purpose. 

## Code
We provide a google colab research notebook for readers to better under our method. You can play with it [here](https://colab.research.google.com/drive/1o-8ETOG-ej3HxVl4lvNJN8D0G6734bu7?usp=sharing).

