# Quora Insincere Question Classifier
---
## Insincere Question Classification: Unmasking Deception on Quora

This repository contains the code and resources for the project on insincere question classification on Quora. The goal of this project is to develop a machine learning model that can accurately identify and classify insincere or deceptive questions on the Quora platform.

## Dataset
The project utilizes the Quora Insincere Questions Classification dataset, which is publicly available on Kaggle. This dataset consists of a large collection of questions from Quora, along with labels indicating whether each question is sincere or insincere. The dataset serves as the foundation for training and evaluating our classification model.

### Dataset Columns Description
- `qid`: Unique question identifier
- `question_text`: Text of the question
- `target`: Binary label indicating whether the question is insincere (1) or sincere (0)

## Methodology
The project follows a supervised learning approach to tackle the problem of insincere question classification. It involves several key steps, including data collection, data preprocessing, feature extraction, model selection, model training, and model evaluation.

### Approach
1. Data Collection: The Quora Insincere Questions Classification dataset is collected and downloaded from Kaggle. The data structures and features will be explored to gain a better understanding of the dataset.

2. Data Preprocessing: Text data is preprocessed by tokenization, lowercasing, and removal of stop words and punctuation. 

3. Feature Extraction: The preprocessed text data will be transformed into numerical representations suitable for machine learning algorithms. For this project, we will be using word embeddings, such as Word2Vec or GloVe, to convert the text into dense vector representations that capture semantic relationships between words.

4. Model Selection and Training: For this project, we will explore various NLP models suitable for insincere question classification, such as recurrent neural networks (RNNs), convolutional neural networks (CNNs), long short term memory (LSTM), or transformer models like BERT. These models have shown promising results in NLP tasks and can capture complex patterns and dependencies in text data. We will select the most appropriate model based on its performance on the validation dataset and train it using the labeled training dataset.

5. Model Evaluation: The trained NLP model will be evaluated using appropriate evaluation metrics, such as accuracy, precision, recall, and F1-score. The performance of the model will be assessed on the test dataset.

## Repository Structure
- `1. Data/`: Holds the Quora Insincere Questions Classification dataset.
- `2. Notebooks/`: Contains Jupyter notebooks with code for data collection, data preprocessing, NLP model development, and evaluation.
- `3. Models/`: Contains the trained NLP model checkpoints.
- `4. Utils/`: Includes utility functions and scripts used in the project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
