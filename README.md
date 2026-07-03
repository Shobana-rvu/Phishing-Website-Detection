# Phishing Website Detection

A deep learning project for detecting phishing websites by analyzing URL patterns and characteristics.

## Course

Fundamentals of Deep Learning

## Overview

This project implements a deep learning classification model to identify potentially malicious phishing websites. The system analyzes URLs and predicts whether they are legitimate or phishing attempts using transformer-based models.

## Project Structure

```
Phising_Website_Detection/
└── Colab_codes/
    ├── PWD_Training.ipynb    # Model training notebook
    └── PWD_Testing.ipynb     # Model testing notebook
```

## Features

- URL preprocessing and feature extraction
- SSL certificate validation
- Domain age verification
- Reputation checking via URLScan API
- Whitelist filtering for trusted domains
- Transformer-based classification model

## Prerequisites

- Python 3.x
- Google Colab (recommended)
- Required libraries:
  - torch
  - transformers
  - pandas
  - numpy
  - scikit-learn
  - python-whois
  - tldextract
  - requests

## Usage

### Training the Model

Open `PWD_Training.ipynb` in Google Colab and run all cells to train the model on the phishing detection dataset.

### Testing the Model

Open `PWD_Testing.ipynb` in Google Colab to test the trained model and evaluate its performance on new URLs.

## Model Architecture

The project uses a transformer-based sequence classification model with weighted loss to handle class imbalance in the dataset.

## Dataset

The model is trained on URLs labeled as:
- 0: Legitimate website
- 1: Phishing website

## License

This project is available for educational and research purposes.
