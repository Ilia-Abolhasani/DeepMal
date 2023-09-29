# DeepMal: Accurate Prediction of Protein Malonylation Sites

This repository contains a Python implementation of the DeepMal model, which accurately predicts protein malonylation sites using deep neural networks. The model is based on the research paper titled "DeepMal: Accurate Prediction of Protein Malonylation Sites by Deep Neural Networks."

**Note:** This repository is a fork of the original DeepMal repository available at [QUST-AIBBDRC/DeepMal](https://github.com/QUST-AIBBDRC/DeepMal/). In this forked repository, we have added a Jupyter notebook (`Code.ipynb`) that covers the entire process, including data processing, model training, and result evaluation.

## Introduction

Lysine malonylation is an important post-translational modification (PTM) of proteins. Malonylated proteins play a crucial role in various cellular functions, including metabolic pathways, mitochondrial functions, and fatty acid oxidation. Accurate identification of malonylation sites is essential for understanding the molecular mechanisms of malonylation. Experimental identification of these sites is challenging and costly. To address this, the DeepMal model has been developed.

## Key Features

- Feature extraction:
  - Enhanced Amino Acid Composition (EAAC)
  - Enhanced Grouped Amino Acid Composition (EGAAC)
  - Dipeptide Deviation from Expected Mean (DDE)
  - K Nearest Neighbors (KNN)
  - BLOSUM62 Matrix

- Classification using deep neural networks:
  - Linear Convolutional Neural Network
  - Maximum Pooling
  - Multilayer Neural Network

## Performance

DeepMal has been evaluated on independent datasets including Escherichia coli (E. coli), Homo sapiens (H. sapiens), and Mus musculus (M. musculus). The model achieved impressive results:

- AUC values: 0.974 (E. coli), 0.956 (H. sapiens), 0.944 (M. musculus)
- Accuracy: 96.5% (E. coli), 95.5% (H. sapiens), 94.5% (M. musculus)

Compared to other prediction models, DeepMal demonstrates a significant increase in prediction accuracy, ranging from 9.5% to 18.5%.

## Usage

To use DeepMal, follow these steps:

1. Clone this repository: `git clone https://github.com/Ilia-Abolhasani/deep-mal.git`
2. Install the required dependencies listed in the [Pipeline](#pipeline) section.
3. Explore the provided Jupyter notebook `Code.ipynb`, which covers data processing, model training, and result evaluation.

## Credits

This repository is a fork of the original DeepMal repository, available at [QUST-AIBBDRC/DeepMal](https://github.com/QUST-AIBBDRC/DeepMal/). The source code and datasets used in this project are publicly available there.

## Dependencies

DeepMal uses the following dependencies:

- MATLAB2014a
- Python 3.6
- NumPy
- SciPy
- scikit-learn
- Keras

## Contributing

If you'd like to contribute to this project, please open an issue or submit a pull request.
