---
layout: course
title: Text as Data
description: A graduate course on computational text analysis methods for social science research, covering topic modeling, word embeddings, sentiment analysis, and large language models.
instructor: Zhicong Chen
year: 2025
years: [2024, 2025]
term: Spring
location: Nanjing University
course_id: text-as-data
schedule:
  - week: 1
    date: "Week 1"
    topic: "Introduction: Why Text as Data?"
    description: "Overview of computational text analysis in social science; the bag-of-words assumption; units of analysis."
    materials:
      - name: "Grimmer et al. — Text as Data (Princeton UP)"
        url: "https://press.princeton.edu/books/paperback/9780691207551/text-as-data"
      - name: "Computational Social Science (Lazer et al., 2020)"
        url: "https://www.science.org/doi/10.1126/science.aaz8170"
  - week: 2
    date: "Week 2"
    topic: "Text Preprocessing"
    description: "Tokenisation, lowercasing, stopword removal, stemming vs. lemmatisation, regex."
    materials:
      - name: "NLTK Book — Chapter 3"
        url: "https://www.nltk.org/book/ch03.html"
      - name: "spaCy 101"
        url: "https://spacy.io/usage/spacy-101"
      - name: "spaCy Download"
        url: "https://spacy.io/"
  - week: 3
    date: "Week 3"
    topic: "Representing Text: Bag-of-Words and TF-IDF"
    description: "Document-term matrices, TF-IDF weighting, cosine similarity, feature selection."
    materials:
      - name: "scikit-learn: Text Feature Extraction"
        url: "https://scikit-learn.org/stable/modules/feature_extraction.html#text-feature-extraction"
      - name: "TF-IDF Explained"
        url: "https://en.wikipedia.org/wiki/Tf%E2%80%93idf"
  - week: 4
    date: "Week 4"
    topic: "Dictionary Methods and Sentiment Analysis"
    description: "Lexicon-based approaches (LIWC, VADER, SentiWordNet); counting and scaling; validation."
    materials:
      - name: "VADER Sentiment (Python)"
        url: "https://github.com/cjhutto/vaderSentiment"
      - name: "LIWC"
        url: "https://www.liwc.app/"
      - name: "TextBlob"
        url: "https://textblob.readthedocs.io/en/dev/"
  - week: 5
    date: "Week 5"
    topic: "Topic Modeling: LDA"
    description: "Latent Dirichlet Allocation; hyperparameters (alpha, beta, K); interpreting topics; coherence metrics."
    materials:
      - name: "Gensim LDA Tutorial"
        url: "https://radimrehurek.com/gensim/auto_examples/tutorials/run_lda.html"
      - name: "LDA Visualization (pyLDAvis)"
        url: "https://github.com/bmabey/pyLDAvis"
      - name: "Blei et al. 2003 — Original LDA Paper"
        url: "https://jmlr.org/papers/v3/blei03a.html"
  - week: 6
    date: "Week 6"
    topic: "Topic Modeling: BERTopic and CTM"
    description: "Neural topic models; BERTopic pipeline; comparing LDA vs. neural approaches."
    materials:
      - name: "BERTopic Documentation"
        url: "https://maartengr.github.io/BERTopic/index.html"
      - name: "BERTopic Paper"
        url: "https://arxiv.org/abs/2203.05794"
  - week: 7
    date: "Week 7"
    topic: "Word Embeddings: Word2Vec and GloVe"
    description: "Distributional semantics; skip-gram and CBOW; analogies; GloVe pre-trained vectors."
    materials:
      - name: "Gensim Word2Vec Tutorial"
        url: "https://radimrehurek.com/gensim/auto_examples/tutorials/run_word2vec.html"
      - name: "GloVe Vectors (Stanford NLP)"
        url: "https://nlp.stanford.edu/projects/glove/"
      - name: "Word2Vec Illustrated"
        url: "https://jalammar.github.io/illustrated-word2vec/"
  - week: 8
    date: "Week 8"
    topic: "Contextualized Embeddings: BERT"
    description: "Transformers overview; BERT architecture; fine-tuning for text classification."
    materials:
      - name: "Hugging Face Transformers Docs"
        url: "https://huggingface.co/docs/transformers"
      - name: "The Illustrated BERT (Jay Alammar)"
        url: "https://jalammar.github.io/illustrated-bert/"
      - name: "BERT Paper"
        url: "https://arxiv.org/abs/1810.04805"
  - week: 9
    date: "Week 9"
    topic: "Text Classification"
    description: "Naive Bayes, logistic regression, SVMs, transformer classifiers; train/test split; cross-validation."
    materials:
      - name: "scikit-learn Text Classification Tutorial"
        url: "https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html"
      - name: "Hugging Face Text Classification"
        url: "https://huggingface.co/docs/transformers/tasks/sequence_classification"
  - week: 10
    date: "Week 10"
    topic: "Large Language Models for Research"
    description: "GPT-4 / Claude API as annotation tools; prompt engineering; zero-shot and few-shot classification."
    materials:
      - name: "OpenAI API Documentation"
        url: "https://platform.openai.com/docs/"
      - name: "Anthropic Claude API"
        url: "https://docs.anthropic.com/"
      - name: "Ziems et al. 2024 — Can LLMs replace human annotators?"
        url: "https://aclanthology.org/2024.acl-long.539/"
  - week: 11
    date: "Week 11"
    topic: "Named Entity Recognition and Information Extraction"
    description: "NER with spaCy and Hugging Face; relation extraction; event detection."
    materials:
      - name: "spaCy NER Docs"
        url: "https://spacy.io/usage/linguistic-features#named-entities"
      - name: "Hugging Face NER"
        url: "https://huggingface.co/docs/transformers/tasks/token_classification"
  - week: 12
    date: "Week 12"
    topic: "Validation and Measurement"
    description: "Inter-rater reliability (Cohen's kappa), precision/recall/F1, construct validity, replication."
    materials:
      - name: "Krippendorff's Alpha"
        url: "https://en.wikipedia.org/wiki/Krippendorff%27s_alpha"
      - name: "Guidelines for Human Annotation (Artstein & Poesio)"
        url: "https://aclanthology.org/J08-4004/"
  - week: 13
    date: "Week 13"
    topic: "Final Project Presentations"
    description: "Students present computational text analysis projects on communication data."
    materials:
---

## Course Overview

This course introduces graduate students to the computational text analysis toolkit used in communication and social science research. Students gain hands-on experience transforming unstructured text into structured data, applying classical NLP methods and large language models.

## Learning Objectives

By the end of this course, students will be able to:

- Preprocess and represent text corpora for computational analysis
- Apply sentiment analysis, topic modelling, and word embeddings to communication research questions
- Fine-tune or prompt large language models for annotation and classification tasks
- Evaluate the validity and reliability of text-based measurements
- Design and execute an original computational text analysis study

## Prerequisites

- Proficiency in Python and pandas (Introduction to Python or equivalent)
- Basic familiarity with social science research methods

## Level

Graduate

## Institution

School of Journalism and Communication, Nanjing University

## Offered

Spring 2024, Spring 2025

## Required Text

Grimmer, J., Roberts, M. E., & Stewart, B. M. (2022). [*Text as Data: A New Framework for Machine Learning and the Social Sciences*](https://press.princeton.edu/books/paperback/9780691207551/text-as-data). Princeton University Press.

## Key Python Libraries

| Library | Purpose | Link |
|---------|---------|------|
| NLTK | Classic NLP toolkit | [nltk.org](https://www.nltk.org/) |
| spaCy | Industrial-strength NLP | [spacy.io](https://spacy.io/) |
| Gensim | Topic models & word vectors | [radimrehurek.com/gensim](https://radimrehurek.com/gensim/) |
| scikit-learn | ML classifiers & vectorisers | [scikit-learn.org](https://scikit-learn.org/stable/) |
| Hugging Face Transformers | BERT, GPT, and more | [huggingface.co](https://huggingface.co/) |
| BERTopic | Neural topic modelling | [maartengr.github.io/BERTopic](https://maartengr.github.io/BERTopic/) |
| VADER | Rule-based sentiment | [github.com/cjhutto/vaderSentiment](https://github.com/cjhutto/vaderSentiment) |

## Useful Datasets

- [Hugging Face Datasets Hub](https://huggingface.co/datasets) — thousands of NLP datasets
- [GDELT Project](https://www.gdeltproject.org/) — global news events
- [Pushshift Reddit Archive](https://arxiv.org/abs/2001.08435)

## Assessment

| Component | Weight |
|-----------|--------|
| Weekly coding labs | 35% |
| Midterm method paper | 20% |
| Final research project | 40% |
| Participation | 5% |
