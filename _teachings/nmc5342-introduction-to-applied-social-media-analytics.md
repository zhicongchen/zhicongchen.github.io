---
layout: course
title: "NMC5342 Introduction to Applied Social Media Analytics"
description: An applied graduate course covering methods for collecting, processing, and analyzing social media data, with emphasis on computational approaches to communication research.
instructor: Zhicong Chen
year: 2025
term: Fall
location: National University of Singapore
code: NMC5342
course_id: applied-social-media-analytics
schedule:
  - week: 1
    date: "Week 1"
    topic: "The Social Media Research Landscape"
    description: "Affordances of social media platforms; computational communication research; big data opportunities and pitfalls."
    materials:
      - name: "Computational Communication Research (journal)"
        url: "https://computationalcommunication.org/"
      - name: "Social Media + Society (journal)"
        url: "https://journals.sagepub.com/home/sms"
      - name: "Salganik — Bit by Bit (free online)"
        url: "https://www.bitbybitbook.com/"
  - week: 2
    date: "Week 2"
    topic: "Python Refresher and Data Wrangling"
    description: "Pandas DataFrames, JSON parsing, datetime handling, environment setup."
    materials:
      - name: "Google Colab"
        url: "https://colab.research.google.com/"
      - name: "pandas User Guide"
        url: "https://pandas.pydata.org/docs/user_guide/index.html"
  - week: 3
    date: "Week 3"
    topic: "Collecting Data via APIs"
    description: "REST API fundamentals, authentication, rate limits, pagination; Reddit API and YouTube Data API."
    materials:
      - name: "PRAW (Reddit API for Python)"
        url: "https://praw.readthedocs.io/en/stable/"
      - name: "YouTube Data API v3"
        url: "https://developers.google.com/youtube/v3"
      - name: "Requests Library"
        url: "https://docs.python-requests.org/en/latest/"
  - week: 4
    date: "Week 4"
    topic: "Web Scraping Social Media"
    description: "Scraping public pages with BeautifulSoup and Playwright; legal and ethical boundaries."
    materials:
      - name: "Beautiful Soup Documentation"
        url: "https://www.crummy.com/software/BeautifulSoup/bs4/doc/"
      - name: "Playwright for Python"
        url: "https://playwright.dev/python/"
      - name: "hiQ v. LinkedIn (court case overview)"
        url: "https://en.wikipedia.org/wiki/HiQ_Labs_v._LinkedIn"
  - week: 5
    date: "Week 5"
    topic: "Descriptive Analytics: Engagement and Audience"
    description: "Like/share/comment distributions, posting patterns, user growth, power-law distributions."
    materials:
      - name: "seaborn Gallery"
        url: "https://seaborn.pydata.org/examples/index.html"
      - name: "Plotly Express"
        url: "https://plotly.com/python/plotly-express/"
  - week: 6
    date: "Week 6"
    topic: "Text Analysis of Social Media"
    description: "Preprocessing tweets and posts; n-grams; TF-IDF; emoji and hashtag handling."
    materials:
      - name: "spaCy"
        url: "https://spacy.io/"
      - name: "emoji Python Library"
        url: "https://pypi.org/project/emoji/"
      - name: "NLTK Book"
        url: "https://www.nltk.org/book/"
  - week: 7
    date: "Week 7"
    topic: "Sentiment and Opinion Mining"
    description: "VADER, transformer-based classifiers (e.g., Twitter-roBERTa), aspect-level sentiment."
    materials:
      - name: "VADER Sentiment"
        url: "https://github.com/cjhutto/vaderSentiment"
      - name: "Twitter-roBERTa (Hugging Face)"
        url: "https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment"
      - name: "Hugging Face Transformers"
        url: "https://huggingface.co/docs/transformers"
  - week: 8
    date: "Week 8"
    topic: "Topic Modeling Social Media Corpora"
    description: "LDA vs. BERTopic on short text; tuning for social media noise; visualising topic change over time."
    materials:
      - name: "BERTopic"
        url: "https://maartengr.github.io/BERTopic/index.html"
      - name: "Gensim LDA"
        url: "https://radimrehurek.com/gensim/auto_examples/tutorials/run_lda.html"
  - week: 9
    date: "Week 9"
    topic: "Network Analysis: Structure and Diffusion"
    description: "Mention, retweet, and follower networks; centrality, clustering, communities; information cascades."
    materials:
      - name: "NetworkX Documentation"
        url: "https://networkx.org/documentation/stable/"
      - name: "Gephi"
        url: "https://gephi.org/"
      - name: "Networks, Crowds, and Markets (Easley & Kleinberg — free)"
        url: "https://www.cs.cornell.edu/home/kleinber/networks-book/"
  - week: 10
    date: "Week 10"
    topic: "Misinformation and Coordinated Behaviour"
    description: "Bot detection, coordinated inauthentic behaviour, echo chambers, fact-checking datasets."
    materials:
      - name: "Botometer (OSoMe)"
        url: "https://botometer.osome.iu.edu/"
      - name: "OSoMe Tools"
        url: "https://osome.iu.edu/tools/"
      - name: "Ferrara et al. 2016 — The Rise of Social Bots"
        url: "https://dl.acm.org/doi/10.1145/2818717"
  - week: 11
    date: "Week 11"
    topic: "LLMs as Research Tools"
    description: "Prompting GPT-4 / Claude for content coding, entity extraction, and synthetic annotation; validation."
    materials:
      - name: "OpenAI API"
        url: "https://platform.openai.com/docs/"
      - name: "Anthropic API"
        url: "https://docs.anthropic.com/"
      - name: "Pangakis et al. 2023 — Automated Annotation with GPT-4"
        url: "https://arxiv.org/abs/2302.13007"
  - week: 12
    date: "Week 12"
    topic: "Ethics and Responsible Research"
    description: "IRB considerations, informed consent for scraped data, anonymisation, platform ToS, GDPR basics."
    materials:
      - name: "AoIR Ethics Guidelines"
        url: "https://aoir.org/ethics/"
      - name: "ACM Code of Ethics"
        url: "https://www.acm.org/code-of-ethics"
  - week: 13
    date: "Week 13"
    topic: "Final Project Presentations"
    description: "Students present original social media analytics projects to the class and invited guests."
    materials:
---

## Course Overview

This applied graduate course equips students with the full pipeline for social media research: collecting data from APIs, analysing text and network structure, and interpreting findings in the context of communication theory. Special attention is paid to ethical and methodological rigour.

## Learning Objectives

By the end of this course, students will be able to:

- Collect social media data via REST APIs and responsible web scraping
- Analyse linguistic patterns, sentiment, and topics in large text corpora
- Construct and characterise social networks from interaction data
- Apply large language models as annotation and classification aids
- Design ethically sound social media research studies

## Prerequisites

- Intermediate Python (Introduction to Python or equivalent)
- Familiarity with basic statistics and social science research design

## Level

Graduate

## Institution

Department of Communications and New Media, National University of Singapore

## Key Tools and Libraries

| Tool | Purpose | Link |
|------|---------|------|
| PRAW | Reddit API client | [praw.readthedocs.io](https://praw.readthedocs.io/) |
| YouTube Data API | YouTube data | [developers.google.com/youtube](https://developers.google.com/youtube/v3) |
| spaCy | NLP preprocessing | [spacy.io](https://spacy.io/) |
| Hugging Face | Transformer models | [huggingface.co](https://huggingface.co/) |
| NetworkX | Network analysis | [networkx.org](https://networkx.org/) |
| Gephi | Network visualisation | [gephi.org](https://gephi.org/) |
| BERTopic | Topic modelling | [maartengr.github.io/BERTopic](https://maartengr.github.io/BERTopic/) |
| Botometer | Bot detection | [botometer.osome.iu.edu](https://botometer.osome.iu.edu/) |

## Recommended Readings

- Salganik, M. J. (2017). [*Bit by Bit: Social Research in the Digital Age*](https://www.bitbybitbook.com/) — free online.
- Grimmer, J., Roberts, M. E., & Stewart, B. M. (2022). [*Text as Data*](https://press.princeton.edu/books/paperback/9780691207551/text-as-data). Princeton UP.
- Easley, D. & Kleinberg, J. (2010). [*Networks, Crowds, and Markets*](https://www.cs.cornell.edu/home/kleinber/networks-book/) — free online.

## Assessment

| Component | Weight |
|-----------|--------|
| Weekly labs | 30% |
| Research design memo | 15% |
| Final project | 45% |
| Participation | 10% |
