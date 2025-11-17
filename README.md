# EfficientNet Classification

**Scene classification with aerial images and deep neural networks**

This repository contains code and experiments focused on **aerial scene
classification** using **deep neural networks**, specifically exploring
the EfficientNet architecture and feature augmentation with spectral
indices.

## 📌 Project Overview

The objective of this project is to classify aerial images into
different scene categories using deep learning models. The work is
divided into two main exercises:

**Reference for Dataset:**\
https://www.kaggle.com/datasets/valdivinosantiago/small-aid

------------------------------------------------------------------------

## 🧪 **Exercise 1 --- Deep Neural Network for Scene Classification**

**Task:**\
Using any deep neural network architecture suitable for scene
classification, try to obtain a **macro F1-score of at least 0.93** on the test
set. Additionally, provide the **confusion matrix** for the test
predictions.

**Approach:**\
- A deep CNN architecture (EfficientNet) was trained using the aerial
image dataset.\
- The model was optimized for high macro-F1 performance, ensuring
balanced results across all classes.\
- The confusion matrix was generated to visually analyze
misclassifications.

------------------------------------------------------------------------

## 🧪 **Exercise 2 --- Adding the NGRDI Spectral Index**

**Task:**\
For **all images** in both the **training** and **test** sets, compute
and add the **Normalized Green--Red Difference Index (NGRDI)** as an
additional channel.\
Then, using the *same model architecture* from Exercise 1, train the
model again and compute the **macro F1-score** on the test set.

**Reference for NGRDI:**\
See Table 2 of the article:\
https://pmc.ncbi.nlm.nih.gov/articles/PMC11085576/

**Questions to answer:**\
- Was the resulting performance better or worse compared to Exercise 1?\
- Explain why.\
- Present the confusion matrix generated with the enhanced dataset
(RGB + NGRDI).


------------------------------------------------------------------------

## 📂 Repository Structure

    /
    ├── small-aid/                # Dataset and image splits - download here https://www.kaggle.com/datasets/valdivinosantiago/small-aid
    ├── doc/                      # Exercises and answers
    ├── efficientnet.ipynb        # Notebook Exercise 1
    ├── efficientnet_NGRDI.ipynb  # Notebook Exercise 2
    └── readme.md                 # Project documentation

## 📜 Citation

If you use part of this project, please cite the repository, dataset or the
article referenced for NGRDI.
