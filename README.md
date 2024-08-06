# NER-Entity-Extraction

This project uses a combination of Hugging Face Transformers and custom heuristics to extract named entities from text and categorize them.

## Installation

To run this project, you'll need to have Python installed. You can install the required dependencies using pip:

# Usage

You can run the code by executing the NER-Entity-Extraction.ipynb file. The script performs the following steps:

1) Initializes a Named Entity Recognition (NER) pipeline using a pre-trained BERT model.
2) Defines a function to create prompts for few-shot learning.
3) Extracts entities from text and categorizes them using the NER pipeline and custom heuristics.
4) Trains the model with few-shot examples.
5) Predicts named entities for a new complex input sentence.

# Code Overview

# Initialization
The code initializes the NER pipeline using the dbmdz/bert-large-cased-finetuned-conll03-english model from Hugging Face.

# Entity Extraction and Categorization
The extract_entities_with_categories function extracts entities from the text and categorizes them into predefined categories such as names, locations, dates, organizations, and miscellaneous.

# Few-Shot Learning
The train_model function creates few-shot learning examples to fine-tune the model for specific tasks.

# Prediction
The predict_ner function generates predictions for named entities in new input sentences and displays the results.

# API Key and Endpoint

Replace the API_KEY and API_ENDPOINT variables in the code with your own Hugging Face API key and endpoint.
