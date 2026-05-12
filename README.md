# H3ACE Workshop Notebooks

This repository contains Jupyter notebooks for machine learning tasks on molecular property prediction.

## Session 1

### SS_Decision_Trees.ipynb
Predicts aqueous solubility (LogS) of organic compounds for drug discovery.
- **Dataset**: ESOL (1,128 compounds with SMILES and solubility values)
- **Model**: Decision Tree Regressor on RDKit descriptors
- **Task**: Regression
- **Predicted**: LogS (log solubility in mol/L)

### SS_MLP.ipynb
Classifies organic compounds as soluble or poorly soluble.
- **Dataset**: ESOL (SMILES and LogS values)
- **Model**: Multi-Layer Perceptron (PyTorch)
- **Task**: Binary Classification
- **Predicted**: Solubility Class (0/1)

## Session 2

### mpnn.ipynb
Predicts molecular properties using Message Passing Neural Networks.
- **Dataset**: ESOL
- **Model**: Simple Mpnn
- **Task**: Regression
- **Predicted**: LogS and LogP

### gcn.ipynb
Predicts molecular solubility and lipophilicity with Graph Convolutional Networks.
- **Dataset**: ESOL
- **Model**: GCN with convolution and pooling layers
- **Task**: Regression
- **Predicted**: LogS and LogP

### gat.ipynb
Predicts physicochemical properties using Graph Attention Networks.
- **Dataset**: ESOL 
- **Model**: GAT on molecular graphs
- **Task**: Regression (multi-target)
- **Predicted**: LogS and LogP

