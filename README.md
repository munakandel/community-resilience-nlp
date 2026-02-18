# Community Resilience NLP: Emergency Detection and Prioritization from Hurricane Tweets

# Overview

This project develops a transformer-based Natural Language Processing (NLP) framework to automatically detect, classify, and prioritize emergency-related tweets during hurricane and disaster events. The system uses pre-trained transformer models (DistilBERT) fine-tuned on hurricane-related social media datasets to identify emergency requests, support offers, and general informational messages.

The objective is to transform unstructured social media data into structured, actionable intelligence that can support emergency responders and improve community resilience.

# Key Features

- Transformer-based emergency tweet classification using DistilBERT
- Multi-class message classification (emergency, support offer, neutral)
- Message type classification (informative, personal, other)
- Tweet preprocessing and cleaning pipeline
- Recency scoring based on timestamp
- Model training, evaluation, and deployment pipeline
- Prepared for extension with location extraction and request-support matching

# Project Pipeline

1. Data Collection  
   Hurricane-related tweet datasets obtained from CrisisNLP

2. Data Preprocessing  
   - Remove URLs, mentions, hashtags
   - Normalize and clean text
   - Remove duplicates
   - Compute recency and engagement features

3. Transformer Model Training  
   - Tokenization using DistilBERT tokenizer
   - Fine-tuning DistilBERT for classification
   - Train-validation-test split
   - Model evaluation using accuracy and F1 score

4. Emergency Prioritization Preparation  
   - Emergency probability scoring
   - Recency scoring
   - Engagement scoring

5. Model Deployment  
   - Saved trained models
   - Real-time prediction pipeline ready

# Technologies Used

- Python
- Hugging Face Transformers
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- spaCy 
- Sentence-Transformers


