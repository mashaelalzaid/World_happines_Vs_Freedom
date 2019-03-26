# What came first, Happiness or Freedom?
A Data Driven study of the relationship between Human Freedoms and Happiness

# important note
kindly note that due to the fact that the graphs are animated, the GitHub can't present them directly, the notebook needs to be downloaded and the cell should be ran to see the animated graph as the video shows. After downloading the notebook in your device, follow the following steps:
1. Go to your Terminal/CMD
2. Enter (jupyter notebook) to start the localhost
3. Navigate to wher the notebook is located
4. Click the notebook
5. click (Kernel > restart and run all)
6. Enjoy the viz :D

# Objective

Studying the major factors of happiness and human freedom studies have always been a hot area of research for its direct impact on peoples' lives. Ruut Veenhoven studied the relationship between freedoms and happiness in 46 nations in the early 1990's and showed in his research that freedom does not always breed happiness, and suggested that economic freedom deserves priority (link to a paper: https://personal.eur.nl/veenhoven/Pub2000s/2000a-full.pdf) This project aims to utilize the available data in recent years and explore the relationship between world happiness and human freedom using Machine Learning and Visualization.

## Datasets
This project used 3 datasets (Human Freedom Index, World Happiness Dataset (2015) and World Happiness Dataset (2016)).
Human Freedom Index Dataset was conducted by CATO institute and other organizations,  The report used 2016 as the latest year because it is the most recent year for which sufficient data are available. There are  37 variables covering 162 countries presented in the Economic Freedom of the World report. (Data is available on: https://www.kaggle.com/gsutters/the-human-freedom-index). On the other hands, World Happiness Dataset which was conducted by the united nations, the data is extracted from Gallup World Poll, where a survey that ask people to evaluate certain features in a scale of 10, where 0 is worst and 10 is best (Data is available on: https://www.kaggle.com/unsdsn/world-happiness)


## Installation
install required packages for the project.

```python
from IPython.core.display import HTML
from string import Template
import pandas as pd
import os
import json, random
import matplotlib.pyplot as plt
%matplotlib inline
plt.style.use('bmh')
#get the d3 host remotely
HTML('<script src=https://d3js.org/d3.v4.min.js></script>')
from plotly.offline import init_notebook_mode, iplot
from IPython.display import display, HTML
init_notebook_mode(connected=True)
import plotly.graph_objs as go
import numpy as np
from plotly.offline import download_plotlyjs, init_notebook_mode, plot, iplot

```
## Source Code and Viz
(Code and Viz are available on: https://github.com/mashaelalzaid/World_happines_Vs_Freedom/blob/master/HF_WH.ipynb)

## Video
(Video is available on: https://youtu.be/QuNC9iVlP5w)

## Contributing
Pull requests are welcome.

## Contact
For further inquiries, contact me at: Mashaelalzaid@gmail.com
