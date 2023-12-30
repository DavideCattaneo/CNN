# CNN - Histopathologic Cancer Detection 
This project is part of the Coursera Introduction to Deep Learning course. The main goal is a binary image classification task, involving the identification of metastatic cancer in small image patches extracted from larger digital pathology scans.

[Kaggle competition](https://www.kaggle.com/competitions/histopathologic-cancer-detection/overview)


# Dataset

> In this dataset, you are provided with a large number of small pathology images to classify. Files are named with an image id. The train_labels.csv file provides the ground truth for the images in the train folder. You are predicting the labels for the images in the test folder. A positive label indicates that the center 32x32px region of a patch contains at least one pixel of tumor tissue. Tumor tissue in the outer region of the patch does not influence the label. This outer region is provided to enable fully-convolutional models that do not use zero-padding, to ensure consistent behavior when applied to a whole-slide image.
The original PCam dataset contains duplicate images due to its probabilistic sampling, however, the version presented on Kaggle does not contain duplicates. We have otherwise maintained the same data and splits as the PCam benchmark

The dataset can be downloaded [here](https://www.kaggle.com/c/histopathologic-cancer-detection/data)

# Score
The model scored _0.83_ on the kaggle leaderboard

# Reference
- [Histopathologic Cancer Detection](https://www.kaggle.com/competitions/histopathologic-cancer-detection)
