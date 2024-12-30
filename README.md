# interview
# Text Classification using BERT

This project demonstrates how to perform text classification using BERT (Bidirectional Encoder Representations from Transformers) on a dataset of abstracts. The model is fine-tuned on the dataset to classify texts into binary categories.

## Table of Contents

- [Project Overview](#project-overview)
- [Setup Instructions](#setup-instructions)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Usage](#usage)
- [License](#license)

## Project Overview

The main goal of this project is to build a text classification model that can classify abstracts into predefined categories. We utilize the BERT model from Hugging Face's `transformers` library to tokenize and process the text. The model is fine-tuned for a binary classification task, where we classify each abstract into one of two categories.

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/text-classification-bert.git
   cd text-classification-bert
   
pip install -r requirements.txt

pip install torch torchvision transformers datasets

python train_model.py
