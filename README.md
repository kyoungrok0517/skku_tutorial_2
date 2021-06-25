## Tutorial 2: Intro to sentiment analysis and topic modeling using scikit-learn and gensim

### Introduction

In this tutorial, you will learn how to build predictive model based on text data. Also, you will learn how to derive and visualize topics from text using LDA method. 

### Required Software

First, we recommend you to install [Anaconda distribution of Python](https://www.anaconda.com) which includes the packages useful for data science. Additionally, attendees will need to prepare their laptop with the following packages installed. 

* numpy
* scikit-learn
* pandas
* gensim
* seaborn
* spacy
* pyLDAvis
  
All the packages can be installed using the following command:

* `pip install -U numpy scikit-learn pandas gensim seaborn spacy pyLDAvis`
* `python -m spacy download en_core_web_sm`
* `python -m nltk.downloader popular`

### Tutorial Files

* Jupyter notebooks: 
* Datasets: data/sms.tsv, data/yelp.csv

### Instructors

* Jang, Kyoung-Rok (PhD student in KAIST IR & NLP)
  * Email: kyoungrok.jang (at) kaist.ac.kr
* Kim, Jeonghwan (MS student in KAIST IR & NLP)
  * Email: jeonghwankim123 (at) kaist.ac.kr

### Acknowledge

This tutorial is created based on the following resources.

*  Machine Learning with Text in scikit-learn ([link](https://github.com/justmarkham/pycon-2016-tutorial/))
* Gensim Topic Modeling - A Guide to Building Best LDA models ([link](https://www.machinelearningplus.com/topic-modeling-gensim-python/))
