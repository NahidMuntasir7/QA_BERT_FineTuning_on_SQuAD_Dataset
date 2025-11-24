# 📘 BERT Fine-Tuning for Extractive Question Answering

This project focuses on fine-tuning a pre-trained BERT model for extractive Question Answering using the SQuAD dataset. The goal is to train a model that can identify the exact span of text within a passage that answers a given question.

## Project Overview
The model is trained on the SQuAD dataset, which consists of context paragraphs, questions, and annotated answer spans. The input is tokenized for BERT, and the model is trained to predict the start and end token positions corresponding to the answer. This setup demonstrates how BERT can be adapted for span-based QA tasks.

## Training Details
- Pre-trained model: bert-base-uncased  
- Task: Extractive span prediction  
- Number of epochs: 2  

## Evaluation Results
Performance after two epochs of fine-tuning:

- Evaluation Loss: 1.44  
- Exact Match (EM): 55.8%  
- F1 Score: 67.27%  

These metrics show the model's ability to locate answer spans with reasonable accuracy within the given constraints.

## Conclusion
This project demonstrates how a pre-trained BERT model can be adapted for extractive question answering by predicting token-level answer spans. The results provide a clear view of the model’s performance after fine-tuning and help illustrate the practical steps involved in building span-based QA systems.
