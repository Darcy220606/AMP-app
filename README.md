# AMP-app
deepchain.bio | Antimicrobial peptide recognition 

## Install AMP conda environment

From the root of this repo, ```run conda env create -f environment.yaml```

Make sure you've tensorflow==2.5.0 installed

Follow this [tutorial](https://docs.neptune.ai/integrations-and-supported-tools/model-training/tensorflow-keras#step-5-monitor-your-tensorflow-keras-training-in-neptune) to make neptune logger works

## Abstarct: 

Antimicrobial peptides (AMPs) are a class of small peptides that widely exist in nature and they are an important part of the innate immune system of different organisms. AMPs have a wide range of inhibitory effects against bacteria, fungi, parasites, and viruses. The emergence of antibiotic-resistant microorganisms and the increasing concerns about the use of antibiotics resulted in the development of AMPs, which have good application prospects in medicine, food, animal husbandry, agriculture, and aquaculture. Faced with this reality, Machine learning methods are now commonly adopted by wet-laboratory researchers to screen for promising candidates in less time. In this app, we propose a deep convolutional neural network model associated with a long short-term memory layer called CNN-LSTM, for extracting and combining discriminative features from different information sources in an interactive way. 
Performance Details: using the 10-Fold Cross-Validation, our model outperforms 90.0% (Standard Deviation: +/-1.69%) accuracy, 87.28% (+/-2.69%) sensitivity, 93.32% (+/-2.38%) specificity, 80.81 (+/-3.36) MCC,  96.02% (+/-0.99%) roc_auc and 96.63% (+/-0.73%) roc_pr.



## Model Architecture:

![image Info](file:///home/haifa/Downloads/AMP-app.drawio.png)

## Specifications

This work is based on the paper : Deep learning improves antimicrobial peptide recognition.  Models and datasets are made freely available through the Antimicrobial Peptide Scanner vr.2 web server at www.ampscanner.com.

