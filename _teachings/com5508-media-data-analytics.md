---
layout: course
title: COM5508 Media Data Analytics
description: A graduate course on computational methods for media research, covering data collection, text mining, network analysis, and machine learning applications in communication studies.
instructor: "Xiaofan Liu (Teaching Assistant: Zhicong Chen)"
year: 2019
term: Spring
location: City University of Hong Kong
course_id: media-data-analytics
schedule:
  - week: 1
    date: "Week 1"
    topic: "Introduction to Computational Communication Research"
    description: "Overview of big data in media studies; the promise and limitations of computational methods; research workflow."
    materials:
      - name: "Computational Communication Research (Atteveldt et al.)"
        url: "https://computationalcommunication.org/"
      - name: "Lazer et al. 2009 — Computational Social Science"
        url: "https://www.science.org/doi/10.1126/science.1167742"
  - week: 2
    date: "Week 2"
    topic: "Python for Media Research"
    description: "Python environment setup, Jupyter notebooks, pandas basics, data types and structures."
    materials:
      - name: "Python Official Tutorial"
        url: "https://docs.python.org/3/tutorial/"
      - name: "pandas Getting Started"
        url: "https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html"
  - week: 3
    date: "Week 3"
    topic: "Collecting Data from APIs"
    description: "REST APIs, authentication, rate limiting; collecting data from social media and news APIs."
    materials:
      - name: "Requests Library"
        url: "https://docs.python-requests.org/en/latest/"
      - name: "Guardian API"
        url: "https://open-platform.theguardian.com/"
  - week: 4
    date: "Week 4"
    topic: "Web Scraping for Media Research"
    description: "Scraping news sites, HTML parsing with BeautifulSoup, handling dynamic pages with Selenium."
    materials:
      - name: "Beautiful Soup Docs"
        url: "https://www.crummy.com/software/BeautifulSoup/bs4/doc/"
      - name: "Scrapy Framework"
        url: "https://scrapy.org/"
  - week: 5
    date: "Week 5"
    topic: "Text Preprocessing and Representation"
    description: "Tokenization, stopwords, stemming, TF-IDF; building document-term matrices."
    materials:
      - name: "NLTK Book — Chapter 1"
        url: "https://www.nltk.org/book/ch01.html"
      - name: "scikit-learn Text Features"
        url: "https://scikit-learn.org/stable/modules/feature_extraction.html#text-feature-extraction"
  - week: 6
    date: "Week 6"
    topic: "Content Analysis and Dictionary Methods"
    description: "Automated content analysis; sentiment dictionaries; LIWC; validation strategies."
    materials:
      - name: "LIWC"
        url: "https://www.liwc.app/"
      - name: "Quanteda (R, reference)"
        url: "https://quanteda.io/"
  - week: 7
    date: "Week 7"
    topic: "Topic Modeling with LDA"
    description: "Latent Dirichlet Allocation; selecting K; interpreting and labelling topics; stability."
    materials:
      - name: "Gensim LDA Tutorial"
        url: "https://radimrehurek.com/gensim/auto_examples/tutorials/run_lda.html"
      - name: "pyLDAvis"
        url: "https://github.com/bmabey/pyLDAvis"
      - name: "Blei et al. 2003 — LDA Paper"
        url: "https://jmlr.org/papers/v3/blei03a.html"
  - week: 8
    date: "Week 8"
    topic: "Social Network Analysis I: Basics"
    description: "Graph theory fundamentals; degree, betweenness and closeness centrality; NetworkX."
    materials:
      - name: "NetworkX Documentation"
        url: "https://networkx.org/documentation/stable/"
      - name: "Networks, Crowds, and Markets (free)"
        url: "https://www.cs.cornell.edu/home/kleinber/networks-book/"
  - week: 9
    date: "Week 9"
    topic: "Social Network Analysis II: Communities"
    description: "Community detection algorithms; modularity; information diffusion; visualisation with Gephi."
    materials:
      - name: "Gephi"
        url: "https://gephi.org/"
      - name: "python-louvain"
        url: "https://pypi.org/project/python-louvain/"
  - week: 10
    date: "Week 10"
    topic: "Machine Learning for Media Classification"
    description: "Naive Bayes, SVM, random forests; train/test split; precision, recall, F1."
    materials:
      - name: "scikit-learn User Guide"
        url: "https://scikit-learn.org/stable/user_guide.html"
      - name: "Confusion Matrix Explained"
        url: "https://scikit-learn.org/stable/modules/model_evaluation.html#confusion-matrix"
  - week: 11
    date: "Week 11"
    topic: "Word Embeddings and Semantic Analysis"
    description: "Word2Vec, GloVe; using pre-trained embeddings; semantic similarity in media text."
    materials:
      - name: "GloVe Vectors (Stanford NLP)"
        url: "https://nlp.stanford.edu/projects/glove/"
      - name: "Gensim Word2Vec"
        url: "https://radimrehurek.com/gensim/auto_examples/tutorials/run_word2vec.html"
  - week: 12
    date: "Week 12"
    topic: "Research Design and Reproducibility"
    description: "Pre-registration, open data, replication; writing up computational studies; ethical considerations."
    materials:
      - name: "OSF (Open Science Framework)"
        url: "https://osf.io/"
      - name: "The Turing Way (reproducibility guide)"
        url: "https://the-turing-way.netlify.app/"
  - week: 13
    date: "Week 13"
    topic: "Student Project Presentations I"
    description: "Student teams present computational media research projects."
    materials:
  - week: 14
    date: "Week 14"
    topic: "Student Project Presentations II"
    description: "Remaining presentations; course wrap-up and reflections."
    materials:
---

## Course Overview

This graduate seminar introduces students to computational and quantitative methods for media and communication research. Topics span the full research pipeline: data collection (APIs, scraping), text analysis (sentiment, topic modeling, word embeddings), social network analysis, and machine learning classification.

*Zhicong Chen served as Teaching Assistant for this course.*

## Learning Objectives

By the end of this course, students will be able to:

- Collect large-scale media and social data programmatically using APIs and web scraping
- Apply text mining techniques (TF-IDF, topic modeling, sentiment analysis) to communication research questions
- Construct and analyse social networks from media interaction data
- Train and evaluate machine learning classifiers on media content
- Critically assess the validity and ethics of computational media research

## Level

Graduate (PhD and Research Masters)

## Institution

Department of Media and Communication, City University of Hong Kong

## Key Software and Libraries

| Tool | Purpose | Link |
|------|---------|------|
| Python 3 | Core language | [python.org](https://www.python.org/) |
| NLTK | NLP preprocessing | [nltk.org](https://www.nltk.org/) |
| Gensim | Topic models & word vectors | [radimrehurek.com/gensim](https://radimrehurek.com/gensim/) |
| scikit-learn | Machine learning | [scikit-learn.org](https://scikit-learn.org/stable/) |
| NetworkX | Network analysis | [networkx.org](https://networkx.org/) |
| Gephi | Network visualisation | [gephi.org](https://gephi.org/) |
| Beautiful Soup | Web scraping | [crummy.com/software/BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) |

## Recommended Texts

- Salganik, M. J. (2017). [*Bit by Bit: Social Research in the Digital Age*](https://www.bitbybitbook.com/) — free online.
- Grimmer, J., Roberts, M. E., & Stewart, B. M. (2022). [*Text as Data*](https://press.princeton.edu/books/paperback/9780691207551/text-as-data). Princeton UP.

## Assessment

| Component | Weight |
|-----------|--------|
| Weekly lab exercises | 30% |
| Literature review | 20% |
| Final research project | 45% |
| Participation | 5% |
