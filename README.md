# SC1015 Group 5 Mini-Project

Members: Peh Zi Heng, Lee Hsien Xiang, Lee Yong Arn

## Description
The emergence of digital marketplaces has greatly changed consumer behaviour where review rank as essential in
the considerations of buying a new product. Consequently, there is a new type of deception invented - fake user reviews, 
which are created to artificially boost the ratings of certain products. Such deceptive practices negatively affect the 
credibility of the platform and reduces user engagement and revenue. 

This project aims to provide detailed analysis insights and fake reviews detection capabilities
using neural networks namely Deep Neural Network, LSTM & BERT.


## Table of Contents
- [File Description](#file-description)
- [Prerequisite](#prerequisite)
- [Getting Started](#getting-started)

## Prerequisite
- [Miniforge](https://github.com/conda-forge/miniforge) (Recommended)
- Python Environment with TensorFlow


## File Description

| File Name                                      | Description                                                                                                                                                                                                                                          |
|------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| fake reviews dataset.csv                       | This CSV file contains the dataset used in the project. [Dataset](https://www.kaggle.com/datasets/mexwell/fake-reviews-dataset/data)                                                                                                                 |
| Analysis of data + Training DNN and LSTM.ipynb | Jupyter notebook that contains our analysis of the fake reviews dataset, including data preprocessing, exploratory data analysis, and the development of Deep Neural Network (DNN) and Long Short-Term Memory (LSTM) models for classifying reviews. |
| Training BERT.ipynb                            | Jupyter notebook focused on the implementation of a BERT (Bidirectional Encoder Representations from Transformers) model for the task of fake review classification. This notebook covers the setup, training, and evaluation of the BERT model.     |
| BERT Attention Visualisation.ipynb             | Jupyter notebook that visualise the attention scores of a BERT (Bidirectional Encoder Representations from Transformers) model.                                                                                                                      |

## Getting Started

Follow these steps to run the mini project:
```bash
pip install -r requirements.txt
```

Run Jupyter Lab
```bash
jupyter lab
```