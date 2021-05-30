# Diffuse large B-cell & Follicular lymphoma classification using ANOVA F-test feature selection method, SMOTE for over-sampling, & SVM, Random Forest classifiers

**Project Report by Anubhab Das** 

Date : 27th May, 2021

[![nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.jupyter.org/github/anubhabdaserrr/dlbcl-fl-lymphoma-classif/blob/main/DLBCL_FL_classif_nb.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anubhabdaserrr/dlbcl-fl-lymphoma-classif/blob/main/DLBCL_FL_classif_nb.ipynb)

## Objective & data

Text goes here

Data Source : [Link](https://file.biolab.si/biolab/supp/bi-cancer/projections/info/DLBCL.html)

**Note : Text.**

## Model & Training details

### Pipelines

The cross-validation pipeline needed extra care while designing to avoid any data leakage or other forms of overfitting which could be caused by performing scaling, oversampling & feature selection in the wrong order.

<img src="./misc/val_train_predict_pipelines.png" height = 500 />

### Data Augmentation
Text goes here.


## Evaluation & test performance
Text goes here.

### Finding optimal values of SMOTE minority fraction & no. of features in feature selection
<img src = './misc/optimize_features.png' width=500  /> <img src = './misc/optimize_smote.png' width=500  />

### Distribution of accuracy scores across various trials of cross-validation
<img src = './misc/acc_20_trails_distrib.png' width=400  /> <img src = './misc/acc_200_trails_distrib.png' width=400  />

### Feature importance scores 
<img src = './misc/ftrs_scores_50.png' /> <img src = './misc/ftrs_scores_grps_500.png' />

### Cross Validation
Text goes here

### Prediction
Text goes here

## Limitations and further improvements :
1. Lim1
2. Lim2

## References
1. [Ref1](google.com)
2. [Ref2](google.com)
