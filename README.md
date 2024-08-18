# English-to-Hindi Translator Project

## Overview

In this project, a deep neural network is developed as part of a machine translation pipeline. The system translates English text into Hindi, with the goal of achieving the highest possible translation accuracy.

## Description

To translate English sentences into Hindi, a model using an encoder-decoder architecture with Long Short-Term Memory (LSTM) units is built. The pipeline involves the following steps:

1. **Import Dataset and Explore It**
   - Load the dataset from the provided source.
   - Perform exploratory data analysis (EDA) to understand the dataset's structure and contents.

2. **Apply Necessary Data Preprocessing Steps**
   - Clean the data by removing unnecessary elements, handling missing values, and normalizing text.
   - Tokenize the text into words or subwords and create vocabulary lists for both languages.

3. **Prepare Data for Encoder and Decoder**
   - Format the data into sequences suitable for the encoder-decoder model.
   - Create training and validation datasets for model evaluation.

4. **Build Encoder and Decoder Architecture**
   - Design and implement the encoder and decoder using LSTM units.
   - Define the input and output layers, loss functions, and optimizers.

5. **Build the Model**
   - Integrate the encoder and decoder into a cohesive translation model.
   - Train the model on the preprocessed data.

6. **Predict**
   - Use the trained model to generate Hindi translations from English input sentences.
   - Evaluate the model's performance and make necessary adjustments.

## Dataset Information

- **Download Dataset:** [Kaggle Dataset](https://www.kaggle.com/umasrikakollu72/hindi-english-truncated-corpus)
- **Dataset Sources:**
  - TED: 39,881 records
  - Indic2012: 37,726 records
  - TIDES: 50,000 records

## Prerequisite Technical Skills

- **Python**
- **TensorFlow**
- **Keras**
- **NLTK**

## Kaggle Link

For a step-by-step tutorial on the English-to-Hindi Translator, refer to the following Kaggle notebook: [Get Step-by-Step Tutorial](https://www.kaggle.com/ysthehurricane/english-to-hindi-translator/notebook#Decoder-LSTM-Model)
