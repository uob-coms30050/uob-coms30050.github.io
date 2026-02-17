---
layout: default
title: Lab 5
---

[Home](../index) \| [Assessment Information](../assessment-information) \| [Refresher](../refresher) \| [Blackboard Page](https://www.ole.bris.ac.uk/ultra/courses/_264181_1/outline) \| [Blackboard Forum](https://www.ole.bris.ac.uk/ultra/courses/_264181_1/engagement) \| [Unit Catalogue](https://upc.bristol.ac.uk/unit-programme-catalogue/UnitDetails.jsa?ayrCode=25%2F26&unitCode=COMS30050)
<br/>
[Data Projects](../data-projects) | Labs: [1](1-data-ingress) | [2](2-data-privacy-ethics) | [3](3-graph-database) | [4](4-exploration) | [5](5-visualisation)

---

# Lab 5: Data Visualisation

The lab builds on the lectures on Data Visualization and Data Science in Production. The lab will involve applying data visualization techniques using Plotly (<https://plotly.com>). Plotly is a graphing library which can be used to create interactive data visualizations.

Plotly (Plotly.js) is available on Python as well as Javascript. Plotly.js (<https://plotly.com/javascript/>) is built on top of D3.js (<https://d3js.org/>), but does not require an in-depth knowledge of concepts such as DOM and SVG. An interactive visualization created by Laura Gemmell (researcher in robotics; one of the previous TAs) using Plotly.js is linked with the other resources.

Plotly's Python package (<https://plotly.com/python/>), also called Plotly.py, is wrapper around Plotly.js. It is also available for R. Plotly Dash is another tool that is available to create interactive dashboards using the Plotly package within Python. Plotly Dash can be used in Juypter notebooks. We will use Plotly.py for this lab.

We will use the World Bank Education dataset for the visualization lab session. This education dataset contains 162 education related indicators for various countries and regions of the world. The World Bank Education data spans from the year 1960 to the year 2022.

## Prerequisites

- Go through lecture material
- Install Plotly for Python
  - For pip: pip install plotly==5.19.0
  - For conda:  conda install -c plotly plotly=5.19.0
- Download the World Bank Education dataset
  - <https://api.worldbank.org/v2/en/topic/4?downloadformat=csv>

## Lab Tasks

- Download the Python notebook [Plotly_WorldBankEducationData-v1.ipynb](https://www.ole.bris.ac.uk/bbcswebdav/xid-75361445_2)

It contains sample code to load the World Bank Education dataset and generate basic plots using Plotly. [You may need to update the code with correct dataset path and file name]  
You will use this notebook during the lab session

- Consider referring to these visualization tutorials on Plotly, Matplotlib, and Seaborn:
  - <https://www.kaggle.com/code/kanncaa1/plotly-tutorial-for-beginners>
  - <https://www.kaggle.com/code/saurav9786/seaborn-tutorial>


## Other Resources For Visualization

- Laura Gemmell's example of Plotly.js to create an interactive flocking simulation: 
  - Download or clone the [Github repository](https://github.com/lauralikespi/flocking)
  - Open the flocking.html file in a browser
- Matplotlib (<https://matplotlib.org/stable/gallery/index.html>)
- Seaborn (<https://seaborn.pydata.org/examples/index.html>)
