# Arabic-Question-Classification
This project aims to create Arabic Question Classification based on Standard Arabic dataset.
## Table of contents
* [Introduction](#introduction)
* [Results](#results)
* [Technologies](#technologies)
* [Setup](#setup)
* [Contact us](#contact-us)


## Introduction
Question Answer System is one of the interesting applications of Natural Language Processing.  This system passes through stages to generate an answer for a given question, one of these stages is Question Classification. Question classification plays a very important role in Question Answering systems. It gives a label to a question depending on the type of answer. This label will be used by the Answer Extraction module to generate the correct answer. In this project, we used Support Vector Machine and Naïve Bayes models with N-Grams models to classify questions into two main classes, which are “Color” and “Yes/No”. The dataset that is used in this project consists of 1645 questions about 18 classes of animals and transport vehicles. The obtained results are 100% for the Naïve Bayes model with two different n-gram models Twitter-CBOW and Wikipedia-CBOW. For the Support Vector Machine, the obtained results are 100% and 99.69% for Twitter-CBOW and Wikipedia-CBOW respectively.

## Results
![alt text](https://github.com/AfnanBq/Arabic-Question-Classification/blob/master/results.png?raw=true)

## Technologies
* python 
* Jupyter Notebook
* gensim 
* matplotlib 
* numpy 
* pandas 
* scikit-learn

## Setup
To run this project, install it locally:
* git clone https://github.com/AfnanBq/Arabic-Question-Classification.git
* cd ../Arabic-Question-Classification 
* install all the required libraries [Technologies](#technologies)


## Contact
* [Afnan Qalas](http://linkedin.com/in/afnanbalghaith)
* [Zarah Shibli](https://www.linkedin.com/in/zarah-shibli)
