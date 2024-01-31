# A Comparative Analysis: Dual-Task CNN vs. Single-Task CNNs for Gender and Age Prediction in Facial Images

Author: Paolo Speziali

This repository contains the code and materials for a comparative analysis between a multi-task Convolutional Neural Network (CNN) and two single-task CNNs for age prediction and perceived gender detection in facial images. The study aims to evaluate their performance and differences in task execution.

## Abstract

This study conducts a comparative analysis between a multi-task Convolutional Neural Network (CNN) and two single-task CNNs for age prediction and perceived gender detection in facial images, aiming to evaluate their performance and differences in task execution.

The two single-task CNNs were designed with identical structures, differing only in the final part: one for age prediction and another for gender classification. The multi-task CNN incorporated a branching mechanism for both tasks, utilizing a shared loss function for backpropagation.

Evaluation metrics included R-squared score for age prediction, accuracy for gender classification, and visualization of mean attention heatmaps to discern disparities in which features the various convolutional layers focus on.

Results indicate that there are no significant differences in performance between the multi-task CNN and the single-task CNNs, suggesting comparable efficacy in gender and age prediction tasks.

## Project Structure

- `Latex/`: Contains the PDF and tex files of the short thesis.
- `Notebook/`:
  - `AgeGender-Multitask.ipynb`: Notebook of the multi-task network.
  - `AgeGender-Singletask.ipynb`: Notebook of the single-task networks.
  
## Dataset
You can download the UTKFace dataset
[here](https://www.kaggle.com/datasets/jangedoo/utkface-new).

