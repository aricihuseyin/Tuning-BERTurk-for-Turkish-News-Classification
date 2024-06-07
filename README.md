# Fine-Tuning BERTurk for Turkish News Classification

This repository contains the code and resources for fine-tuning a pre-trained BERTurk model to classify Turkish news articles into multiple categories. The dataset used for this project consists of news articles labeled with categories such as sports, politics, technology, economy, culture, world, and health.

## Project Overview

The aim of this project is to leverage the `bert-base-turkish-uncased` model provided by Hugging Face to perform multiclass text classification on Turkish news articles. The pre-trained BERTurk model is fine-tuned using a labeled dataset, and its performance is evaluated based on training and test accuracy, as well as a confusion matrix.

## Deliverables

- **Code File:** The code for fine-tuning the BERTurk model is provided in a Jupyter notebook (`Tuning BERTurk for Turkish News Classification.ipynb`).
- **Fine-Tuning Parameters:** The main fine-tuning parameters used are:
  - Learning rate (`lr`): `2e-5`
  - Number of epochs: `4`
  - Batch size: `16`
- **Confusion Matrix:** Confusion matrices for both the training and test datasets are generated and visualized as separate charts.
- **Prediction Results:** The fine-tuned model makes predictions on a set of example news articles, and the results are displayed with their original category names.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/arici.huseyin/fine-tuning-berturk-for-turkish-news-classification.git
   cd fine-tuning-berturk-for-turkish-news-classification
