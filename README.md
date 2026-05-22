# Jet-quenching-identification-via-supervised-learning-in-simulated-heavy-ion-collisions

This repository contains the codes developed and used in the study:

**Jet Quenching Identification via Supervised Learning in Simulated Heavy-Ion Collisions**  
Leonardo Lima da Silva and Marcelo Gameiro Munhoz  
arXiv:2604.21088 [hep-ph]

## Overview

Jet quenching is one of the signatures of the formation of the quark-gluon plasma (QGP) in relativistic heavy-ion collisions. In this work, five supervised machine learning methods are used to investigate whether jets modified by the medium can be distinguished from jets produced in vacuum-like conditions using jet substructure observables.

The analysis is based on simulated data generated with the code Jet Evolution With Energy Loss (JEWEL) and processed through jet reconstruction via FastJet. The main goal is to evaluate the capability of machine learning models to identify jet quenching patterns from physically motivated observables.

## Repository Description

The code available in this repository was used in the development of the analysis presented in the paper. It includes scripts for data preprocessing, feature extraction, model training, prediction and evaluation.

The repository is intended to support transparency and reproducibility of the results discussed in the manuscript.


## Main Features

- Simulation pipeline of heavy-ion collisions with JEWEL and JEWEL+v-USPhydro;

- Preprocessing of simulated jet datasets;

- Organization of jet substructure observables in non-sequential and sequential data;

- Training of supervised machine learning models;

- Evaluation of classification performance;

- Support scripts for comparing different physical scenarios.


## Repository structure
```text

.

├── preprocessing/        # Scripts for cleaning and preparing the datasets

├── models/               # Machine learning model definitions and training scripts

├── sim/                  # Pipeline of the simulation and computation of jet observables used in this work

├── requirements.txt      # Python dependencies

└── README.md             # Repository documentation


```

## Data Availability

The full simulated datasets are not included in this repository due to storage limitations, but they can be generated using the simulation and analysis pipeline described in this manuscript, or made available upon reasonable request to the authors. 


## Citation

If you use or find this repository useful for your research, please cite
```text
@misc{dasilva2026jetquenchingidentificationsupervised,
      title={Jet Quenching Identification via Supervised Learning in Simulated Heavy-Ion Collisions}, 
      author={Leonardo Lima da Silva and Marcelo Gameiro Munhoz},
      year={2026},
      eprint={2604.21088},
      archivePrefix={arXiv},
      primaryClass={hep-ph},
      url={https://arxiv.org/abs/2604.21088}, 
}
```


## Contact

For questions, suggestions, or collaboration, please contact:
leonardols.lsilva@usp.br
