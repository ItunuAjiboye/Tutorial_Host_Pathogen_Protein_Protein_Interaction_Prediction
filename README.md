# Tutorial:Host_Pathogen_Protein_Protein_Interaction_Prediction
A step-by-step, easy-to-follow tutorial for machine-learning–based host–pathogen protein–protein interaction prediction.

## Overview

This repository contains a step-by-step tutorial for predicting host–pathogen protein–protein interactions (HP-PPI) using machine learning. The tutorial is implemented as a series of Google Colab notebooks that collectively demonstrate an end-to-end workflow—from dataset preparation to model deployment.

The pipeline is designed primarily for human–bacterial PPI prediction, but it is generalizable and can be adapted to other host–pathogen systems, provided experimentally verified interaction data and protein sequences are available.


## Repository Structure

The tutorial is organized into four main notebooks, each representing a key stage in the workflow:

## Dataset Preparation

- Retrieval of positive interaction data from curated databases

- Generation of negative interaction pairs

- Mapping of host and pathogen protein IDs

## Data Preprocessing

- Sequence validation and cleaning

- Removal of non-standard amino acids and Filtering sequences based on length constraints

- Preparation of clean datasets for feature extraction

## Feature Extraction

- Conversion of protein sequences into numerical representations

- Implementation of multiple sequence-based descriptors

- Feature concatenation for host–pathogen protein pairs

## Machine Learning Application

- Data splitting and normalization

- Training and evaluation of multiple classifiers

- Cross-validation and performance comparison

- Model selection, retraining on the full dataset, and model saving

## Getting Started

1. Open the notebooks in Google Colab

2. Follow the notebooks sequentially

3. Mount Google Drive where required for data access and model saving

4. Install required Python packages as indicated in the notebooks

## Notes on Scalability

* Feature descriptors with large dimensionality require more computation time and memory.

* The bacterial dataset used in this tutorial is relatively small, allowing the workflow to be completed efficiently.

* For larger datasets (e.g., host–virus interactions), training and cross-validation may take significantly longer.

 ## Citation

If you use this tutorial or adapt the pipeline for your research, please cite the corresponding publication.
