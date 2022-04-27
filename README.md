# NLP-BERT-exploring-hatespeech
This repository contains fine-tuned models for hate speech classification tasks on English tweets in the context of the Russian-Ukraine war. It presents the results of a pre-trained BERT model (bert-base-uncased) from Hugging Face and its performance using different architectures. 

# Data
I worked with two sources of datasets. The first one comes from https://huggingface.co/datasets/tweets_hate_speech_detection and I used it to fine-tune the BERT. 

The second one was extracted directly from Twitter and contains a sample of 1000 tweets in English related to the Ukraine-Russia war context. I use this data set to evaluate the performance of the pre-trained BERT. 

# Excersise and architectures

I tried three architectures of classifiers.

1) Linear
2) ReLu Linear
3) Relu Relu Linear

I also explore how the results changed when the BERT was fine-tuned with a highly unbalanced class dataset. 

