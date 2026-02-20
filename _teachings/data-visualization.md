---
layout: course
title: Data Visualization
description: A graduate course covering principles and practices of data visualization, with a focus on theory, tools, and best practices for communicating data insights effectively.
instructor: Zhicong Chen
year: 2025
term: Spring
location: Nanjing University
course_id: data-visualization
schedule:
  - week: 1
    date: "Week 1"
    topic: "Why Visualize Data?"
    description: "The power and limits of visualization; pre-attentive attributes; Anscombe's quartet; Datasaurus."
    materials:
      - name: "Visualization Analysis & Design (Munzner) — Chapter 1"
        url: "https://www.cs.ubc.ca/~tmm/vadbook/"
      - name: "Anscombe's Quartet on Wikipedia"
        url: "https://en.wikipedia.org/wiki/Anscombe%27s_quartet"
      - name: "The Datasaurus Dozen"
        url: "https://www.autodesk.com/research/publications/same-stats-different-graphs"
  - week: 2
    date: "Week 2"
    topic: "Perception and Visual Encoding"
    description: "Stevens' power law, Weber-Fechner, Cleveland & McGill rankings, the grammar of graphics."
    materials:
      - name: "Cleveland & McGill 1984 (JSTOR)"
        url: "https://www.jstor.org/stable/2288400"
      - name: "A Layered Grammar of Graphics (Wickham)"
        url: "https://vita.had.co.nz/papers/layered-grammar.html"
  - week: 3
    date: "Week 3"
    topic: "Colour in Visualization"
    description: "Colour models, sequential vs. diverging vs. categorical palettes, colour blindness, ColorBrewer."
    materials:
      - name: "ColorBrewer 2.0"
        url: "https://colorbrewer2.org/"
      - name: "Choosing Color Palettes (seaborn docs)"
        url: "https://seaborn.pydata.org/tutorial/color_palettes.html"
      - name: "Viz Palette Tool"
        url: "https://projects.susielu.com/viz-palette"
  - week: 4
    date: "Week 4"
    topic: "Charting with Python: matplotlib & seaborn"
    description: "Figure/axes model, common chart types, annotation, themes, saving publication-quality figures."
    materials:
      - name: "matplotlib Tutorials"
        url: "https://matplotlib.org/stable/tutorials/index.html"
      - name: "seaborn Tutorial"
        url: "https://seaborn.pydata.org/tutorial.html"
      - name: "Scientific Visualization (Rougier) — free PDF"
        url: "https://github.com/rougier/scientific-visualization-book"
  - week: 5
    date: "Week 5"
    topic: "Interactive Visualization with Plotly & Altair"
    description: "Hover tooltips, zoom/pan, linked brushing, declarative grammars."
    materials:
      - name: "Plotly Express Documentation"
        url: "https://plotly.com/python/plotly-express/"
      - name: "Altair Documentation"
        url: "https://altair-viz.github.io/"
  - week: 6
    date: "Week 6"
    topic: "Web-Based Visualization with D3.js"
    description: "DOM manipulation, data binding, scales and axes, transitions, the D3 ecosystem."
    materials:
      - name: "D3.js Official Site"
        url: "https://d3js.org/"
      - name: "Observable Notebook Gallery"
        url: "https://observablehq.com/@d3/gallery"
      - name: "D3 in Depth"
        url: "https://www.d3indepth.com/"
  - week: 7
    date: "Week 7"
    topic: "Geospatial Visualization"
    description: "Projections, choropleths, flow maps, dot density, GeoPandas, Folium, Leaflet."
    materials:
      - name: "GeoPandas Documentation"
        url: "https://geopandas.org/en/stable/"
      - name: "Folium Documentation"
        url: "https://python-visualization.github.io/folium/"
      - name: "Kepler.gl (web tool)"
        url: "https://kepler.gl/"
  - week: 8
    date: "Week 8"
    topic: "Network Visualization"
    description: "Node-link diagrams, adjacency matrices, force-directed layouts, Gephi, networkx drawing."
    materials:
      - name: "Gephi"
        url: "https://gephi.org/"
      - name: "NetworkX Drawing"
        url: "https://networkx.org/documentation/stable/reference/drawing.html"
      - name: "Pyvis Interactive Networks"
        url: "https://pyvis.readthedocs.io/en/latest/"
  - week: 9
    date: "Week 9"
    topic: "Text and Time-Series Visualization"
    description: "Word clouds (and their pitfalls), alluvial diagrams, small multiples, horizon charts."
    materials:
      - name: "WordCloud Python Library"
        url: "https://amueller.github.io/word_cloud/"
      - name: "Small Multiples (Tufte)"
        url: "https://en.wikipedia.org/wiki/Small_multiple"
  - week: 10
    date: "Week 10"
    topic: "Dashboard Design with Streamlit"
    description: "Building interactive data apps with Streamlit; layout, widgets, caching."
    materials:
      - name: "Streamlit Documentation"
        url: "https://docs.streamlit.io/"
      - name: "Streamlit Gallery"
        url: "https://streamlit.io/gallery"
  - week: 11
    date: "Week 11"
    topic: "Communicating Uncertainty"
    description: "Error bars, confidence intervals, fan charts, probability distributions, frequency framing."
    materials:
      - name: "How to visualize uncertainty (Moritz Stefaner)"
        url: "https://www.visualisingdata.com/2022/01/ten-directions-in-data-visualisation-for-2022/"
      - name: "NYT Election Forecast Needle"
        url: "https://www.nytimes.com/elections"
  - week: 12
    date: "Week 12"
    topic: "Ethics, Accessibility, and Misleading Visuals"
    description: "Truncated axes, dual axes, cherry-picking, WCAG colour contrast, alt-text best practices."
    materials:
      - name: "Calling Bullshit (Bergstrom & West)"
        url: "https://www.callingbullshit.org/"
      - name: "WCAG Contrast Checker"
        url: "https://webaim.org/resources/contrastchecker/"
  - week: 13
    date: "Week 13"
    topic: "Final Project Critique"
    description: "Peer review of draft visualisation projects; instructor feedback on design and coding."
    materials:
---

## Course Overview

This course covers the theory and practice of data visualization for graduate students in journalism and communication. Students learn to design effective visualisations and implement them with Python (matplotlib, seaborn, Plotly, Altair) and D3.js, and to critically evaluate design choices.

## Learning Objectives

By the end of this course, students will be able to:

- Explain the perceptual and cognitive principles behind effective data visualisation
- Select appropriate chart types and visual encodings for different data and tasks
- Implement static and interactive visualisations in Python and D3.js
- Build and deploy a simple interactive data dashboard
- Critique visualisations for accuracy, clarity, and accessibility

## Prerequisites

- Proficiency in Python and pandas (equivalent to the Introduction to Python course)
- Basic familiarity with HTML/CSS is helpful for the D3.js module

## Level

Graduate

## Institution

School of Journalism and Communication, Nanjing University

## Offered

Spring 2025

## Required Texts

- Munzner, T. (2014). [*Visualization Analysis and Design*](https://www.cs.ubc.ca/~tmm/vadbook/). CRC Press.
- Cairo, A. (2016). [*The Truthful Art*](http://www.thefunctionalart.com/p/the-truthful-art-book.html). New Riders.

## Recommended Resources

| Resource | Link |
|----------|------|
| matplotlib Documentation | [matplotlib.org](https://matplotlib.org/) |
| seaborn Documentation | [seaborn.pydata.org](https://seaborn.pydata.org/) |
| Plotly Python | [plotly.com/python](https://plotly.com/python/) |
| Altair | [altair-viz.github.io](https://altair-viz.github.io/) |
| D3.js | [d3js.org](https://d3js.org/) |
| Observable (D3 examples) | [observablehq.com](https://observablehq.com/@d3/gallery) |
| ColorBrewer | [colorbrewer2.org](https://colorbrewer2.org/) |
| Gephi | [gephi.org](https://gephi.org/) |
| Streamlit | [streamlit.io](https://streamlit.io/) |
| Datawrapper | [datawrapper.de](https://www.datawrapper.de/) |

## Inspiration

- [Information is Beautiful](https://informationisbeautiful.net/)
- [FlowingData](https://flowingdata.com/)
- [The Pudding](https://pudding.cool/)
- [Observable Featured Notebooks](https://observablehq.com/explore)
- [Kantar Information is Beautiful Awards](https://www.informationisbeautifulawards.com/)

## Assessment

| Component | Weight |
|-----------|--------|
| Weekly visualisation assignments | 35% |
| Midterm critique essay | 15% |
| Final visualisation project | 40% |
| Participation & peer critique | 10% |
