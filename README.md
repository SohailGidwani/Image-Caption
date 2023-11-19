# Image Caption Generator

## Overview

This repository contains code for an Image Caption Generator trained on the Flicker30k dataset. The model utilizes a combination of Convolutional Neural Networks (CNNs) for feature extraction and Transformers for sequence generation.

## Dataset

The model is trained on the Flicker30k dataset, a diverse collection of images with corresponding captions.

## Evaluation Metric

Accuracy is measured using BLEU (BiLingual Evaluation Understudy) Score, providing a quantitative measure of the generated captions' similarity to human-generated reference captions.

## Usage

1. **Data Preparation:**
   - Download and preprocess the Flicker30k dataset.

2. **Model Training:**
   - Run the training script, specifying dataset paths and desired hyperparameters.

3. **Evaluation:**
   - Evaluate the model using BLEU Score on a validation set.

4. **Inference:**
   - Generate captions for new images using the trained model.

## Dependencies

- Python 3.x
- TensorFlow (or other deep learning framework)

