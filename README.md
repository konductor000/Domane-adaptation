
## Domain adaptation

I took Bert model trained on NER task and two datasets (wnut and conll). The model coped better with the first dataset than with the second. Then I fine-tuned model using different methods to choose which one is better.

### Results

The methods are sorted from the best to the worst.

- Fine-tune model on wnut dataset.
- Fine-tune on 25% conll sentences that are most simmilar to wnut dataset. There I used classifier and sentence embeddings to choose 25% sentences.
- Fine-tune on 50% wnut sentences that had the highest probability before tuning.
- Fine-tune only model's classifier on wnut dataset.

[Colab link](https://colab.research.google.com/drive/1LIDoZ_mbzad9EHWuh7PRsqbvfKF1Tgxw?usp=sharing)
