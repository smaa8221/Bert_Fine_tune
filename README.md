# Fine-Tuning BERT for Sentiment Analysis
This repository contains the code used for fine-tuning a pre-trained BERT model using the Hugging Face Transformers library for sentiment analysis.

# Table of Contents
* Introduction
* Setup
* Code Structure
* Usage
* Results
* Introduction

This project demonstrates the step-by-step process of fine-tuning a pre-trained BERT model using the Hugging Face Transformers library for sentiment analysis. We use the IMDB dataset and the bert-base-cased model to achieve state-of-the-art results.

# Setup
* Clone this repository: git clone https://github.com/your-username/fine-tuning-bert.git
* Install the required libraries: pip install transformers torch
* Download the pre-trained bert-base-cased model from Hugging Face: huggingface_hub download bert-base-cased

# Code Structure
The code is organized as follows:

* data: contains the IMDB dataset
* models: contains the pre-trained bert-base-cased model and the fine-tuned PEFT model
* train.py: contains the training code for the fine-tuned PEFT model
* inference.py: contains the inference code for the fine-tuned PEFT model

# Usage
1. Train the fine-tuned PEFT model: python train.py
2. Run inference on a sample text: python inference.py

# Results
The accuracy of the fine-tuned PEFT model is:

* Foundational model without fine tuning: 0.496%
* Training #1: 0.88%
* Training #2: 0.899%
Note: The results may vary depending on the system configuration and the dataset used.

# License
This project is licensed under the MIT License.

# Acknowledgments
This project was inspired by the Hugging Face Transformers library and the IMDB dataset.

# Contact
This repository is originally used in the blog: [Link to the blog](https://www.linkedin.com/pulse/mastering-fine-tuning-llm-models-effortlessly-hugging-kerbachi-xcnhe/?trackingId=l%2FiXDFzgQOi3ulfK8GsRmw%3D%3D)
