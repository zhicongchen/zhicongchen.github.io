---
layout: course
title: Introduction to Python
description: An undergraduate course introducing Python programming for data analysis, with applications in social science and communication research.
instructor: Zhicong Chen
year: 2024
term: Spring
location: Nanjing University
course_id: introduction-to-python
schedule:
  - week: 1
    date: "Week 1"
    topic: "Getting Started: Python & Jupyter"
    description: "Course overview, installing Python, working with Jupyter notebooks, basic syntax and data types."
    materials:
      - name: "Official Python Tutorial"
        url: "https://docs.python.org/3/tutorial/"
      - name: "Jupyter Quickstart"
        url: "https://jupyter.org/try"
      - name: "Google Colab (no install)"
        url: "https://colab.research.google.com/"
  - week: 2
    date: "Week 2"
    topic: "Variables, Types, and Operators"
    description: "Numbers, strings, booleans, type conversion, arithmetic and comparison operators."
    materials:
      - name: "Python Built-in Types"
        url: "https://docs.python.org/3/library/stdtypes.html"
  - week: 3
    date: "Week 3"
    topic: "Data Structures: Lists, Dicts, Sets"
    description: "Choosing the right container; indexing, slicing, and mutability."
    materials:
      - name: "Python Data Structures Docs"
        url: "https://docs.python.org/3/tutorial/datastructures.html"
  - week: 4
    date: "Week 4"
    topic: "Control Flow: Conditionals and Loops"
    description: "if/elif/else, for loops, while loops, list comprehensions."
    materials:
      - name: "Control Flow Tools"
        url: "https://docs.python.org/3/tutorial/controlflow.html"
  - week: 5
    date: "Week 5"
    topic: "Functions and Modules"
    description: "Defining functions, arguments, return values, scope, importing standard-library modules."
    materials:
      - name: "Defining Functions"
        url: "https://docs.python.org/3/tutorial/controlflow.html#defining-functions"
      - name: "Python Standard Library"
        url: "https://docs.python.org/3/library/index.html"
  - week: 6
    date: "Week 6"
    topic: "Working with Files and the OS"
    description: "Reading/writing text and CSV files, pathlib, os.path."
    materials:
      - name: "Reading and Writing Files"
        url: "https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files"
  - week: 7
    date: "Week 7"
    topic: "NumPy: Numerical Computing"
    description: "Arrays, vectorised operations, broadcasting, random number generation."
    materials:
      - name: "NumPy Quickstart Tutorial"
        url: "https://numpy.org/doc/stable/user/quickstart.html"
      - name: "NumPy for Absolute Beginners"
        url: "https://numpy.org/doc/stable/user/absolute_beginners.html"
  - week: 8
    date: "Week 8"
    topic: "pandas: Data Manipulation"
    description: "DataFrames, Series, loading CSV/Excel, filtering, groupby, merging."
    materials:
      - name: "10 Minutes to pandas"
        url: "https://pandas.pydata.org/docs/user_guide/10min.html"
      - name: "pandas User Guide"
        url: "https://pandas.pydata.org/docs/user_guide/index.html"
  - week: 9
    date: "Week 9"
    topic: "Data Cleaning and Transformation"
    description: "Handling missing values, duplicates, type casting, string operations, apply()."
    materials:
      - name: "Working with Missing Data"
        url: "https://pandas.pydata.org/docs/user_guide/missing_data.html"
      - name: "Text Data in pandas"
        url: "https://pandas.pydata.org/docs/user_guide/text.html"
  - week: 10
    date: "Week 10"
    topic: "Visualization with matplotlib & seaborn"
    description: "Line plots, bar charts, scatter plots, histograms, heatmaps, and style customisation."
    materials:
      - name: "matplotlib Tutorials"
        url: "https://matplotlib.org/stable/tutorials/index.html"
      - name: "seaborn Gallery"
        url: "https://seaborn.pydata.org/examples/index.html"
  - week: 11
    date: "Week 11"
    topic: "Fetching Data: APIs and Web Scraping"
    description: "HTTP requests with requests library, parsing HTML with BeautifulSoup, working with JSON."
    materials:
      - name: "Requests Library Docs"
        url: "https://docs.python-requests.org/en/latest/"
      - name: "Beautiful Soup Docs"
        url: "https://www.crummy.com/software/BeautifulSoup/bs4/doc/"
  - week: 12
    date: "Week 12"
    topic: "Mini-Project Presentations"
    description: "Students present end-to-end data analyses of a self-chosen social or communication topic."
    materials:
      - name: "Anaconda Distribution"
        url: "https://www.anaconda.com/download"
---

## Course Overview

This course gives undergraduate students a practical foundation in Python programming, with a focus on data analysis tasks common in journalism, communication, and social science research. No prior programming experience is required.

## Learning Objectives

By the end of this course, students will be able to:

- Write clean, readable Python scripts and Jupyter notebooks
- Load, clean, and transform tabular data with **pandas**
- Produce publication-quality charts with **matplotlib** and **seaborn**
- Collect data from web APIs and perform basic web scraping
- Complete an end-to-end data analysis project independently

## Prerequisites

No prior programming experience required. Familiarity with spreadsheets (Excel / Google Sheets) is helpful but not mandatory.

## Level

Undergraduate

## Institution

School of Journalism and Communication, Nanjing University

## Offered

Spring 2024

## Required Textbook

McKinney, W. (2022). [*Python for Data Analysis*, 3rd ed.](https://wesmckinney.com/book/) — freely available online. O'Reilly.

## Key Tools

| Tool | Purpose | Link |
|------|---------|------|
| Python 3 | Core language | [python.org](https://www.python.org/) |
| Jupyter Notebook | Interactive coding environment | [jupyter.org](https://jupyter.org/) |
| Google Colab | Cloud-based Jupyter (no setup) | [colab.research.google.com](https://colab.research.google.com/) |
| pandas | Data manipulation | [pandas.pydata.org](https://pandas.pydata.org/docs/) |
| NumPy | Numerical computing | [numpy.org](https://numpy.org/doc/) |
| matplotlib | Plotting | [matplotlib.org](https://matplotlib.org/) |
| seaborn | Statistical visualisation | [seaborn.pydata.org](https://seaborn.pydata.org/) |
| Requests + BeautifulSoup | Web scraping | [requests](https://docs.python-requests.org/en/latest/) |
| Anaconda | All-in-one installer | [anaconda.com](https://www.anaconda.com/download) |

## Assessment

| Component | Weight |
|-----------|--------|
| Weekly coding exercises | 40% |
| Midterm project | 20% |
| Final data analysis project | 35% |
| Participation | 5% |
