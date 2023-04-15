# unsupervised-topic-modeling

![sample LDA](https://github.com/0xArwa/unsupervised-topic-modeling/blob/main/images/Figures%20of%20words%20associated%20with%20each%20topic%20for%20LDA%20Model.png)
## Table of Contents
- <a href="#1"> Description </a>
- <a href="#2"> Project Motivation </a>
- <a href="#3"> Installation </a>
- <a href="#4"> Dataset </a>
- <a href="#5"> Used Libraries </a>
- <a href="#6"> Results </a>
- <a href="#7"> Blog post </a>
- <a href="#8"> Acknowledgements </a>
<a id='1'></a>
## Description 📜
Topic modeling is task in natural language processing (NLP) aims to discover latent topics or themes in a collection of unstructured text data, without the need of any labeled data. The goal of topic modeling is to uncover the semantic structure of a corpus of text by identifying groups of words that mostly co-occur in the same context. <br> This repository contains code for performing topic modeling on a given corpus of text.
<a id='2'></a>
## Project Motivation ✨
The motivation behind this project is to gain a better understanding of how topic 
modeling can be applied to real-world problems and to develop a practical skill set in this area.
Furthermore, this project will also allow me to refine my skills in data preprocessing,
exploratory data analysis, and machine learning. <br> Through this project, I aim to showcase my ability
to develop and implement a data science solution to a complex problem.
<a id='3'></a>
## Installation ⚙️
The repository includes a Jupyter notebook which you can run on your local machine or you can use Google Colab.

<a id='4'></a>
## Dataset 📊
The dataset includes around 190K rows and 6 columns. <br>
The variables included in the dataset are:

- `title` (str): Article title.
- `text` (str): Article full text.
- `url` (str): Article URL.
- `authors` (list of list of str): Author name.
- `timestamp` (str): datetime of the published article.
- `tags` (list of list of str): List of tags associated to the article.

The dataset was retrived from Kaggle [<a href="https://www.kaggle.com/datasets/fabiochiusano/medium-articles?resource=download">link</a>]
<a id='5'></a>
## Used Libraries 📚
- `Pandas`
- `NLTK`
- `matplotlib`
- `gensim`
- `sklearn`
- `wordcloud`

<a id='6'></a>
## Results 🪄
![scores](https://github.com/0xArwa/unsupervised-topic-modeling/blob/main/images/output.png)

3 algorithms were tested and evaluated and these are the results:
| #Model    | #Coherence Score   |
| :---: | :---: |
| LDA   | 0.425   |
| NMF   | 0.581   |
| LSA   | 0.471   |

The NMF algorithm achived the highest score and the model was fine-tuned based on topic numbers as shown in the above figure.
<a id='7'></a>
## Blog post  📝
Check out the article that I have published on Meduim <a href="https://medium.com/@arwaomayrah/a-comparative-analysis-of-lda-nnmf-and-lsa-algorithms-for-topic-modeling-4b6d7ad28a8c">HERE</a>. 

<a id='8'></a>
## Acknowledgements
- Medium. (2022). 190k+ Medium Articles [Data set]. Kaggle. <a href="https://www.kaggle.com/datasets/fabiochiusano/medium-articles?resource=download"> Link </a>
- This project is part of Udacity Data Scientist Nanodegree Capstone Project <a href="https://www.udacity.com/">Link</a>
