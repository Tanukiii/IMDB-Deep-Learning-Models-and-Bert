# Sentimental Analysis(感情分析) in IMDB 
# Deep Learning (DNN,LSTM) and Bert for Sentimental Analysis

This is a tutorial of Deep Learning model(DNN,LSTM) and Bert(Ktrain)for Sentimental analysis.

Here, I provide the data visualization and 4 models

このレポジトリーはディープラーニングモデル（DNN、LSTM,Bert）を用いた感情分析のチュートリアルとなっています。

ここではデータ分析と４つのモデルを提供しています

### 1.Deep Neurak Network model with TF-IDF tokenizer

### 2.Deep Neurak Network model with USEM(Universal Sentence Encoding)

### 3.RNN model(LSTM)

### 4.Bert(K-train);but I recommend Googlecolab


I introduce the above models on
[My blog](https://tanuki.blog) (written  Japanese), so please check it.

Anyhow, lets's move on!

僕の[ブログ](https://tanuki.blog)にて、このプロジェクトとモデルの内容を詳しく説明しておりますのでよければ見てください！


## Summary Installation

  - [Installation](#Installation)
  - [IMDB](#IMDB)
  - [Model](#Model)
  - [Bert](#Bert)
  - [Result](#Result)
  - [Reference](#Reference)
  - [Notes](#Notes)


## Installation
- Python 3.6.8

- tensorflow 2.3.1

- tensorflow-datasets 3.2.1

- tensorflow-hub 0.6.0

- tensorflow-text 2.3.0




## IMDb

>IMDb (short for Internet Movie Database)is an online database of information related to films, television programs, home videos, video games, and streaming content online – including cast, production crew and personal biographies, plot summaries, trivia, ratings, and fan and critical reviews. An additional fan feature, message boards, was abandoned in February 2017. Originally a fan-operated website, the database is owned and operated by IMDb.com, Inc., a subsidiary of Amazon. As of January 2020, IMDb has approximately 6.5 million titles (including episodes) and 10.4 million personalities in its database, as well as 83 million registered users.(Wikipedia)

## Model

1.Deep Neurak Network model with TF-IDF tokenizer

2.Deep Neurak Network model with USEM(Universal Sentence Encoding)

3.RNN model(LSTM)

4.Bert(K-train)


## Bert

After downloading and mounting the csv file, install ktrain on google colab

    !pip3 install ktrain


## Result

| Accuracy | Model |
| --- | :--- |
| 0.9060 | Deep Neurak Network model with TF-IDF tokenizer |
| 0.8026 | Deep Neurak Network model with USEM |
| 0.8447 | RNN model(LSTM) |
| git diff | Bert(K-train) |


## Reference 

  - [IMDb](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/): Data set
  
  - [USEM](https://tfhub.dev/google/universal-sentence-encoder-multilingual/3/): Tensorflow hub
  
  - [Ktrain](https://github.com/amaiya/ktrain/): Ktrain
  
  - [Creative Commons](https://creativecommons.org/) 
  
  ## Notes
  Suddenly Deep Neurak Network model with USEM doesn't work because I can't use USE.Now, I'm finding the reason.
  
  After fixing the part, I'll rewrite the part.

