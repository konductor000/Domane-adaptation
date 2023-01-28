## Domain Adaptation for NLP

This GitHub project explores the use of domain adaptation techniques on a pre-trained BERT model for Named Entity Recognition (NER) using two datasets: wnut and conll. The goal is to improve the model's performance on the wnut dataset by fine-tuning it using different methods. The project was implemented in Google Colab.  
### Datasets

- wnut: A dataset of tweets and web pages for NER.
- conll: A dataset of news articles for NER.

### Model

- Pre-trained BERT model for NER task.

### Results

The results are sorted from the best to the worst, according to the performance on the wnut dataset.

- Fine-tuning on the entire wnut dataset
- Fine-tuning on 25% of the wnut sentences that are most similar to the wnut dataset
- Fine-tuning on 50% of the wnut sentences that had the highest probability before tuning
- Fine-tuning only the model's classifier on the wnut dataset

### Usage

You can run this project using Google Colab

[Colab link](https://colab.research.google.com/github/konductor000/Domane-adaptation/blob/main/domain_adaptation.ipynb)
