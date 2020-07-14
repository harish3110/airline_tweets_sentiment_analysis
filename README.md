# About

This repository contains code for building a Sentiment Classifier on Kaggle's [Twitter Airlines Tweets](https://www.kaggle.com/crowdflower/twitter-airline-sentiment#Tweets.csv) by using the famous [ULMFiT]() approach and decoding the methodologies used in the paper. 

## The ULMFiT approach
The Universal Language Model Fine-tuning (ULMFiT) is an inductive transfer learning approach developed by Jeremy Howard and Sebastian Ruder to all the tasks in the domain of natural language processing which sparked the usage of transfer learning in NLP tasks. 

**The ULMFiT approach to training NLP models is heralded as the ImageNet moment in the domain of Natural Language Processing** 

The model architecture used in the entire process of the ULMFiT approach is ubiquitous and is the well-known **AWD-LSTM** architecture. 

The ULMFiT approach can be braodly explained in the 3 major steps as shown below:
![](https://miro.medium.com/max/2000/1*9n9yv4EalUn76yP1Yffhfw.png 'The ULMFiT Process')

## Dependencies 
- Fastai2: ```pip install fastai2 --quiet```
- Kaggle API:  ```pip install kaggle  --quiet```

## References

- Fastai v2 [Documentation](www.dev.fasta.ai)
- Fastbook Chapter 10: [NLP Deep Dive](https://github.com/fastai/fastbook/blob/master/10_nlp.ipynb)
- ULMFiT [Paper](https://arxiv.org/abs/1801.06146)
